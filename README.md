# BodyBuilder for FreeCAD

Usage:
By creating a binding of a Body to a Sketch the macro will keep them attached, the binding is an aligninment of the Body origin to the sketch 
origin. The Body can be positioned (relative to the sketch attachment) after the binding is created. 
Two important things about selection, (read at least twice):
1) To create a binding in the Binding menu) the Body has to be selected in the 3D space. 
2) While in the Positioning and Binding menus, selections in the 3D space are normally a face selection, the macro will convert the selection to 
the entire body.  

----------------------------------------------------------------------------------------------------------------------------------------------------------
MAIN MENU:
Exit:
This will exit the macro

To Positioning button:
This will take you to the Positioning menu

Sketch 3D view: When opening a sketch the view will stay in the current view, clicking this while in sketch edit will toggle the view 3D -2D

Sketch origin: Will display the selected sketch X and Y coordinates, this is useful if the sketch origin has moved i.e. Attachment offset
Face Ref. Sketch: Click on any planar face and click this option, the maco will create a sketch of the face and place it in the current Active BodyMain menu.

POSITIONING MENU:
To Main button: This will take you back to the main menu

Sketch 3D view: has been described previously

X-Ray Selected:
Click an object in the 3D and click this button, the object will toggle between total solid and 62% transparent. The macro will only 
	respond to these values of transparency.
Edit binding button:
This will take you to the edit binding menu
Adjustment fields will be described later.
Reposition sketch origin: While in sketch edit, place a vertex anywhere in the sketch and check this box, the sketch origin will move to the vertex.
	More later on this option.
Input step:
This is the step increment/decrement when changing the positioning fields.
Update model:
This will do a assemble connection update, sometimes required while bindings have changed and your in sketch edit.
Paste with binding:
If checked this will copy all the properties and the bindings with the objects. It's best to reposition a copied object after the paste because 
	the objects will be be stacked exactly on top of the original. Copied exactly, this make since.
BINDING MENU:
To Main button, Sketch 3D view, X-Ray Selected,To Positioning button, Paste with binding have been described previously: 
Builder status area: This will give you feedback as you select objects and will also give you a hint of what to do next. The binding properties are
	the Body positioning data, the binding (the target sketch object) can be deleted while retaining the binding properties. This is useful if you want to 
	switch a binding from one sketch to another, the Body will stay in the same orientation.
Delete Binding, Delete Properties: These options will only work on selections from the 3D space.
Paste with binding has been described previously: 
 
