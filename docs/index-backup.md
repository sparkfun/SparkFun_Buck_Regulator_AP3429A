# Getting Started

!!! note
	The SparkFun Buck Regulator Breakout - [3.3V (AP3429A)](https://www.sparkfun.com/products/21337) and [1.8V (AP3429A)](https://www.sparkfun.com/products/21338) have similar features to our previous [buck regulators (AP63203 & AP63357)](https://www.sparkfun.com/categories/tags/buck-).


## Introduction
These boards feature the AP3429A from [Diodes Inc.](https://www.diodes.com/), a 2A step-down DC-DC converter with an input voltage range of 2.7V to 5.5V. They are configured to provide a regulated **3.3V** or **1.8V** output, which is controlled by an `EN` *(enable)* pin and indicated by a red power LED. A pre-assembled screw terminal and 0.1" spaced PTH pins are available to connect the input and output power of the boards. Additionally, there is the option to solder on a [barrel jack](https://www.sparkfun.com/products/119) for an [external power supply](https://www.sparkfun.com/categories/308). To dissipate excess heat, a 0.5" x 0.6" copper pad is provided to attach a heat sink to the bottom of the board.

<section class="grid cards show" style="grid-template-columns: repeat(auto-fit,minmax(8rem,1fr));" markdown>

-	[3.3V Buck Regulator (COM-21337)](https://www.sparkfun.com/products/21337)

	---

	<figure markdown>
	[![SparkFun Buck Regulator Breakout - 3.3V (AP3429A)](https://cdn.sparkfun.com/r/500-500/assets/parts/2/1/1/4/6/21337-_COM-_Buck_Regulator_3.3v-_01.jpg)](https://cdn.sparkfun.com/assets/parts/2/1/1/4/6/21337-_COM-_Buck_Regulator_3.3v-_01.jpg)
	</figure>

	This board provides a regulated **3.3V** output with an input voltage range of **3.9V - 5.5V**.

	<center>
	[Purchase from SparkFun :fontawesome-solid-cart-plus:{ .heart }](https://www.sparkfun.com/products/21337){ .md-button .md-button--primary }
	</center>

-	[1.8V Buck Regulator (COM-21338)](https://www.sparkfun.com/products/21338)

	---

	<figure markdown>
	[![SparkFun Buck Regulator Breakout - 1.8V (AP3429A)](https://cdn.sparkfun.com/r/500-500/assets/parts/2/1/1/4/7/21338-_COM-_Buck_Regulator_1.8v-_01.jpg)](https://cdn.sparkfun.com/assets/parts/2/1/1/4/7/21338-_COM-_Buck_Regulator_1.8v-_01.jpg)
	</figure>

	This board provides a regulated **1.8V** output with an input voltage range of **2.7V - 5.5V**.

	<center>
	[Purchase from SparkFun :fontawesome-solid-cart-plus:{ .heart }](https://www.sparkfun.com/products/21338){ .md-button .md-button--primary }
	</center>

</section>


## :fontawesome-solid-list-check::material-list-box::material-format-list-checks:&nbsp;Required Materials
To get started, users will need a few items. Now some users may already have a few of these items, feel free to modify your cart accordingly. For users just getting started with electronics, we have linked a few tutorials to establish a foundation of knowledge to follow along with this hookup guide.

* [SparkFun Buck Regulator Breakout - 3.3V (AP3429A)](https://www.sparkfun.com/products/21337)
* [Heat Sink](https://www.sparkfun.com/products/18704 "Thermal tape is included") - Used to help dissipate excess heat
    * [Thermal Tape](https://www.sparkfun.com/products/17054) - To attach a heat sink to the board
* [Power Supply](https://www.sparkfun.com/categories/307 "Click here for a full selection of our available power supplies")
* Soldering Tools (1)
{ .annotate }

	1.	Check out the beginner tool kit below; otherwise, click here for a full selection of our available [soldering tools](https://www.sparkfun.com/categories/49).

* [Hookup Wire](https://www.sparkfun.com/categories/141 "Click here for a full selection of our available wires.") - May be used to connect the external power or power output
* [Headers](https://www.sparkfun.com/categories/381 "Click here for a full selection of our available headers.")  - May be used to connect the external power or power output
* [DC Barrel Jack Adapter](https://www.sparkfun.com/products/119)
* [Small Flathead Screw Driver](https://www.sparkfun.com/categories/376 "Click here for a full selection of our available screwdrivers.")


<table class="pdf" style="border-style:none">
	<tr>
		<td>
			<a href="https://www.sparkfun.com/products/21338">
				<center><img src="https://cdn.sparkfun.com/r/140-140/assets/parts/2/1/1/4/7/21338-_COM-_Buck_Regulator_1.8v-_01.jpg" alt="SparkFun Buck Regulator Breakout - 3.3V (AP3429A)">
				</center>
				<h3 class="title">SparkFun Buck Regulator Breakout - 1.8V (AP3429A)</h3>
			</a>
			COM-21338
		</td>
		<td>
			<a href="https://www.sparkfun.com/products/21337">
				<center><img src="https://cdn.sparkfun.com/r/140-140/assets/parts/2/1/1/4/6/21337-_COM-_Buck_Regulator_3.3v-_01.jpg" alt="SparkFun Buck Regulator Breakout - 3.3V (AP3429A)">
				</center>
				<h3 class="title">SparkFun Buck Regulator Breakout - 3.3V (AP3429A)</h3>
			</a>
			COM-21337
		</td>
		<td>
			<a href="https://www.sparkfun.com/products/18704">
				<center><img src="https://cdn.sparkfun.com/r/140-140/assets/parts/1/8/2/3/7/18704-1.jpg" alt="Heatsink - 13.20 x 12.10 mm (Copper)"></center>
				<h3 class="title">Heatsink - 13.20 x 12.10 mm (Copper)</h3>
			</a>
			PRT-18704
		</td>
		<td>
			<a href="https://www.sparkfun.com/products/17054">
				<center><img src="https://cdn.sparkfun.com/r/140-140/assets/parts/1/6/0/0/0/17054-Thermal_Tape_4x4in._Square-01.jpg" alt="Thermal Tape 4x4" Square">
				</center>
				<h3 class="title">Thermal Tape 4x4" Square</h3>
			</a>
			PRT-17054
		</td>
	</tr>
	<tr>
		<td>
			<a href="https://www.sparkfun.com/products/14681">
				<center><img src="https://cdn.sparkfun.com/r/140-140/assets/parts/1/2/8/8/3/14681-SparkFun_Beginner_Tool_Kit.jpg" alt="SparkFun Beginner Tool Kit">
				</center>
				<h3 class="title">SparkFun Beginner Tool Kit</h3>
			</a>
			TOL-14681
		</td>
		<td>
			<a href="https://www.sparkfun.com/products/11367">
				<center><img src="https://cdn.sparkfun.com/r/140-140/assets/parts/7/1/0/8/11367-Hook-Up_Wire_-_Assortment__Solid_Core__22_AWG_-01.jpg" alt="Hook-Up Wire - Assortment (Solid Core, 22 AWG)"></center>
				<h3 class="title">Hook-Up Wire - Assortment (Solid Core, 22 AWG)</h3>
			</a>
			PRT-11367
		</td>
		<td>
			<a href="https://www.sparkfun.com/products/116">
				<center><img src="https://cdn.sparkfun.com/r/140-140/assets/parts/1/0/6/00116-02-L.jpg" alt="Break Away Headers - Straight"></center>
				<h3 class="title">Break Away Headers - Straight</h3>
			</a>
			PRT-00116
		</td>
		<td>
			<a href="https://www.sparkfun.com/products/119">
				<center><img src="https://cdn.sparkfun.com/r/140-140/assets/parts/1/0/8/00119-03-L.jpg" alt="DC Barrel Power Jack/Connector"></center>
				<h3 class="title">DC Barrel Power Jack/Connector</h3>
			</a>
			PRT-00119
		</td>
	</tr>
    <tr>
		<td>
			<a href="https://www.sparkfun.com/products/12891">
				<center><img src="https://cdn.sparkfun.com/r/140-140/assets/parts/9/7/8/3/12891-01.jpg" alt="Pocket Screwdriver Set">
				</center>
				<h3 class="title">Pocket Screwdriver Set</h3>
			</a>
			TOL-12891
		</td>
    </tr>
</table>

<div class="pdf" markdown>
!!! note "New to soldering?"
	Check out our [Through-Hole Soldering Tutorial](https://learn.sparkfun.com/tutorials/5) for a quick introduction!
	<p align="center">
		<a href="https://learn.sparkfun.com/tutorials/5">How to Solder: Through-Hole Soldering<br>
		<img src="https://cdn.sparkfun.com/c/264-148/assets/e/3/9/9/4/51d9fbe1ce395f7a2a000000.jpg" alt="Tutorial's thumbnail"></a>
	</p>
</div>


<div class="grid cards" markdown>

-   <a href="https://www.sparkfun.com/products/21337">**3.3V Buck Regulator Breakout - (AP3429A)**<br>
	COM-21337

	---

	<figure markdown>
	![SparkFun Buck Regulator Breakout - 3.3V (AP3429A)](https://cdn.sparkfun.com/assets/parts/2/1/1/4/6/21337-_COM-_Buck_Regulator_3.3v-_01.jpg)
	</figure></a>

-   <a href="https://www.sparkfun.com/products/21338">**1.8V Buck Regulator Breakout - (AP3429A)**<br>
	COM-21338

	---

	<figure markdown>
	![SparkFun Buck Regulator Breakout - 1.8V (AP3429A)](https://cdn.sparkfun.com/assets/parts/2/1/1/4/7/21338-_COM-_Buck_Regulator_1.8v-_01.jpg)
	</figure></a>

-   <a href="https://www.sparkfun.com/products/18704">**Heatsink - 13.20 x 12.10 mm (Copper)**<br>
	PRT-18704

	---

	<figure markdown>
	![Heatsink - 13.20 x 12.10 mm (Copper)](https://cdn.sparkfun.com/assets/parts/1/8/2/3/7/18704-1.jpg)
	</figure></a>

	!!! tip "Fits both boards."
	!!! info "Thermal tape is included."

-   <a href="https://www.sparkfun.com/products/17054">**Thermal Tape 4x4" Square**<br>
	PRT-17054

	---

	<figure markdown>
	![Thermal Tape 4x4" Square](https://cdn.sparkfun.com/assets/parts/1/6/0/0/0/17054-Thermal_Tape_4x4in._Square-01.jpg)
	</figure>
	</a>

-   <a href="https://www.sparkfun.com/products/14681">**SparkFun Beginner Tool Kit**<br>
	TOL-14681

	---

	<figure markdown>
	![SparkFun Beginner Tool Kit](https://cdn.sparkfun.com/assets/parts/1/2/8/8/3/14681-SparkFun_Beginner_Tool_Kit.jpg)
	</figure>
	</a>

	??? note "New to soldering?"
		Check out our [Through-Hole Soldering Tutorial](https://learn.sparkfun.com/tutorials/5) for a quick introduction!
		<p align="center">
			<a href="https://learn.sparkfun.com/tutorials/5">How to Solder: Through-Hole Soldering<br>
			<img src="https://cdn.sparkfun.com/c/264-148/assets/e/3/9/9/4/51d9fbe1ce395f7a2a000000.jpg" alt="Tutorial's thumbnail"></a>
		</p>

-   <a href="https://www.sparkfun.com/products/11367">**Hook-Up Wire - Assortment (Solid Core, 22 AWG)**<br>
	PRT-11367

	---

	<figure markdown>
	![Hook-Up Wire - Assortment (Solid Core, 22 AWG)](https://cdn.sparkfun.com/assets/parts/7/1/0/8/11367-Hook-Up_Wire_-_Assortment__Solid_Core__22_AWG_-01.jpg)
	</figure>
	</a>

-   <a href="https://www.sparkfun.com/products/116">**Break Away Headers - Straight**<br>
	PRT-00116

	---

	<figure markdown>
	![Break Away Headers - Straight](https://cdn.sparkfun.com/assets/parts/1/0/6/00116-02-L.jpg)
	</figure>
	</a>

-   <a href="https://www.sparkfun.com/products/119">**DC Barrel Power Jack/Connector**<br>
	PRT-00119

	---

	<figure markdown>
	![DC Barrel Power Jack/Connector](https://cdn.sparkfun.com/assets/parts/1/0/8/00119-03-L.jpg)
	</figure>
	</a>

-   <a href="https://www.sparkfun.com/products/12891">**Pocket Screwdriver Set**<br>
	TOL-12891

	---

	<figure markdown>
	![Pocket Screwdriver Set](https://cdn.sparkfun.com/assets/parts/9/7/8/3/12891-01.jpg)
	</figure>
	</a>

</div>



??? note "Jumper Modification"
	!!! tip "New to jumper pads?"
		Check out our [Jumper Pads and PCB Traces Tutorial](https://learn.sparkfun.com/tutorials/664) for a quick introduction!
		<p align="center">
			<a href="https://learn.sparkfun.com/tutorials/664">How to Work with Jumper Pads and PCB Traces<br>
			<img src="https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/6/6/4/PCB_TraceCutLumenati.jpg" alt="Tutorial's thumbnail"></a>
		</p>

	To modify the [jumper](hardware_overview/#jumper), users will need [soldering equipment](https://www.sparkfun.com/categories/49) and/or a [hobby knife](https://www.sparkfun.com/categories/379).


	<table class="pdf">
		<tr>
			<td>
				<a href="https://www.sparkfun.com/products/9325">
					<center><img src="https://cdn.sparkfun.com/r/140-140/assets/parts/2/8/7/3/09325_9161-Solder_Lead_Free_-_100-gram_Spool-01.jpg" alt="Solder Lead Free - 100-gram Spool"></center>
					<h3 class="title">Solder Lead Free - 100-gram Spool</h3>
				</a>
				TOL-09325
			</td>
			<td>
				<a href="https://www.sparkfun.com/products/14228">
					<center><img src="https://cdn.sparkfun.com/r/140-140/assets/parts/1/2/1/7/3/14228-01.jpg" alt="Weller WLC100 Soldering Station">
					</center>
					<h3 class="title">Weller WLC100 Soldering Station</h3>
				</a>
				TOL-14228
			</td>
			<td>
				<a href="https://www.sparkfun.com/products/14579">
					<center><img src="https://cdn.sparkfun.com/r/140-140/assets/parts/1/2/7/2/5/14579-Chip_Quik_No-Clean_Flux_Pen_-_10mL-01.jpg" alt="Chip Quik No-Clean Flux Pen - 10mL">
					</center>
					<h3 class="title">Chip Quik No-Clean Flux Pen - 10mL</h3>
				</a>
				TOL-14579
			</td>
			<td>
				<a href="https://www.sparkfun.com/products/9200">
					<center><img src="https://cdn.sparkfun.com/r/140-140/assets/parts/2/6/4/6/09200-Hobby_Knife-01.jpg" alt="Hobby Knife">
					</center>
					<h3 class="title">Hobby Knife</h3>
				</a>
				TOL-09200
			</td>
		</tr>
	</table>


	<div class="grid cards" markdown>

	-   <a href="https://www.sparkfun.com/products/9325">**Solder Lead Free - 100-gram Spool**<br>
		TOL-09325

		---

		<figure markdown>
		![Solder Lead Free - 100-gram Spool](https://cdn.sparkfun.com/assets/parts/2/8/7/3/09325_9161-Solder_Lead_Free_-_100-gram_Spool-01.jpg)
		</figure></a>

	-   <a href="https://www.sparkfun.com/products/14228">**Weller WLC100 Soldering Station**<br>
		TOL-14228

		---
		
		<figure markdown>
		![Weller WLC100 Soldering Station](https://cdn.sparkfun.com/assets/parts/1/2/1/7/3/14228-01.jpg)
		</figure></a>


	-   <a href="https://www.sparkfun.com/products/14579">**Chip Quik No-Clean Flux Pen - 10mL**<br>
		TOL-14579

		---

		<figure markdown>
		![Chip Quik No-Clean Flux Pen - 10mL](https://cdn.sparkfun.com/assets/parts/1/2/7/2/5/14579-Chip_Quik_No-Clean_Flux_Pen_-_10mL-01.jpg)
		</figure></a>


	-   <a href="https://www.sparkfun.com/products/9200">**Hobby Knife**<br>
		TOL-09200

		---

		<figure markdown>
		![Hobby Knife](https://cdn.sparkfun.com/assets/parts/2/6/4/6/09200-Hobby_Knife-01.jpg)
		</figure>
		</a>
	</div>



## :material-head-question: :books: Suggested Reading

As a more sophisticated product, we will skip over the more fundamental tutorials (i.e. [**Ohm's Law**](https://learn.sparkfun.com/tutorials/voltage-current-resistance-and-ohms-law) and [**What is Electricity?**](https://learn.sparkfun.com/tutorials/what-is-electricity)). However, below are a few tutorials that may help users familiarize themselves with various aspects of the board.


<table class="pdf">
	<tr>
		<td align="center">
			<a href="https://learn.sparkfun.com/tutorials/72">Electric Power<br>
			<img src="https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/7/2/PowerThumb.jpg"></a>
		</td>
		<td align="center">
			<a href="https://learn.sparkfun.com/tutorials/18">Connector Basics<br>
			<img src="https://cdn.sparkfun.com/c/264-148/assets/c/d/6/9/4/511421f8ce395f687e000007.jpg"></a>
		</td>
        <td align="center">
			<a href="https://learn.sparkfun.com/tutorials/41">Working with Wire<br>
			<img src="https://cdn.sparkfun.com/c/264-148/assets/0/5/0/0/f/5138de3cce395fbb1b000002.JPG"></a>
		</td>
		<td align="center">
			<a href="https://learn.sparkfun.com/tutorials/36">How to Power a Project<br>
			<img src="https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/3/6/Bench_Power_Supply.jpg"></a>
		</td>
    </tr>
	<tr>
		<td align="center">
			<a href="https://learn.sparkfun.com/tutorials/26">What is a Circuit?<br>
			<img src="https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/2/6/Concept_Tutorial_Images-03.jpg"></a>
		</td>
		<td align="center">
			<a href="https://learn.sparkfun.com/tutorials/115">Alternating Current (AC) vs. Direct Current (DC)<br>
			<img src="https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/1/1/5/acDC.jpg"></a>
		</td>
        <td align="center">
			<a href="https://learn.sparkfun.com/tutorials/75">Polarity<br>
			<img src="https://cdn.sparkfun.com/c/264-148/assets/5/4/1/e/0/5193d2adce395f3d7a000001.jpg"></a>
		</td>
		<td align="center">
			<a href="https://learn.sparkfun.com/tutorials/62">Logic Levels<br>
			<img src="https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/6/2/Input_Output_Logic_Level_Tolerances_tutorial_tile.png"></a>
		</td>
	</tr>
    <tr>
		<td align="center">
			<a href="https://learn.sparkfun.com/tutorials/1890">Buck Regulator Hookup Guide<br>
			<img src="https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/1/8/9/0/Thumbnail.png"></a>
		</td>
		<td align="center">
			<a href="https://learn.sparkfun.com/tutorials/5">How to Solder: Through-Hole Soldering<br>
			<img src="https://cdn.sparkfun.com/c/264-148/assets/e/3/9/9/4/51d9fbe1ce395f7a2a000000.jpg" alt="Tutorial's thumbnail"></a>
		</td>
		<td align="center">
			<a href="https://learn.sparkfun.com/tutorials/664">How to Work with Jumper Pads and PCB Traces<br>
			<img src="https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/6/6/4/PCB_TraceCutLumenati.jpg" alt="Tutorial's thumbnail"></a>
		</td>
	</tr>
</table>


<div class="grid cards" markdown align="center">

-   <a href="https://learn.sparkfun.com/tutorials/72">**Electric Power**

	---
	
	<figure markdown>
	![Electric Power](https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/7/2/PowerThumb.jpg)
	</figure></a>

-   <a href="https://learn.sparkfun.com/tutorials/18">**Connector Basics**

	---
	
	<figure markdown>
	![Connector Basics](https://cdn.sparkfun.com/c/264-148/assets/c/d/6/9/4/511421f8ce395f687e000007.jpg)
	</figure></a>

-   <a href="https://learn.sparkfun.com/tutorials/41">**Working with Wire**

	---
	
	<figure markdown>
	![Working with Wire](https://cdn.sparkfun.com/c/264-148/assets/0/5/0/0/f/5138de3cce395fbb1b000002.JPG)
	</figure></a>

-   <a href="https://learn.sparkfun.com/tutorials/36">**How to Power a Project**

	---
	
	<figure markdown>
	![IHow to Power a Project](https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/3/6/Bench_Power_Supply.jpg)
	</figure></a>

-   <a href="https://learn.sparkfun.com/tutorials/26">**What is a Circuit?**

	---
	
	<figure markdown>
	![What is a Circuit?](https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/2/6/Concept_Tutorial_Images-03.jpg)
	</figure></a>

-   <a href="https://learn.sparkfun.com/tutorials/115">**Alternating Current (AC) vs. Direct Current (DC)**

	---
	
	<figure markdown>
	![Alternating Current (AC) vs. Direct Current (DC)](https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/1/1/5/acDC.jpg)
	</figure></a>

-   <a href="https://learn.sparkfun.com/tutorials/75">**Polarity**

	---
	
	<figure markdown>
	![Polarity](https://cdn.sparkfun.com/c/264-148/assets/5/4/1/e/0/5193d2adce395f3d7a000001.jpg)
	</figure></a>

-   <a href="https://learn.sparkfun.com/tutorials/62">**Logic Levels**

	---
	
	<figure markdown>
	![Logic Levels](https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/6/2/Input_Output_Logic_Level_Tolerances_tutorial_tile.png)
	</figure></a>

-   <a href="https://learn.sparkfun.com/tutorials/1890">**Buck Regulator Hookup Guide**

	---

	<figure markdown>
	![Buck Regulator Hookup Guide](https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/1/8/9/0/Thumbnail.png)
	</figure></a>

-   <a href="https://learn.sparkfun.com/tutorials/664">**How to Solder: Through-Hole Soldering**

	---
	
	<figure markdown>
	![How to Solder: Through-Hole Soldering](https://cdn.sparkfun.com/c/264-148/assets/e/3/9/9/4/51d9fbe1ce395f7a2a000000.jpg)
	</figure></a>

-   <a href="https://learn.sparkfun.com/tutorials/664">**How to Work with Jumper Pads and PCB Traces**

	---
	
	<figure markdown>
	![How to Work with Jumper Pads and PCB Traces](https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/6/6/4/PCB_TraceCutLumenati.jpg)
	</figure></a>

</div>