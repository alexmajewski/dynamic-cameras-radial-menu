# Dynamic Cameras Radial Menu
This tool dynamically generates a radial menu from the cameras in the scene and sets the viewport to look through one of them.

It uses the native Houdini radial menu system. It works in Solaris and /obj.

## Usage
Select the menu from the dropdown at the top of the screen, and press 'C' key with your cursor in the 3D Viewport in order to access the menu. You can also enter Edit Radial Menus window available in the dropdown and set a custom hotkey.

There are 8 slots in the radial menu. If the total number of cameras in the scene/graph is higher than this, they will be omitted.

In Solaris, you can give priority to cameras by adding them to `%camera_menu` collection.

## Installing as a Package
Edit the .JSON file and replace the file path to the actual location of the package folder on your disk, and copy it to your Houdini user preferences into a packages folder, i.e. `C:/Users/You/Documents/houdini19.5/packages/`.

Once properly installed, a new option 'Cameras' should appear in the radial menu dropdown at the top of the screen. 
