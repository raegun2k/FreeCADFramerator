# FreeCAD Framerator
FreeCAD project that generates a picture frame based on spreadsheet values. I created this after getting too many oddly shaped prints at artist alleys :) 

<img width="1301" height="816" alt="freecadframerator2" src="https://github.com/user-attachments/assets/3bd1ef21-2dfc-4eae-a1b7-f1245ea28df1" />


## How To Use
Simply open up the project in [FreeCAD](https://freecad.org). Then double click the "spreadsheet_dimensions" in the model tree viewer to edit the values. ALL VALUES ARE IN METRIC MM.

It should generate the frame model based on those when you go back to the model editor after editing the spreadhseet.

## Exporting as mesh for printing
2) After generating your frame, open the "Mesh" workbench in FreeCAD using the pulldown menu. 
<img width="1710" height="1083" alt="meshworkbench1" src="https://github.com/user-attachments/assets/a142a8dc-d377-4f33-9d29-222f600d3f40" />

3) Then click the body (frame, glass_holder) you wish to export.
<img width="359" height="242" alt="meshselectobject" src="https://github.com/user-attachments/assets/233ba262-a083-460c-b45d-0a8af24cd846" />


4) Then under the "Mesh" menu up top in the menu bar, click "Mesh From Shape".
<img width="1147" height="392" alt="meshfromshape1" src="https://github.com/user-attachments/assets/1c9d995c-3eab-41f0-a7db-0d70050317c0" />

5) You can likely keep the default options in the Task window. Just click "Okay"
<img width="1165" height="1541" alt="meshfromshape2" src="https://github.com/user-attachments/assets/b749554d-cc0e-476b-925b-aa21fead8ad8" />


6) You'll see a new mesh object in the tree viewer. 
<img width="341" height="210" alt="meshfromshape3" src="https://github.com/user-attachments/assets/d6492f3f-a14a-4b20-8d91-099e8444960c" />


7) Click that and select "Export Mesh" to save the STL.
<img width="420" height="317" alt="meshfromshape4" src="https://github.com/user-attachments/assets/e42a31c6-1908-433a-94c0-cb2736bd9507" />


## What is the "Glass Holder"?

It's just a small frame within the frame. It's meant to interference fit or be glue in place, sandwiching a piece of glass or plexi between it and the print/photo itself. It's optional if you just want to glue on the print to the backing.

<img width="1145" height="506" alt="glass_holder" src="https://github.com/user-attachments/assets/42e729b7-22e3-492a-b8bc-1e0ef789e630" />


## What is the "hook groove?"

These are just optional holes on all side of the print you can stick a tack or nail to hang with. Like the glass holder, you can toggle this in the spreadsheet on or off. If you don't want to deal with the potentially more complex print (though the default 40 degree angle shouldn't require any support) just export it without the groove holes and stick on or screw on standard framing mount options.
