# Openlane-Workshop

Contents

* Intro to Workshop
* Installing Openlane
* RTL to GDSII Flow
* Openlane Flow
* Inception of Open-Source EDA, OpenLANE and Sky130 PDK
* Floorplanning and Standard cells
* Design library cells using magic layout and ngspice simulation
* Contact
* Acknowledgements


### Intro to Workshop
---
The aim of this workshop is to understand RTL to GDSII flow using Openlane.

Openlane is an automated RTL to GDSII flow and it is based on several components which include Magic, OpenROAD, YOSYS etc. The main goal of Openlane is to produce GDSII layout  without any human involvement. Openlane is tuned for Skywater 130nm open source PDK.


### Installing Openlane
---
To intall Openlane:

#### Prerequisites
* Ubuntu OS
* 25 GB Disk Space

For installation refer to:
*  https://github.com/nickson-jose/openlane_build_script
* [Complete Guide to Install Openlane and Sky130nm PDK](https://www.udemy.com/course/vsd-a-complete-guide-to-install-openlane-and-sky130nm-pdk/)
* [Complete Guide to Install Open-Source EDA Tools](https://www.udemy.com/course/vsd-a-complete-guide-to-install-open-source-eda-tools/)


### RTL to GDSII Flow
---
ASIC design flow is an iterative process and the design flow changes depending upon our requirements for example, IP requirements, DFT insertion etc. This flow can be classified into 11 steps as shown below.

![RTL to GDSII Flow](https://github.com/AnDu00/Openlane-Workshop/blob/main/Images/RTL%20to%20GDSII%20flow.PNG)

* Chip Specification : Chip specifications are basically the desired requirements of the chip.
* Design Entry/ Functional Verification : In this stage the RTL and Behavioral modelling are performed using Hardware Description Languages(HDLs), mainly using verilog.
* RTL Synthesis : 


### Contact
---
Anirban Dutta - anirbandutta014@gmail.com


### Acknowledgements
* [Nickson Jose - VSD VLSI Engineer](https://github.com/nickson-jose)
* [Kunal Ghosh - Co-founder (VSD Corp. Pvt. Ltd)](https://github.com/kunalg123)
