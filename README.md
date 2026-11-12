# FreeCAD Framerator
FreeCAD project that generates a picture frame based on spreadsheet values

## How To Use
Simply open up the project in [FreeCAD](https://freecad.org). Then double click the "spreadsheet dimensions" in the tree to edit the values. ALL VALUES ARE IN METRIC MM.

It should generate the frame model based on those.

## Exporting as mesh for printing
After generating your frame, open the "Mesh" workbench in FreeCAD using the pulldown menu. Then click the body (frame, glass_holder) you wish to export. Then under the "Mesh" menu up top in the menu bar, click "Generate Mesh From Shape". You'll see a new mesh object in the tree viewer. Click that and select "Export Mesh" to save the STL.

## What is the "Glass Holder"?

It's just a small frame within the frame. It's meant to interference fit or be glue in place, sandwiching a piece of glass or plexi between it and the print/photo itself. It's optional if you just want to glue on the print to the backing.

## What is the "hook groove?"

These are just optional holes on all side of the print you can stick a tack or nail to hang with. Like the glass holder, you can toggle this in the spreadsheet on or off. If you don't want to deal with the potentially more complex print (though the default 40 degree angle shouldn't require any support) just export it without the groove holes and stick on or screw on standard framing mount options.
