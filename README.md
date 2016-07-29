# CustomMMPKLibrary

A library that can be used automate the creation of MMPKs **when Map objects are supported in arcpy.managementCreateMobileMapPackage()**

To use this script you will need:
* ArcGIS Pro w/ArcPy
* The directories that make up this project:
  * CustomMMPKLibrary
  * CustomMMPKData

In order to use the script:
* Open 'Python Command Prompt'
* Change directories to where the Python script is located 
  * `cd "/Users/joel8641/Dropbox/Esri Material/CustomMMPKs/CustomMMPKLibrary/"`
* Change command line parameters and execute script
  * `python custom_mmpk_from_csv.py -aprx "../CustomMMPKData/CustomMMPKDirectory.aprx" -opLyrName "SD_Fire_Hydrants" -csvFile "custom_mmpk_list.csv"`