#### Mousr Bites Minimal
A minimal, ready to use 2x4mm Mouse Bites footprint. No need of drawing or removing anything extra after placing the footprint on your PCB Editor design. 

**Panelization** allows multipele PCBs to be produced together reducing overall production turnaround time. One of the ways to panelize a PCB is to use a technique called Mouse Bites. It is by creating small, perforated tabs along the edges of the board - allows easy seperation by snapping apart the PCB by hand or basic snipping tools. This footprint is tested with KiCad 9. It has an automatic edgecut which is compatible with 2mm drillbit that most fabrication houses use. 

![Alt text](./mouse-bites.png?raw=true "Mouse Bites on a PCB (rendering)")

#### How to use
* Download this repro
* Add the folder `mouse-bites.pretty` to your kicad project folder
* Open your project en select `PCB editor`
* In the menu go to `Preferences` then `Manage Symbol libraries`
* Select `Project Specific Libraries`
* Click on the folder icon  and select the `mouse-bites.pretty` folder and then `Open`
* In the `PCB editor` click the footprint icon  and in the search field type `mouse`
* Select the mouse bite minimal from the list and add it to your design.
* Place the footprint on your PCB edge

