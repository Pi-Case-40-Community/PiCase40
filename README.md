# Pi Case 40  

Community modifications, accessories and designs for Cooler Master's Raspberry Pi Case - Pi Case 40 and its GPIO redirecting PCB  

# Contributing

While you are welcome to share your Pi Case 40 creations with us, in any shape or form and under any license, we strongly encourage you to adhere to the following:

 1. Release as [Open Source Hardware](https://www.oshwa.org/definition/). We recommend the [strongly-reciprocal variant of CERN Open Hardware License v2.](https://ohwr.org/project/cernohl/wikis/Documents/CERN-OHL-version-2)
 2. Use [Free Software](https://www.gnu.org/philosophy/free-sw.en.html) for the creation. We recommend [KiCAD](https://kicad.org/) for PCBs, and [FreeCAD](https://www.freecadweb.org/) for 3D/CAD.
 3. Create your PCB with a project-specific library that contains all the schematic symbols and footprints (and possibly 3D shapes) that your PCB uses
 4. Your README file should mention whether you design has been tested or not, and any settings and/or order parameters and manifacturer used for producing/assembly.
 5. Use the structure described in the next section

# Structure

Create a folder with your username as its name, under ```Case```, ```Accessories``` or ```PCB``` (depending on the type of your project). Inside it, put your ```README.md``` and ```LICENSE``` files, as well as a folder with the name of your project.

Your project folder should contain 3 things:

 1. Your source files. In the case of a CAD project those would be either FreeCAD project file, or a KiCAD project's files in the case of a PCB.
 2. In the case of a PCB - a folder called ```Library``` with folders inside it, named ```3D```, ```Footprints``` and ```Schematic Symbols``` respectively, for your PCB library's footprints and schematic symbols (and possibly 3D shapes).
 3. In cases of a tested project, a folder called ```Output``` for your manifacturing files. .STEP/.STP and .STL in the case of a CAD project, or your gerber and drill files in the case of a PCB.
