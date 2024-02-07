# Dynamic Cameras Radial Menu
This tool dynamically generates a radial menu from the cameras in the scene and sets the viewport to look through one of them.

![menu in use](https://github.com/alexmajewski/houdini-camera-radial-menu/assets/77795178/501e1637-6828-4e5b-b68a-0bad601a3e11)

It uses the native Houdini radial menu system. It works in Solaris and /obj.

## Usage
Select the 'Cameras' option from the menu dropdown at the top of the screen (located in the 'Standard' section), and press 'C' key with your cursor in the 3D Viewport in order to access the menu. 

You can also enter Edit Radial Menus window available in the dropdown and set a custom hotkey.

![menu_dropdown](https://github.com/alexmajewski/houdini-camera-radial-menu/assets/77795178/6b0312d9-dfda-476f-82db-e9998c06263d)

![creating menu](https://github.com/alexmajewski/houdini-camera-radial-menu/assets/77795178/41d1c7f9-250e-4eda-b2e4-06d373f463a0)

There are 8 slots in the radial menu. If the total number of cameras in the scene/graph is higher than this, they will be omitted.

In order to give priority to cameras when there's more than 8, in Solaris you can add them to `%camera_menu` collection. Currently, there's no solution like this for /obj context yet.

## Installing as a Package
Edit the .JSON file and replace the file path to the actual location of the package folder on your disk, and copy it to your Houdini user preferences directory into a `/packages/` folder, i.e. `C:/Users/You/Documents/houdini19.5/packages/`.

Alternatively, you can just put the .radialmenu file inside a `/radialmenu/` folder inside the houdini preferences directory.

Once properly installed, a new option 'Cameras' should appear in the radial menu dropdown at the top of the screen. 

## External platforms
This product is also available [on Gumroad](https://alexmajewski.gumroad.com/l/dynamic-cameras-radial-menu), where you can add it to your library or even leave me a tip.
