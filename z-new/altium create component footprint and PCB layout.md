[[altium]]

- find it on snapEDA and import the extracted source
- footprint wizard
- 

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


- add new to project -> PCB
- design -> import from schematic
- adjust board size, change grid to mm
-   [ ] design → rules
    -   [ ] electrical clearance 0.3mm
    -   [ ] routing → width → width 0.5mm preferred
    -   [ ] routing via → routing via style 0.6mm, hole 0.3mm


- silk to soldermask
	- silkscreen to soldermask clearance
	- ctrl-m for measure
	- shift-c for clear measurements