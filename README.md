# Spore-IconGenerator


A super quick and easy to use mod which creates a custom category with 40 empty pages, each one can store a part for generating high resolution part icons that can be edited afterwards in any image editor to cut down to size or add drop shadows too.


To use, make sure you download the package and drop it into Spore's dataEP1 folder along with the other packages lurking there. After which you can modify the items in the super handy [SporeModder FX](https://emd4600.github.io/SporeModder-FX/ "SporeModder FX") tool. The only files you have to modify are those in `creature_editor_palette_items~`, paste the name of your creature part file in the `creature_rigblock~` folder into the `ce_page_icongen_page00_parts.prop.prop_t` file:

![image](https://github.com/CarrioNet/Spore-IconGenerator/assets/10189147/41f0abf8-6113-43c7-bae2-91f8d61a55c5)

Like so:

![image](https://github.com/CarrioNet/Spore-IconGenerator/assets/10189147/2d16858a-42d9-4057-8209-8728a957a7e3)

Repeat for each part you want to generate an icon for in the following `ce_page_icongen_page01_parts.prop.prop_t, ce_page_icongen_page02_parts.prop.prop_t, ce_page_icongen_page03_parts.prop.prop_t,` etc... To make part icon generation faster, feel free to drop your rigblock and model files in their respective folders.


Contains a python script (3.9.0) to reset the page files as well so you don't have to manually go through each one to clear them out, and can be modified to change how many template files you want to generate or even the specifics or dimensions you want the corresponding part icons to come out at, it's currently set to export within the range of 500x500 (dimensions may vary based on monitor size and part dimensions). The only files that will be reset by the script are those in `creature_editor_palette_items~`, `creature_editor_palette_pages~` and `creature_editor_palette_~`.


Be sure to take a look at [emd4600's part icon tutorial](https://github.com/emd4600/SporeModder-FX/wiki/How-to:-Generate-perfect-part-thumbnails "How to: Generate perfect part thumbnails") for the specifics and the console command.


Requires the [ModCreatorKit](https://github.com/emd4600/Spore-ModAPI/tree/master/Projects/Example%20Projects/ModCreatorKit#modcreatorkit "ModCreatorKit") and the [Spore ModAPI Launcher](http://davoonline.com/sporemodder/rob55rod/ModAPI/Public/ "Spore ModAPI Launcher") and obviously the above mentioned SporeModder FX tool.
