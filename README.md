# Power Distribution Unit for Aristotle University Racing Team Electric (ARISTURTLE)

<p align= "center"><img src="https://github.com/tsoukias/Power-Distribution-Unit-ARISTURTLE-/blob/master/Splitter-Box_renders/irida.jpg"/>`</p>

In this repository anyone can found all the CAD files for the power distribution unit / splitter box used by ARISTURTLE in the electric racing car of 2017-2018, called Irida. This project was made in collaboration with Iakovos Koutris. 

<p align= "center"><img src="https://github.com/tsoukias/Power-Distribution-Unit-ARISTURTLE-/blob/master/Splitter-Box_renders/Assmbly-without-EM.jpg" width="500" align="center"/>`</p>

### Brief Explanation

The power distribution unit is a *3D-printed box*, containing all the necessary connections for splitting the *DC High Voltage* from the battery of the racecar in order to supply the two inverters of the car, by splitting the positive and negative pole to two supply lines. It also contains the **discharge circuit** for the DC link capacitors of the inverters the **BSPD** (Brake System Plausibility Device), the **energy meter** for the Formula Student competitions and the **HVD** (High Voltage Disconnect). Below you can see the **powertrain** of the racecar. The top container is the *power distribution unit*.

![alt text](https://github.com/tsoukias/Power-Distribution-Unit-ARISTURTLE-/blob/master/Splitter-Box_renders/tractive_system_45_view.jpg)

### Structural 

The power distribution unit is *3D-printed*, thing that gives facility for many configurations. The construction is composed of 6 pieces, due to the 3D printer restrictions, that were glued together. The box is made of ABS, due to its low weight, its high temperature resistance and because its electrically non conductive. An exploded view of the splitter box as well as the HVD lid can be seen below. The top lid of the box is a 2mm transparent polycarbonate piece for fast inspection of the system.  

|                    Splitter Box Exploded                     |                           HVD Lid                            |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| ![](https://github.com/tsoukias/Power-Distribution-Unit-ARISTURTLE-/blob/master/Splitter-Box_renders/splitter-exploded.jpg) | ![](https://github.com/tsoukias/Power-Distribution-Unit-ARISTURTLE-/blob/master/Splitter-Box_renders/HVD-LID.jpg) |

For waterproofing the construction a special recess was placed around the perimeter of the box for installing an o-ring. The box has two compartments that are separated by a polycarbonate piece for ensuring electrical insulation between the two. One other important aspect of the construction is the use of brass threaded inserts for screwing all the components together. These were fitted to ABS via a soldering iron. Lastly, for ensuring proper installation for the High Voltage path threaded insulators were used. 

|                    Brass Threaded Insert                     |                     Threaded Insulators                      |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| ![](https://github.com/tsoukias/Power-Distribution-Unit-ARISTURTLE-/blob/master/Splitter-Box_renders/brass-threaded-inserts.jpg) | ![](https://github.com/tsoukias/Power-Distribution-Unit-ARISTURTLE-/blob/master/Splitter-Box_renders/busbar-insulators.jpg) |

### High Voltage Compartment

The High Voltage compartment features the two nodes where the positive and negative terminal of the battery split, the HVD, the Energy Meters & also topologies for current and voltage measurements. The nodes can be seen below for each terminal:

|                          HV+ busbar                          |                          HV- busbar                          |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| ![](https://github.com/tsoukias/Power-Distribution-Unit-ARISTURTLE-/blob/master/Splitter-Box_renders/HV%2BBusbar.jpg) | ![](https://github.com/tsoukias/Power-Distribution-Unit-ARISTURTLE-/blob/master/Splitter-Box_renders/Hv-Busbar.jpg) |

The HVD is placed in the front part of the box, right in the center. It is contained inside a lid, that is mounted on the top of the box, and is mounted in the outside skin of the chassis with two M8 bolts. 

Two cables from the accumulator container are inserting the splitter box from the left side through PG13.5 cable glands as shown in the picture.

<p align= "center"><img src="https://github.com/tsoukias/Power-Distribution-Unit-ARISTURTLE-/blob/master/Splitter-Box_renders/in-out-lines.jpg" width="500" align="center"/>`</p>

The positive line is connected to the one side of the HVD with a 35M8 ring terminal. The other side of the HVD is where the split takes place, as an S shaped HV+ busbar and a 25M8 ring terminal is connected there. The busbar is then connected to a 25M6 ring terminal and the cable exits the splitter box from the left side through a cable gland, while the other cable exits from the right side. 

The negative line passes through a LEM that is mounted in the side of the box and is connected in the middle of the HV- busbar with a 35M8 ring terminal. Then from the end of each side, a 25M6 ring terminal is connected and the cables are exiting the splitter box through PG 13.5 cable glands.

|                         Cable gland                          |                        Ring Terminal                         |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| ![](https://github.com/tsoukias/Power-Distribution-Unit-ARISTURTLE-/blob/master/Splitter-Box_renders/cable-gland.jpg) | ![](https://github.com/tsoukias/Power-Distribution-Unit-ARISTURTLE-/blob/master/Splitter-Box_renders/ring-terminal.jpg) |

The HV+ and HV- busbars are also separated by a 2mm polycarbonate piece and are supported by cylindrical busbar insulators that have screw thread from both sides. In front of the HV- busbar there is enough space to accommodate the different energy meters of the competitions as well as configurations with brass threaded inserts to mount them in the floor.

### Low Voltage Compartment

<p align= "center"><img src="https://github.com/tsoukias/Power-Distribution-Unit-ARISTURTLE-/blob/master/Splitter-Box_renders/LV-Compartment.jpg" />`</p>

The Low Voltage Compartment consists of the discharge and BSPD PCB, a fan and a connector. The discharge PCB is susceptible to heat, thus a heat sink along with a fan is used. Airflow is achieved using grilles at the position of the fan, at the polycarbonate wall between the HV and LV compartment and also at the very front of the box (at the HV+ side) of the power distribution unit. M3 threaded inserts are used to mount the PCBs.  All the signals for and from the PCBs communicate through a 21-pin connector. Above the connector there is a PG 9 cable gland for the cables of the measuring points.

|                             BSPD                             |                          Discharge                           |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| ![](https://github.com/tsoukias/Power-Distribution-Unit-ARISTURTLE-/blob/master/Splitter-Box_renders/BSPD.jpg) | ![](https://github.com/tsoukias/Power-Distribution-Unit-ARISTURTLE-/blob/master/Splitter-Box_renders/Dishcharge.jpg) |

### Mounting 

The splitter box is located in the middle of the rear part of the chassis, above the accumulator container and just behind the driver’s seat. It is accessible from the top part of the chassis for the easy insertion/removal of the energy meters during the competitions and is supported by an aluminum mounting that is screwed on the chassis.

|                           Mounting                           |                           Top View                           |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| ![](https://github.com/tsoukias/Power-Distribution-Unit-ARISTURTLE-/blob/master/Splitter-Box_renders/mounting.jpg) | ![](https://github.com/tsoukias/Power-Distribution-Unit-ARISTURTLE-/blob/master/Splitter-Box_renders/car_top_view_splitter.png) |

The position of the splitter box is shown in the picture below.

![](https://github.com/tsoukias/Power-Distribution-Unit-ARISTURTLE-/blob/master/Splitter-Box_renders/position-in-the-car.jpg)

### Energy Meters

The team participated to FS ATA Italy, FS East and FS Czech Republic and each one of them had a different energy meter for the measurement of the consumed energy. Below you can see the three different topologies. 

##### FS ATA 

<p align= "center"><img src="https://github.com/tsoukias/Power-Distribution-Unit-ARISTURTLE-/blob/master/Splitter-Box_renders/FS_ATA_ASSEM.jpg"/>`</p>

##### FS EAST

<p align= "center"><img src="https://github.com/tsoukias/Power-Distribution-Unit-ARISTURTLE-/blob/master/Splitter-Box_renders/FS-EAST_ASSEM.jpg"/>`</p>

##### FS CZECH REPUBLIC

<p align= "center"><img src="https://github.com/tsoukias/Power-Distribution-Unit-ARISTURTLE-/blob/master/Splitter-Box_renders/FS_CZECH_ASSEM.jpg"/>`</p>

### Notice 

For any further details about the design feel free to contact me to: stefanostsoukias@gmail.com