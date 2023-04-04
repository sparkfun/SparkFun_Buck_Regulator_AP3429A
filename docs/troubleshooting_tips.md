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

On the Buck Regulator boards, users can short/[jumper](https://www.sparkfun.com/products/9044) the [`VIN`](../hardware_overview/#power "Input Voltage") and [`EN`](../hardware_overview/#power-control "Enable Pin") pins. This will bypass the undervoltage lockout setting and allow users to provide a lower input voltage. However, it should be noted that because this is a step-down converter and the input voltage should remain higher than the regulated output voltage.


## Connecting Batteries
For lower current applications, users can connect a battery as the power source. However, please be aware of the input voltage range for each board and the limitations of utilizing rechargeable batteries. We recommend a 3xAA battery pack and AA alkaline batteries for novice users to avoid technical complications.

<table class="pdf">
	<tr>
		<td>
			<a href="https://www.sparkfun.com/products/10891">
				<center><img src="https://cdn.sparkfun.com/r/140-140/assets/parts/5/9/7/5/10891-01b.jpg">
				</center>
				<h3 class="title">Battery Holder 3xAA with Cover and Switch - Bare Wire</h3>
			</a>
			PRT-10891
		</td>
		<td>
			<a href="https://www.sparkfun.com/products/15201">
				<center><img src="https://cdn.sparkfun.com/r/140-140/assets/parts/1/3/6/2/5/15201-Panasonic_Alkaline_Battery_-_AA-02.jpg">
				</center>
				<h3 class="title">Panasonic Alkaline Battery - AA</h3>
			</a>
			PRT-15201
		</td>
    </tr>
</table>


<div class="grid cards hide" markdown>

-   <a href="https://www.sparkfun.com/products/10891">**Battery Holder 3xAA with Cover and Switch - Bare Wire**<br>
	PRT-10891

	---

	<figure markdown>
	![](https://cdn.sparkfun.com/assets/parts/5/9/7/5/10891-01b.jpg)
	</figure></a>

-   <a href="https://www.sparkfun.com/products/15201">**Panasonic Alkaline Battery - AA**<br>
	PRT-15201

	---

	<figure markdown>
	![](https://cdn.sparkfun.com/assets/parts/1/3/6/2/5/15201-Panasonic_Alkaline_Battery_-_AA-02.jpg)
	</figure>
	</a>

</div>

!!! tip " Lithium Ion Batteries"
    While lithium polymer batteries have a nominal voltage of 3.7V, the voltage will vary as it is discharged. These types of batteries often have a range of approximately **3.2V** to **4.2V** and will be damaged if their voltage exceeds these parameters. Therefore, we recommend that users only connect LiPo batteries with a protection circuit from the manufacturer.

    !!! warning
        For example, the [18650 lithium-ion batteries](https://www.sparkfun.com/products/12895) in our catalog don't include a battery protection circuit. If used with the 1.8V buck regulator and left to discharge below 3.2V, the battery would be permanently damaged and rendered useless.
        
        There is no way to recover the battery from this type of damage. *(While there are hacks to get the battery working again, its performance will be significantly reduced.)*

    !!! info
        With an undervoltage threshold of 3.7V, [3.3V buck regulator](https://www.sparkfun.com/products/21337) will not be able to utilize the full capacity of a LiPo battery. The board will be unable to access the last 40-50% of the LiPo battery's charge capacity.