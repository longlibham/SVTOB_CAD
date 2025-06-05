# SVTOB_CAD
SVTOB CAD conversion repository for B'ham user
This is a step by step instruction about converting the CAD file in to GDML file for dd4hep simulation
Dependencies:
  [FreeCAD](https://www.freecad.org/)
  
1. prepare CAD file and convert it to `.FCStd` file in FreeCAD
2. run `python autogen_svtob_xml.py -f FCStd_file_L3 FCStd_file_L4 `
