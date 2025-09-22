#### Mouse Bites Minimal
A minimal, ready to use 2x4mm Mouse Bites footprint. No need of drawing or removing anything extra after placing the footprint on your PCB Editor design. 

**Panelization** allows multipele PCBs to be produced together reducing overall production turnaround time. One of the ways to panelize a PCB is to use a technique called Mouse Bites. It is to create aseries of small, perforated tabs along the edges of the board - allows easy seperation by snapping apart the PCB by hand or basic snipping tools. It has an automatic edgecut which is compatible with 2mm drillbit that most fabrication houses use. This footprint is tested with KiCad 9. 

![Alt text](./mouse-bites.png?raw=true "Mouse Bites on a PCB (rendering)")

#### How to use
1. Download this repro
2. Add the folder `mouse-bites.pretty` to your kiCad project folder
3. Open your project and select `PCB editor`
4. In the menu go to `Preferences` then `Manage Symbol libraries`
5. Select `Project Specific Libraries`
6. Click on the folder icon  and select the `mouse-bites.pretty` folder and then `Open`
7. In the `PCB editor` click the footprint icon  and in the search field type `mouse`
8. Select the mouse bite minimal from the list and add it to your design.
9. Place the footprint on your PCB edge (Repeat placing untill all sides are covered sufficiently)

