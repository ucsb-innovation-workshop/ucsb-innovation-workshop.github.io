# WAZER Desktop Waterjet Cutter ​Safe Operating Procedures

**Tool Type:** CNC Waterjet Cutting Machine
**Manufacturer:** Wazer
**Location:**  Elings Hall 2442

## Training Checklist
*  Safety Considerations
*  Materials: Allowed Materials, Prohibited Materials
*  Mounting Materials in the Bed: Polypropylene Plastic Corrugated Bed
*  Cutting
*  Troubleshooting
*  General Material Recipes For Aluminum
*  Thickness, cutting settings
*  Maintenance

## Overview
This training provides an introduction to using and operating the waterjet cutters including:

*  File Types: DXF, SVG
*  Software: Job Control, WAM Software
*  Safety: General hazard, Material composition
*  Waterjet Use
*  Maintenance: adding more abrasive, throwing away used abrasive, collecting used abrasive

## Safety Considerations
*  Always wear safety glasses when using the machine.
*  Always work with the machine cover closed.
*  NEVER leave the waterjet alone when running a job.
*  The machine door must be left open while you are away.
*  Ensure that the abrasive tanks are full.
*  Remove leftovers of used abrasive in the used abrasive bucket before running a new job.
*  Confirm that there are no leaks when running a job.

## Materials
Always check materials list BEFORE attempting to cut/engrave a material. If unsure contact IW Staff.

Allowed Materials:

*  Thin sheets of metal
*  Glass and ceramics (will produce larger kerfs)
*  Plastic (poor finish and will clog filters)
*  Rubber (poor finish and will clog filters)
*  Composites (will delaminate)

## Cutting with the Wazer Waterjet
Operating WAM to create a toolpath:

- Open WAM (Wazercam software).
- Import your DXF or SVG file into the software.
- Scale and position your parts:
    - Importing the file may result in a change in dimensions, so double check the measurements are accurate before proceeding.
    - The grid in the software matches the plastic cut bed in the Wazer. Move your part(s) so that they will fit within your material and correspond to where you wish to cut.

- Select Material
    - User Materials Tab: Scroll through the options and choose the material you are cutting and the corresponding thickness.
    - Wazer Materials Tab: If you are unable to find your allowed material in the "User Materials" tab, the material can also be chosen through the Wazer Materials tab, information on the type and thickness will need to be inputted manually.
    - If you do not see the material you are cutting, please contact a Wizard.

- Select the cutting path offset. This will allow you to control how the kerf will affect your cut.
    - Outside: The tool will cut entirely outside of the file's boundary lines. Best when cutting the perimeter of a part. 
    - Centerline: Tool cuts on top of the file's boundary lines. Best when cutting slots. 
    - Inside: The tool will cut entirely inside of the file's boundary lines. Best when cutting out internal holes or parts where the scrap material will be located on the inside of the cut. 

- Select your tabs and leads. This will improve accuracy and prevent vibration/pop-ups, which can jam the waterjet and ruin the cut. 
    - Usually 2-4 tabs is enough for most materials and thicknesses. For more complex cut geometries, the number of tabs should be increased.
    - Tab thickness should be proportional to material thickness, a good rule of thumb is for your tab thickness to be 30-50% of your material thickness. For very thin materials, we recommend a minimum tab thickness of 0.05“.
    - Tab locations may leave sharp edges along the cut. Avoid placing tabs in areas where dimensional accuracy is critical.
    - Disable leads unless your material is prone to delamination when cutting.

- Select the cut quality. This will determine time for each job and the amount of abrasive used.
    - Fine typically provides the best results, although the differences in overall cut quality between settings are generally minimal.

- Name your file and select "Generate Job File". Upload to the SD card located plugged into either the Waterjet or desktop computer. Eject SD card and plug into Waterjet.

Operating the Waterjet

- Power on waterjet
    - Three switches (hidden switch to flip too) ...... add More detail 
-   Select file using the arrow keys, follow prompted instructions and set up the tool. Ensure that a dry run is done before cutting and then close the hood and cut!

## Maintinence


## Additional Resources

[Wazer User Manual](https://support.wazer.com/s/WORKING-WAZER-User-Manual_REV-A_Online_long.pdf)

[Wazer Maintenance Manual](https://support.wazer.com/maintenance-)
