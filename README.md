# Cross Section Planner - FreeCAD Macro

## Overview
The Cross Section Planner is a FreeCAD macro that helps create evenly spaced cross-sections of a 3D model along a chosen axis (X, Y, or Z). It's particularly useful for creating 2D profiles from 3D models for manufacturing, analysis, or documentation purposes.

## Features
- Create multiple parallel cross-sections along any axis
- Adjustable number of sections (2-20)
- Configurable offset from model edges
- Interactive preview of section planes
- Automatic creation of new document with sections
- Visual feedback with colored preview planes

## Installation
1. Copy the `MyCrossSection.FCMacro` file to your FreeCAD macros directory
2. In FreeCAD, go to `Macro > Macros...` and select `MyCrossSection.FCMacro`
3. Click "Execute"

## Usage
1. Open a FreeCAD document containing a 3D model
2. Select the object you want to section
3. Run the macro
4. In the dialog:
   - Choose the axis for sectioning (X, Y, or Z)
   - Set the number of sections
   - Adjust the offset from edges
   - Click "Preview Sections" to see the section planes
   - Click "Create Sections" to generate the cross-sections in a new document

## Notes
- The macro creates a new document for the cross-sections
- Preview planes are shown in green
- Sections are created as individual Part features
- The offset prevents sections from being too close to the model edges

## Requirements
- FreeCAD 0.19 or later
- A 3D model in the active document

## License
This macro is provided as-is under the MIT License. See the source code for details.

## Author
[Your Name Here]

## Version
1.0 - Initial release
