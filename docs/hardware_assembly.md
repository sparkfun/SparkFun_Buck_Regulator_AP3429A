---
icon: material/tools
---

## :material-soldering-iron:&nbsp;Headers

??? note "New to soldering?"
	If you have never soldered before or need a quick refresher, check out our [How to Solder: Through-Hole Soldering](https://learn.sparkfun.com/tutorials/how-to-solder-through-hole-soldering) guide.
	<p align="center">
		<a href="https://learn.sparkfun.com/tutorials/5">How to Solder: Through-Hole Soldering<br>
		<img src="https://cdn.sparkfun.com/c/264-148/assets/e/3/9/9/4/51d9fbe1ce395f7a2a000000.jpg" alt="Tutorial's thumbnail"></a>
	</p>

The pins for the SparkFun AP3429A Buck Regulator Breakout boards are broken out to 0.1"-spaced pins on the outer edges of the board. When selecting headers, be sure you are aware of the functionality and board orientation required.

<figure markdown>
[![](../img/hookup_guide/assembly-header.jpg){ width="200" }](../img/hookup_guide/assembly-header.jpg "Click to enlarge")
<figcaption markdown>
Soldering headers to the AP3429A Buck Regulator Breakout boards.
</figcaption>
</figure>

??? tip "Jumper the Enable Pin"
	On the AP3429A Buck Regulator Breakout board, users can short the [`VIN`](../hardware_overview/#power "Input Voltage") and [`EN`](../hardware_overview/#power-control "Enable Pin") pins. This will allow users to bypass the undervoltage threshold and force the power output to be enabled.


## :material-soldering-iron:&nbsp;Hookup Wire
??? note "New to soldering?"
	If you have never soldered before or need a quick refresher, check out our [How to Solder: Through-Hole Soldering](https://learn.sparkfun.com/tutorials/how-to-solder-through-hole-soldering) guide.
	<p align="center">
		<a href="https://learn.sparkfun.com/tutorials/5">How to Solder: Through-Hole Soldering<br>
		<img src="https://cdn.sparkfun.com/c/264-148/assets/e/3/9/9/4/51d9fbe1ce395f7a2a000000.jpg" alt="Tutorial's thumbnail"></a>
	</p>

Users can also solder their wire connections directly to the pins of the AP3429A Buck Regulator breakout boards. When planning out the connections, be sure you are aware of the functionality required.

!!! danger
	With higher current applications, users should ensure the wires can handle the current load. *(i.e. A 32AWG wire probably won't be able to handle 2A)*

<figure markdown>
[![](../img/hookup_guide/assembly-wire.jpg){ width="200" }](../img/hookup_guide/assembly-wire.jpg "Click to enlarge")
<figcaption markdown>
Soldering wires to the AP3429A Buck Regulator Breakout boards.
</figcaption>
</figure>


## :material-soldering-iron:&nbsp;Barrel Jack PTH
??? note "New to soldering?"
	If you have never soldered before or need a quick refresher, check out our [How to Solder: Through-Hole Soldering](https://learn.sparkfun.com/tutorials/how-to-solder-through-hole-soldering) guide.
	<p align="center">
		<a href="https://learn.sparkfun.com/tutorials/5">How to Solder: Through-Hole Soldering<br>
		<img src="https://cdn.sparkfun.com/c/264-148/assets/e/3/9/9/4/51d9fbe1ce395f7a2a000000.jpg" alt="Tutorial's thumbnail"></a>
	</p>

A [barrel jack connector](https://www.sparkfun.com/products/119) can be added to the AP3429A Buck Regulator breakout boards. The plated through-hole slots allow the barrel jack connector to be oriented on the top or bottom of the board.


<div class="grid cards" markdown>

-   <figure markdown>
	[![](../img/hookup_guide/assembly-barrel_jack_top.jpg)](../img/hookup_guide/assembly-barrel_jack_top.jpg "Click to enlarge")
	<figcaption markdown>
	Soldering a [barrel jack connector](https://www.sparkfun.com/products/119) onto the top of the AP3429A Buck Regulator Breakout board.
	</figcaption>
	</figure>

-   <figure markdown>
	[![](../img/hookup_guide/assembly-barrel_jack_bottom.jpg)](../img/hookup_guide/assembly-barrel_jack_bottom.jpg "Click to enlarge")
	<figcaption markdown>
	Soldering a [barrel jack connector](https://www.sparkfun.com/products/119) onto the bottom of the AP3429A Buck Regulator Breakout board.
	</figcaption>
	</figure>

</div>


## :material-screwdriver:&nbsp;Screw Terminals
A screw terminal is a great non-permanent solution, to connect the board. To use the screw terminals, simply insert the correct wires into the screw terminal opening and tighten the screw with a small flathead screwdriver for a firm connection.

<figure markdown>
[![](../img/hookup_guide/assembly-screw_terminal.jpg){ width="200" }](../img/hookup_guide/assembly-screw_terminal.jpg "Click to enlarge")
<figcaption markdown>Connecting a wire to the AP3429A Buck Regulator Breakout Board's' screw terminal.</figcaption>
</figure>


## Battery Power
Unlike our previous buck converter breakouts, the output voltage for these AP3429A buck converters is low enough to be supplied by batteries. Users can connect batteries directly to the board, utilizing the screw terminals or PTH pins.

### :material-soldering-iron:&nbsp;2-Pin JST Connector
Another option is to solder on a [2-pin JST right-angle connector](https://www.sparkfun.com/products/9749). Make sure to note the polarity of the connections to the JST connector before attaching it to the board.

<figure markdown>
[![](../img/hookup_guide/assembly-jst.jpg){ width="200" }](../img/hookup_guide/assembly-jst.jpg "Click to enlarge")
<figcaption markdown>
Soldering a [2-pin JST right-angle connector](https://www.sparkfun.com/products/9749) to the AP3429A Buck Regulator Breakout boards.
</figcaption>
</figure>


This connector is compatible with several of our [LiPo batteries and battery packs](https://www.sparkfun.com/categories/54). Just make sure to select an option that is appropriate for your project.


<div class="grid cards" markdown>

-   <figure markdown>
	[![](../img/hookup_guide/assembly-battery_pack.jpg)](../img/hookup_guide/assembly-battery_pack.jpg "Click to enlarge")
	<figcaption markdown>
	The AP3429A Buck Regulator Breakout board powered by a [3xAA battery pack](https://www.sparkfun.com/products/18769).
	</figcaption>
	</figure>

-   <figure markdown>
	[![](../img/hookup_guide/assembly-battery_lipo.jpg)](../img/hookup_guide/assembly-battery_lipo.jpg "Click to enlarge")
	<figcaption markdown>
	The AP3429A Buck Regulator Breakout board powered by a [400mA LiPo battery](https://www.sparkfun.com/products/13851).
	</figcaption>
	</figure>

	!!! warning "LiPo Batteries"
		Utilize a LiPo battery with an undervoltage protection circuit. This will ensure that the buck regulator boards don't damage the battery as its energy is depleted.

</div>


!!! tip "Disconnecting Hardware"
    <p><b><span style="color:red">DO <u>NOT</u></span></b> remove batteries by pulling on their wires. Instead, it is recommended that pair of dikes (i.e. diagonal wire cutters), pliers, or tweezers be used to pull on the JST connector housing, to avoid damaging the battery wiring.</p>
    <p><center>
        <a href="https://docs.sparkfun.com/SparkFun_Thing_Plus_ESP32_WROOM_C/img/hookup_guide/assembly_batt_removal.jpg"><img alt="Disconnect battery w/ dikes" title="Click to enlarge" src="https://docs.sparkfun.com/SparkFun_Thing_Plus_ESP32_WROOM_C/img/hookup_guide/assembly_batt_removal.jpg" width="200"></a>
        <br>
        <i>Using a pair of dikes to disconnect a battery.</i>
    </center></p>


## Heat Sink
!!! tip
    With larger heat sinks, we recommend a test fit and attaching it last to avoid conflicts with other parts of the board. For example, the heat sink could block the PTH pins/slots or access to the jumper pad.

To attach a [heat sink](https://www.sparkfun.com/products/18704) to the board, users will also need a piece of [thermal tape](https://www.sparkfun.com/products/17054). We recommend the following procedure:

1. Cut out a piece of [thermal tape](https://www.sparkfun.com/products/17054) to fit the bottom of the [heat sink](https://www.sparkfun.com/products/18704).
	
	!!! tip
		Covering the entire bottom of the heat sink can insulate the electrical contacts on the board from shorting.

    * For a perfect fit, users can place the heat sink over the tape and trace the outline to cut with scissors.
    * For a perfect fit, users can also place the heat sink over the tape and cut the outline with a [hobby knife](https://www.sparkfun.com/products/9200).

2. Place the piece of thermal tape on the bottom of the heat sink.

	!!! tip
		We recommend peeling off just one side of the backing sheet or [release liner](https://en.wikipedia.org/wiki/Release_liner) to place the thermal tape on the heat sink. Users can then peel the other side off when they are ready to place the heat sink on their board.
	
3. Attach the heat sink to the board.
    * Make sure to make any jumper modifications and/or solder any connections before placing the heat sink on the board.
    * Make sure to avoid any electrical contact with the sides of the heat sink.


<div class="grid cards" markdown>

-   <figure markdown>
	[![](../img/hookup_guide/assembly-heat_sink_sizes.jpg)](../img/hookup_guide/assembly-heat_sink_sizes.jpg "Click to enlarge")
	<figcaption markdown>
	Different [heat sinks](https://www.sparkfun.com/categories/tags/heatsink) next to the AP3429A Buck Regulator Breakout board.
	</figcaption>
	</figure>

-   <figure markdown>
	[![](../img/hookup_guide/assembly-heat_sink.jpg)](../img/hookup_guide/assembly-heat_sink.jpg "Click to enlarge")
	<figcaption markdown>
	[Heat sink](https://www.sparkfun.com/products/18704) attached to the AP3429A Buck Regulator Breakout board.
	</figcaption>
	</figure>

</div>
