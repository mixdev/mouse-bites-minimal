### Mouse Bites Minimal
A minimal, ready to use 2x4mm Mouse Bites footprint. 

**Panelization** allows multipele PCBs to be produced together reducing overall turnaround time. One of the ways to panelize a PCB is to use a technique called Mouse Bites. It is to create aseries of small, perforated tabs along the edges of the board - allows easy seperation by snapping apart the PCB by hand or basic snipping tools. It has an automatic edgecut which is compatible with 2mm drillbit that most fabrication houses use. This footprint is tested with **KiCad 9**. 



![Alt text](./mouse-bites.png?raw=true "Mouse Bites on a PCB (rendering)")

### Why use mouse bites?
* **Cost-Effective**: Panelization allows for multiple boards to be processed together, improving manufacturing efficiency and cost. 
* **Easy Separation**: The strategically placed holes create weak points, making it easy to snap boards apart by hand or with basic tools. 
* **Handles Complex Shapes**: Mouse bites are a good alternative to V-scores when dealing with PCBs that have connectors sticking out or curved edges. 

### How to use
1. Add a folder `mouse-bites.pretty` to your KiCad project folder
2. Download this repro to it
4. Open your project in KiCad and select `PCB editor`
5. In the menu go to `Preferences` then `Manage Footprint libraries`
6. Select `Project Specific Libraries` tab on top
7. Click on the folder icon  and select the `mouse-bites.pretty` folder and then `Open` and click `OK`
8. In the `PCB editor`, press `A` to open up footprint list and in the search field type `mouse`
9. Select the `Mouse-Bite-2mm-4mm` footprint from the list and add it to your design.
10. Place the footprint on your PCB edge (Repeat placing untill all sides are covered sufficiently)

### Placement Gudelines
* **Clearance**: Ensure there is ample clearance (at least 2mm) around the mouse bites to prevent damage to components or traces during separation
* **Even Distribution**: Place mouse bites evenly along the edges to provide uniform support across the panel
* **Avoid Sensitive Areas**: Do not place mouse bites over vias, traces, mounting holes, or protruding components

