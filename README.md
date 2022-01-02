# Macintosh Upgrades
|![WARNING](https://friconix.com/png/fi-ensuxs-warning-solid.png) |The project requires minimal operating skills with electronics, you must have a simple multimeter and soldering iron as well as to be able to use them properly. Everything you do hereinafter is at your own risk. :) |
|:---:|:---|
|![ATTENTION](https://friconix.com/png/fi-owpdxs-plug-alt.png)| **<u>DO NOT</u> forget to discharge the CRT before to touch any internal parts of your Mac.** |
|![DISCLAMER](https://friconix.com/png/fi-cnsuxs-question-mark.png) | **Please refer to [issues](https://github.com/way5/mac-classic-pram-battery-bay/issues) :beetle: if you have any suggestion or found an error.**|

<br/>

## **+ Description**

<br/>

### **- Mac Classic**

| <p style="width:150px;text-align:center;"><img alt="Mac Classic" src="./.IMG/M420.jpg" /></p>|PRAM battery.<br/>All the dimensions taken from a particular Macintosh model - M0420. The battery compartment locates in a small space between logic board and the case (see photos).<br/>Batteries will serve longer if you choose to use it from the same manufaturer and maintain them well charged. In my experience 3.2-3.9V total is enougn for proper functioning.|
|:---:|:---|

<br/>

**BOM:**

1. PRAM battery compartment
   - Wire <= AWG22 ~ 0.1 m
   - Single flat contact plates for AA, AAA batteries - 6 pcs.

<br/>

---

**PLEASE NOTE**: \
Before to install the battery compartment with the batteries inside it should be electrically isolated from the logic board, otherwise the permanent damage of electrical circuits might occur. For that purpose I'm using thin (~0.5mm) transparent film, wrapping it over the battery compartment and securing it on the connector (see photos).

---

### **+ Photos**

| ![top view](.IMG/P001.jpg) | ![bottom view](.IMG/P002.jpg) | ![logic board](.IMG/P003.jpg) | ![installation](.IMG/P004.jpg) |
|:---:|:---:|:---:|:---:|

<br/>

### **- Mac Plus**

| <p style="width:150px;text-align:center;"><img alt="Mac Plus" src=".IMG/M01A.jpg"/></p> | PRAM Battery. <br/>The battery case is pretty match as for previous model with the only difference, it attaches directly to standard battery holder of Mac. To install it you need to gently bend down all 3 capacitors that located right behind your Mac's battery. Despite it designed to use 4.5V battery, in my experience 3.5 ± 0.4V is enough.  <br/>Cooling Fan. <br/>Mac Plus was designed to be cooled passively via natural convective flow through the ventilation grates all over its housing. Sometimer it is not enough, so it gets noticeably hot. In order to make its life longer I've installed cooling fan at one of the vent. grates from the inside of the housing. |
|:---:|:---|

<br/>

**BOM:**

1. PRAM battery compartment
   - Wire <= AWG22 ~ 0.1m
   - Single flat contact plates for AA, AAA batteries - 6 pcs.
   - Copper foil ~ 30mm2

<br/>

### **+ Photos**

| ![PIC1](.IMG/P101.jpeg) | ![PIC2](.IMG/P102.jpeg) | ![PIC3](.IMG/P103.jpeg) | ![PIC4](.IMG/P104.jpeg) | ![PIC5](.IMG/P105.jpeg) | ![PIC6](.IMG/P106.jpeg) |
|:---:|:---:|:---:|:---:|:---:|:---:|


<br/>

2. Cooling fan
   - Bolts M3 - 4 pcs.
   - Thru Threaded Inserts M3 - 4 pcs.
   - Washer Head Screws (for plastic) - 2 pcs.
   - Wire <= AWG22 - 0.5m
   - Diode rectifier (ex. 1N4007) - 1 pcs.
   - Resistor (~50Ω) - 1 pcs.
   - Double sided tape.
<br/>Optional:
   - Copper foil ~ 30mm2

<br/>

**Schematics:**

The resistor slows down the fan and makes it less noisy, could be any in range 1Ω-100Ω. The diode could be any common rectifier diode (~1.2W max).

<p style="text-align:center;"><img alt="Cooling fan connection" src=".IMG/C002.jpg"/></p>

<br/>

---

**PLEASE NOTE:**: \
I'd not recommend you to use the fancy connector that you can see on the photos below, unless you know what you are doing. It requires that its both parts to be perfectly aligned, so when you close the housing it makes secure contact at all times.<br/>
A much secure solution is to use any of the following connectors:

<p style="text-align:center; height: 100px;"><img alt="connectors" src="./.IMG/C040.jpg" /></p>
---

### **+ Photos**

| ![PIC1](.IMG/P201.jpeg) | ![PIC2](.IMG/P202.jpeg) | ![PIC3](.IMG/P203.jpeg) | ![PIC4](.IMG/P204.jpeg) | ![PIC5](.IMG/P205.jpeg) | ![PIC6](.IMG/P206.jpeg) | ![PIC7](.IMG/P207.jpeg) |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|

<br/>

I'd recommend to use PLA plastic for printing. The temperatures are 60•C for heated bed and 200°C. In my case plastic almost isn't shrinked after cooldown. No further processing required.

~Enjoy