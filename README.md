# Export-Annotated-Regions
Ubuntu application to Extract annotated regions and create binary mask.

The export-annotated-region_0.1_all.deb file is the ubuntu application to extract annotated regions and create corresponding mask.
How to Install this application?
Before installing application directly make sure that,
1. you have python 2 or python 3 installed
2. If you are dealing with Whole-Slide-Images(WSI i.e. images with format- .ndpi, .svs, .tiff, .tif, .mrxs, .svslide) then you need to install openslide.
To install openslide reffer to the following link,
http://openslide.org/download/


Now you can start with installation.

1. Download .deb file
2. Run following command in terminal
        sudo dpkg -i /path/to/deb/file
        sudo apt-get install -f
3. You might get some errors such as import error or Gtk related errors. You can resolve by searching about them on google.
4. To start application run foolowing command in terminal
        export-annotated-region
5. If everything is fine it will start your application else you will be promted with error messages which will ask you to install certain python-packages/gtk-packages.



How to Use The Application:
You will be presented with the Window shwing multiple empty fields.

1. First choose the folder containing the original data(From which to extract the annotated region).
Use the file chooser button to select/locate the directory.
The selected folder can contain multiple sub-folders. 
It may contain sub-tree of folders (code will take care of this).
Same sub-tree will be created while storing the extracted regions.

2. Specify the image type (image format)

3. Specify the padding (The extra portion around the bounding rectangle)

4. Locate the folder containing xml files

5. If xml files are located in the same folder where original images are store then check the button "Same as Source Data Folder"

6. Choose the directory where you want to store the annotated regions. (If you do not specify the store folder bydefault it wiil create a foldernamed "Exported Annotations" on Desktop and store the extracted regions there.)

7. Finnaly execute using Run button.

8. The progress bar displays the progress so far.
