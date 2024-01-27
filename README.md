# <p align="center">Upgrading Classic Apples</p>

<p align="center">
<img src="./img/LOGO.png" alt="Apple Logo" width="128" height="128"/>
</p>

<br>

<h2>Table of Contents</h2>

+ [**- Macintosh Classic**](#--macintosh-classic)
+ [**- Macintosh Plus**](#--macintosh-plus)
+ [**- Zero Track Finder for SONY MP-F75W**](#--zero-track-finder-for-sony-mp-f75w)
+ [**- Apple II / II+**](#--apple-ii--ii)
  + [**+ DATANEKTICS Keyboard: key switch shackle**](#-datanektics-keyboard-key-switch-shackle)
  + [**+ Rear Insert for Apple II**](#-rear-insert-for-apple-ii)
+ [**- Apple Keyboard (M7803)**](#--apple-keyboard-m7803)
+ [**- Apple Silentype (A2M0032)**](#--apple-silentype-a2m0032)

<br>

<table cellpadding="0" cellspacing="0" width="100%">
<tr><td>

![ATTENTION](https://friconix.com/png/fi-hnsdxt-plug-alt.png)

</td><td>

**<u>DISCHARGE</u> the CRT before doing any service inside of your Mac.**

</td></tr>

<tr><td>

![](https://friconix.com/png/fi-cnsuxt-question-mark.png)

</td><td>

**Please refer to [issues](https://github.com/way5/mac-classic-pram-battery-bay/issues) :beetle: if you have a suggestion or found an error.**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

</td></tr>
</table>

## **- [Macintosh Classic](./models/macintosh%20classic/)**

<table cellpadding="0" cellspacing="0" width="100%">
<tr><td width="160px">
<img alt="Macintosh Classic" src="./img/M420.jpg" width="150" />
</td><td>
The PRAM battery compartment sits between the logic board and the case (see photos).<br>Batteries will serve longer if you choose to use it from the same manufaturer and maintain them well charged. In my experience 3.2-3.9V total is enougn for proper timekeeping.
</td></tr></table>

<br>

**BOM:**

1. PRAM battery compartment
   - Wire <= AWG22 ~ 0.1 m
   - Single flat contact plates for AA, AAA batteries - 6 pcs.

---

**PLEASE NOTE**: \
Before to install the battery compartment with the batteries inside it should be electrically isolated from the logic board, otherwise the permanent damage of electrical circuits might occur. For that purpose I'm using thin (~0.5mm) transparent film, wrapping it over the battery compartment and securing it on the connector (see photos).

---

**<h3>+ Photos</h3>**

| ![top view](img/P001.jpg) | ![bottom view](img/P002.jpg) | ![logic board](img/P003.jpg) | ![installation](img/P004.jpg) |
|:---:|:---:|:---:|:---:|

</br>

## **- [Macintosh Plus](./models/macintosh%20plus/)**

<table cellpadding="0" cellspacing="0" width="100%">
<tr><td width="160px">
<img alt="Macintosh Plus" src="img/M01A.jpg" width="150"/>
</td><td>

PRAM Battery. <br>The battery case is pretty much as for previous model with the only difference, it attaches directly to standard battery holder of Mac. Despite it designed to use 4.5V battery, in my experience 3.5 ± 0.4V is enough.  <br>Cooling Fan (Noninvasive method). <br>Mac Plus was designed to be cooled passively via natural convective flow through the ventilation grates all over its housing. Usually this is not enough, so it gets noticeably hot, so the cooling fan may be installed in order to make Mac's life longer.

</td></tr></table>

<br>

**BOM:**

1. PRAM battery compartment
   - Wire <= AWG22 ~ 0.1m
   - Single flat contact plates for AA, AAA batteries - 6 pcs.
   - Copper foil ~ 30mm2

**<h3>+ Photos</h3>**

| ![PIC1](img/P101.jpeg) | ![PIC2](img/P102.jpeg) | ![PIC3](img/P103.jpeg) | ![PIC4](img/P104.jpeg) | ![PIC5](img/P105.jpeg) | ![PIC6](img/P106.jpeg) |
|:---:|:---:|:---:|:---:|:---:|:---:|

<br>

2. Cooling fan
   - Bolts M3 - 4 pcs.
   - Thru Threaded Inserts M3 - 4 pcs.
   - Washer Head Screws (for plastic) - 2 pcs.
   - Wire <= AWG22 - 0.5m
   - Diode rectifier (ex. 1N4007) - 1 pcs.
   - Double sided tape.
<br>Optional:
   - Copper foil ~ 30mm2
   - Resistor (~50Ω) - 1 pcs.

<br>

---

**PLEASE NOTE:**: \
I'd not recommend you to use the fancy connector that you can see on the photos below, unless you know what you are doing. It requires that its both parts to be perfectly aligned, so when you close the housing it makes secure contact at all times.<br>
A much secure solution is to use any of the following connectors:

<p align="center'><img alt="connectors" src="./img/C040.jpg" /></p>

---

**<h3>+ Photos</h3>**

| ![PIC1](img/P201.jpeg) | ![PIC2](img/P202.jpeg) | ![PIC3](img/P203.jpeg) | ![PIC4](img/P204.jpeg) | ![PIC5](img/P205.jpeg) | ![PIC6](img/P206.jpeg) | ![PIC7](img/P207.jpeg) |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|

<br>

## **- [Zero Track Finder for SONY MP-F75W](./models/sony%20MP-F75W/)**

<table cellpadding="0" cellspacing="0" width="100%">
<tr><td width="160px">
<img alt="Zero Track finder for SONY-F75W" src="img/P300.jpg" width="150"/>
</td><td>

**<p>DO NOT USE if your drive operates properly</p>**
A simple tool which may help you to adjust zero track sensor on SONY-F75W-XX floppy drives. Place it over the sensor and secure the assembly. Loosen the sensor screw and slowly adjust the knob, insert the disk. If zero track has been found the floppy will start reading properly, if not repeat adjustment and insert the disk again. Once you finished, secure the sensor on its place and take off Zero Finder assembly.

</td></tr></table>

**<h3>+ Photos</h3>**

| ![PIC1](img/P304.jpg) | ![PIC2](img/P301.jpg) | ![PIC3](img/P302.jpg) | ![PIC4](img/P303.jpg) |
|:---:|:---:|:---:|:---:|
<br>

## **- [Apple II / II+](./models/apple%20II/)**

### **+ [DATANEKTICS Keyboard: key switch shackle](./models/apple%20II/datanectics%20keyboard%20switch%20shackle_v7.f3d)**

<table cellpadding="0" cellspacing="0" width="100%">
<tr><td width="160px">

<img alt="Apple II Datanekticts Keyboard repair" src="img/P405.jpg" width="150"/>

</td><td>

There are a multiple ways to repair Apple II's Datanektiks keyboard. My decision was to crack open all malfunctioning key switches to give them a proper maintainment. When the key is back to work, clean and lubricated, you may glue the both halves of the key mechanism together as it was before or to leave the opportunity to painlessly open if it will fail again. The key swith shackle securely holds the both parts of the mechanism together and may be easily removed by whatever reason you need to open the switch in future. 
<p><u>Hint:</u> Be very careful when opening the key switch with the cutter knife, do not apply too much force. Open it from the opposite side to the contact pins.</p>

</td></tr></table>

**<h3>+ Photos</h3>**

| ![PIC1](img/P401.jpg) | ![PIC2](img/P402.jpg) | ![PIC3](img/P403.jpg) | ![PIC4](img/P404.jpg) |
|:---:|:---:|:---:|:---:|

### **+ [Rear Insert for Apple II](./models/apple%20II/rear_insert_v16.f3d)**
<table cellpadding="0" cellspacing="0" width="100%">
<tr><td width="160px">
<img alt="Apple II Plus" src="img/P410.jpg" width="150"/>
</td><td>

Just a simple insert, originally designed for Apple II+ in order to allow some cable management on the rear side of the housing.

</td></tr></table>

<br>

## **- [Apple Keyboard (M7803)](./models/imac%20g4/m7809_keyboard_key_shaft.stl)**

<table cellpadding="0" cellspacing="0" width="100%">
<tr><td width="160px">
<img alt="iMac G4 keyboard M7803" src="img/P505.jpg" width="150"/>
</td><td>

The Apple keyboards are rarely reliable particularly an old ones. Let's give a chance to one of the most fragile devices by modifying the switching mechanism, adding custom key shaft instead of an unreliable side clips.

</td></tr></table>

**<h3>+ Photos</h3>**

| ![PIC1](img/P501.jpg) | ![PIC2](img/P502.jpg) | ![PIC3](img/P503.jpg) | ![PIC4](img/P504.jpg) |
|:---:|:---:|:---:|:---:|

## **- [Apple Silentype (A2M0032)](./models/apple%20silentype/)**

<table cellpadding="0" cellspacing="0" width="100%">
<tr><td width="160px">
<img alt="Apple Silentype (A2M0032)" src="img/P700.jpg" width="150"/>
</td><td>

The Apple Silentype had two plastic inserts on both sides of the paper roll. Sometimes one or both of these are lost. To fully assemble the insert you'd also need a spiral spring of corresponding diameters and the starlock stopper ring (outer d = ~7mm).

</td></tr>
<tr><td width="160px">
<img alt="Apple Silentype (A2M0032)" src="img/P600.jpg" width="150"/>
</td><td>

The main shaft of paper feeding mechanism is connected to the stepper motor through the plastic bushing which becomes brittle over time. You probably already faced the need to replace it or in the near future would do. This [printable model](./models/apple%20silentype/bushing.stl) may resolve the issue.

</td></tr></table>

**<h3>+ Photos</h3>**

| ![PIC1](img/P701.jpg) | ![PIC2](img/P702.jpg) | ![PIC3](img/P703.jpg) |
|:---:|:---:|:---:|


<br>