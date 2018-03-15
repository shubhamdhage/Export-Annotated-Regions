# Export-Annotated-Regions
GUI based application to Extract annotated regions and create binary mask.

The export_0.1_all.deb file is the ubuntu application to extract annotated regions and create corresponding mask.
Install this application and run
You will be presented with the Window shwing multiple empty fields.

1. First choose the folder containing the original data(From which to extract the annotated region).
Use the file chooser button to select/locate the directory.
The selected folder can contain multiple sub-folders. 
It may contain sub-tree of folders (code will take care of this).
Same sub-tree will be created while storing the extracted regions.

2. Specify the image type (image format)

3.Specify the paddind (The extra portion around the bounding rectangle)

4. Locate the folder containing xml files

5. If xml files are located in the same folder where original images are store then check the button "Same as Source Data Folder"

6. Choose the directory where you want to store the annotated regions. (If you do not specify the store folder bydefault it wiil create a foldernamed "Exported Annotations" on Desktop and store the extracted regions there.)

7. Finnaly execute using Run button.

8. The progress bar displays the progress so far.
