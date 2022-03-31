### [Tutorial 3 for Altium Beginners: PCB Layout - YouTube](https://www.youtube.com/watch?v=2I2TX3RLEGM)
-   [ ] project → project options → class generation → generate rooms uncheck all
-   [ ] design → update PCB document
-   [ ] adjust board size, change grid to mm
    -   [ ] grid manager set to 10mm
-   [ ] view → 1 board design view
-   [ ] design → redefine board shape
-   [ ] edit → set origin
-   [ ] design → layer stack manager
-   [ ] design → rules
    -   [ ] electrical clearance 0.3mm
    -   [ ] routing → width → width 0.5mm preferred
    -   [ ] routing via → routing via style 0.6mm, hole 0.3mm
-   [ ] route → interactive routing
-   [ ] tent via

### [Tutorial 2 for Altium Beginners: How to create footprints - YouTube](https://www.youtube.com/watch?v=wxYbIGV9_CY&t=552s)

-   [ ] tools → footprint wizard
-   [ ] mechanical 1 layer
-   [ ] place → 3D body
-   [ ] tool → 3D body placement
-   [ ] assembly drawing layer = mechanical 29
-   [ ] shift-S single layer mode
-   [ ] copy and paste special top layer into mechanical 29
-   [ ] place → string
-   [ ] .Designator , text height 0.7, text width 0.1
-   [ ] DIP
-   [ ] dual in line package for header
-   [ ] pad dimensions
-   [ ] edit → set reference → center
-   [ ] top layer → set line width = 0.2mm
-   [ ] .23 x 0.1 (size of header in inch, or 230mil x 100mil
-   [ ] J to jump to new position




### [Tutorial 1 for Altium Beginners: How to draw schematic and create schematic symbols - YouTube](https://www.youtube.com/watch?v=KpgTud1iQ-4)
-   [ ] system → supplier search
-   [ ] digikey → header 2.54mm
-   [ ] molex → in stock → EDA model → 2 positions → 1 row → board to cable wire → through hole
-   [ ] 0022292021 → WM2744-ND
-   [ ] check if can be bought one piece
-   [ ] place → pin
-   [ ] system preference → mouse wheel → uncheck ctrl to zoom
-   [ ] system preference → schematic → auto pan off
-   [ ] system preference → PCB→ auto pan off
-   [ ] system preference → grid→ grid color
-   [ ] view → fit all objects (v, f)
-   [ ] edit → move → send to back
-   [ ] Designator to J?
-   [ ] set comment
-   [ ] add parameter "category"



### Altium
[Tutorial 1 for Altium Beginners: How to draw schematic and create schematic symbols](https://www.youtube.com/watch?v=KpgTud1iQ-4)

-   [ ] system → mouse wheel → zoom main window
-   [ ] schematic → graphic editing → disable autopan
-   [ ] schematic → graphic editing → disable autopan
-   [ ] schematic → grid → grid color

[Tutorial 2 for Altium Beginners: How to create footprints](https://www.youtube.com/watch?v=wxYbIGV9_CY&list=RDCMUCJQkHVpk3A8bgDmPlJlOJOA&index=3)

-   [ ] tools → footprint wizard
-   [ ] change to mm and grid size
-   [ ] mechanical 1 layer for 3d models
-   [ ] tools → align face with board
-   [ ] assembly drawing layer
    -   [ ] add m29
    -   [ ] shift-s, single layer mode
    -   [ ] board insight display → uncheck hide other layers
    -   [ ] select all , ctrl-C and set reference point to edit → paste special
    -   [ ] designator 0.7mm text height, 0.1 stroke width
    -   [ ]

[Tutorial 3 for Altium Beginners: PCB Layout](https://www.youtube.com/watch?v=2I2TX3RLEGM&t=2s)

-   [ ] uncheck generate rooms and component classes
-   [ ] design → update PCB docs
-   [ ] change to mm and change grid step to 10mm
-   [ ] View → broad planning mode
-   [ ] design → redesign board shape
-   [ ] edit → origin
-   [ ] design → layer stack manager
-   [ ] design → rules
    -   [ ] minimal clearance 0.3mm
    -   [ ] min/max track width 0.3mm/1mm, 0.5mm preferred
    -   [ ] routing via style
-   [ ] route → interactive routing
    -   [ ] +/- for via
    -   [ ] tented via
    -   [ ] select a segment and tab to select all
    -   [ ] place → polygon pour
-   [ ] uncheck board insight information
-   [ ] board outline layer
    -   [ ] mechanical layer 2 ⇒ "board outline"
-   [ ] create layer set
    -   [ ] top and bottom sets
-   [ ] DRC
    -   [ ] tools → DRC
    -   [ ] panels → PCB rules and violation window
    -   [ ] silk to solder mask clearance

[Tutorial 4 for Altium Beginners: Placement, Variants, Assembly Drawings](https://www.youtube.com/watch?v=L36KicrU45Q)

-   [ ] Add a LED and resistor
    -   [ ] Design → Update PCB document


[Resistor Sizes and Packages | Resistor Standards and Codes | Resistor Guide](https://eepower.com/resistor-guide/resistor-standards-and-codes/resistor-sizes-and-packages/#)

[Connector Basics - learn.sparkfun.com](https://learn.sparkfun.com/tutorials/connector-basics/all)

-   [ ] shortcuts
    -   [ ] ctrl-M measurement mode
    -   [ ] shfit-c clear measurement
    -   [ ] shift-m insight lens