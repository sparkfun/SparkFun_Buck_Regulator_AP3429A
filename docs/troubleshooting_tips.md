---
icon: sfe-logo
---

!!! warning "Need Help?"
    If you need technical assistance or more information on a product that is not working as you expected, we recommend heading on over to the [SparkFun Technical Assistance](https://www.sparkfun.com/technical_assistanc) page for some initial troubleshooting.

    <center>
    [SparkFun Technical Assistance Page](https://www.sparkfun.com/technical_assistance){ .md-button .md-button--primary }
    </center>
    
    If you can't find what you need there, the [SparkFun Forums](https://forum.sparkfun.com/index.php) is a great place to search product forums and ask questions.
    
    !!! info "Account Registration Required"
        If this is your first visit to our forum, you'll need to create a [Forum Account](https://forum.sparkfun.com/ucp.php?mode=register) to post questions.

## Bypass the UVLO
!!! info "Default Configuration"
    On our boards, the `EN` pin is pulled-up to enable the power output from the board by default.

On the Buck Regulator boards, users can short/jumper the [`VIN`](../hardware_overview/#power "Input Voltage") and [`EN`](../hardware_overview/#power-control "Enable Pin") pins. This will bypass the undervoltage lockout setting and allow users to provide a lower input voltage. However, it should be noted that because this is a step-down converter and the input voltage should remain higher than the regulated output voltage.

<figure markdown>
[![](../img/hookup_guide/assembly-bypass-400.gif)](../img/hookup_guide/assembly-bypass.gif "Click to enlarge")
<figcaption markdown>
Jumpering the `EN` and `VIN` pins on the Buck Regulator to bypass the [UVLO]("undervoltage lockout").
</figcaption>
</figure>
