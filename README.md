# Pi Case 40  

Community modifications, accessories and designs for Cooler Master's Raspberry Pi Case - Pi Case 40 and its GPIO redirecting PCB  

## Repo Structure  

- Cases/  
    - \<author github username\>/  
        - README.md  
        - LICENSE  
        - Top/  
            - Source Files/  
            - Output Files/  
        - Bottom/  
            - Source Files/  
            - Output Files/  
        - Outer/  
            - Source Files/  
            - Output Files/  
- PCBs/  
    - \<author github username\>/  
        - README.md  
        - LICENSE 
        - Source Files/  
        - Output Files/  
- Accessories/  
    - \<author github username\>/  
        - README.md  
        - LICENSE 
        - Source Files/  
        - Output Files/  

## Contributing  

Please use the structure shown above. I.e. Depending on the type of resource, make a folder named after your GitHub username, in the respective directory. Inside it, place a README, a LICENSE and your Source and Output files in the respective folders.  

If it replaces the top, bottom or outer part of the case, it goes in **Cases**. If it replaces the GPIO redirection PCB, it goes in **PCBs**. If it is an addition to the case, it goes in **Accessories**. Create folders only for the parts your design includes. I.e. If your design doesn't replace the bottom of the case, you should only create the Top and Outer folders. If your design only replaces the GPIO PCB, only create a folder with your username, under PCBs, etc...  

### Cases  

- **README**: Your designs must be finalized and tested, and your README must include instructions for reproducing the part from the design. I.e. Mention the machine or manifacturer you have used and cut/print settings or order parameters. E.g. `3D printed at home with Original Prusa i3 MK3S+ in ABS with a layer thickness of 0.3mm, etc...` or `Ordered from XXX. Cut from 1inch aluminum, with a kerf setting of Y, etc...`  
- **LICENSE**: The recommended LICENSE is [Creative Commons CC BY-SA International 4.0](https://creativecommons.org/licenses/by-sa/4.0/)  
- **Source Files**: Put your source files (I.e. Your CAD software's project file/s in the folder). The use of [Free Software](https://en.wikipedia.org/wiki/Free_software) (such as [FreeCAD](https://www.freecadweb.org/) for example) for the creation of your case is encouraged.
- **Output Files**: Put both a .STEP and .STL files in your design's respective Output Files folder/s. If your top or outer or bottom of the case has multiple parts, put separate .STEP and .STL files for each of those parts.  
