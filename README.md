# illustrator-scripts
### Collection of scripts for adobe illustrator, created or modified by me.
### **How install:**
1. Download archive and unzip. All scripts are in the folder jsx
2. Place <script_name>.jsx in the Illustrator Scripts folder:
OS X: /Applications/Adobe Illustrator [vers.]/Presets.localized/en_GB/Scripts
Windows (32 bit): C:\Program Files (x86)\Adobe\Adobe Illustrator [vers.]\Presets\en_GB [or your localization]\Scripts\
Windows (64 bit): C:\Program Files\Adobe\Adobe Illustrator [vers.] (64 Bit)\Presets\en_GB [or your localization]\Scripts\
3. Restart Illustrator


## **ArtboardResizeWithObjects**
Script to resize on value an document artboards with all the objects on it.
### Usage:
1. Open your file
2. Run script File → Scripts → artboardResizeWithObjects.jsx
3. Select the size of the artboard or a percentage of the size, also configure other items
3. Press button "OK" or press enter

![ArtboardResizeWithObjects](/images/artboardResizeWithObjects.gif)


## **ArtboardsRotateWithObjects**
Script to rotate 90 degrees an document artboards with all the objects on it.
Author: Alexander Ladygin. UI: [Sergey Osokin](https://github.com/creold/).
### Usage:
1. Open your file
2. Run script File → Scripts → artboardsRotateWithObjects.jsx
3. Press button "OK" or press enter

![ArtboardsRotateWithObjects](/images/artboardsRotateWithObjects.gif)


## **Harmonizer**
Sort a lot of objects in Adobe Illustrator is hard. With Harmonizer you can just achieve results with a few clicks.
### Usage:
1. Select objects
2. Run script File → Scripts → harmonizer.jsx
3. Set the desired settings
4. Press button "OK" or press enter

![Harmonizer](/images/harmonizer.gif)


## **InlineSVGToAI**
The script inserts the SVG code as an object from the clipboard into the Adobe Illustrator CC 2014+. Adobe Illustrator CC 2018 v.22.1 (march, 2018) can insert SVG graphics without a script.
Author: Alexander Ladygin. Code refactoring: [Sergey Osokin](https://github.com/creold/).

![InlineSVGToAI](/images/inlineSVGToAI.gif)


## **Cropulka**
The script cuts all that goes beyond the artboard. This script is ideal for microstock and printing, well, or just you need to trim the elements on the artboard.
### Usage:
1. Run script File → Scripts → cropulka.jsx
2. Select the desired settings
    - The script also cuts the images and the mesh, although the mesh will be rasterized and the picture will lose its connection. Also all raster effects will be separate images.
3. Press button "OK" or press enter

![Cropulka](/images/cropulka.gif)


## **Fillinger**
A Jongware Script - modified by Alexander Ladygin. The script fills the object with other objects in a random order or with one object. The ability to select the rotation of the object and much more.
### Usage:
1. Select objects
2. Run script File → Scripts → fillinger.jsx
3. Select the desired settings
    - The item to be filled must be either PathItem or CompoundPathItem, the items to be filled can be either in the group or outside the group.
4. Press button "OK" or press enter

![Fillinger](/images/fillinger.gif)


## **Randomus**
The script can:
- Random fill color
- Random stroke color
- Random scale
- Random rotate
- Random opacity
- Random position X, Y
### Usage:
1. Select objects
2. Run script File → Scripts → randomus.jsx
3. Press buttons - result in real time
4. Press "OK" or press enter - confirm changes, or press "Cancel" or press escape - cancel changes

![Randomus](/images/randomus.gif)


## **ReplaceItems**
Script for replacing objects with objects, the top object, an object from the clipboard. It can rotate elements in random order, copy width and height, and much more.
### Usage:
1. Select objects
2. Select the desired settings
    - You can copy an object to the clipboard and use it as an object to insert.
3. Run script File → Scripts → replaceItems.jsx
4. Press "OK" or press enter

![ReplaceItems](/images/replaceItems.gif)


## **PuzzleClipper**
The script makes copies of the last (lowest) object and puts them into a mask based on other (upper) objects. Creates a puzzle.
## Usage:
1. Select objects
    - The last (lowest in \[Layers\]) object will be taken as the main element for the puzzle
2. Select the desired settings
    - You can copy an object to the clipboard and use it as an object to insert.
3. Run script File → Scripts → puzzleClipper.jsx
4. Press "OK" or press enter

![PuzzleClipper](/images/puzzleClipper.gif)


## **ArtboardItemsMoveToNewLayer**
The script places all objects on the artboard in a new layer.
### Usage:
1. Run script File → Scripts → artboardItemsMoveToNewLayer.jsx
2. Select the desired artboards
    - If custom is selected, you can specify the numbers of the artboard as pages when printing, for example: 1, 2, 5-8
3. Press button "OK" or press enter

![ArtboardItemsMoveToNewLayer](/images/artboardItemsMoveToNewLayer.gif)


## **CreateArtboardsFromTheSelection**
The script creates artboards on selected items
### Usage:
1. Select objects
2. Run script File → Scripts → createArtboardsFromTheSelection.jsx
3. Set the desired settings
4. Press button "OK" or press enter

![CreateArtboardsFromTheSelection](/images/createArtboardsFromTheSelection.gif)


## **ForceCloseOtherDocuments**
The script closes the documents except the active one, it closes them without saving. It happens that you open many documents and various auxiliary elements, and to close them you need time, which you are wasting, the script will help you save time.
## Usage:
1. Select objects
2. Select the desired settings
    - You can copy an object to the clipboard and use it as an object to insert.
3. Run script File → Scripts → forceCloseOtherDocuments.jsx
4. Press "OK" or press enter

![ForceCloseOtherDocuments](/images/forceCloseOtherDocuments.gif)


## **BatchTextEdit**
Script for editing the contents of the text frames all together.
Author: [Hiroyuki Sato](https://github.com/shspage). Modify (sort by [Layers] and reverse): Alexander Ladygin
## Usage:
1. Select the textframe(s).
2. Run script File → Scripts → batchTextEdit.jsx
3. Edit the contents in the dialog.
4. Press "OK" or press enter


## **CompoundFix**
Script to fix the bug in compoundPathItems. In compoundPathItem there can be a group, because of which there are all sorts of problems, this script will help to fix this bug.
## Usage:
1. Select items (optional).
2. Run script File → Scripts → compoundFix.jsx
3. Select - fix all or selected.
4. Press "OK" or press enter


## **TransferSwatches**
The script copies color samples from the document to the active document while maintaining the hierarchy.
## Usage:
1. Run script File → Scripts → transferSwatches.jsx
2. Select the document from which to copy the swatches
3. Press "OK" or press enter

![TransferSwatches](/images/transferSwatches.gif)