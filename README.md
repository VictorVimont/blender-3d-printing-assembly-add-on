# blender-3d-printing-assembly-add-on

Add-on cutting meshes into smaller bricks of customizable size. This add-on was originally designed as a tool for 3D printing assembly.



##Features :

➡️ Procedural boolean designed to avoid crashes.

➡️ Customization of boolean type.

➡️ Progression bar and estimated time left.

➡️ Quick export of the bricks.



##How to use :

###➡️ Select object to convert into bricks

###➡️ Boolean settings

Customize boolean setting used by Blender to calculate brick intersection with the 3D model.

###➡️ Generate or define domain :

Domain is a volume used to define the area covered by bricks and intersect with the original mesh creating a duplicate. You can choose using a custom existing object as a domain instead if wanted.

###➡️ Apply domain :

This function intersect the domain with the base mesh.

###➡️ Bricks settings :

Used to set bricks size and allowing to quickly generate, delete and export them.

###➡️ Process :

Automatically intersect each generated brick with the domain object. Show time left and total generated bricks. Empty bricks will be deleted at the end of the process.


3D Printing assembly add-on is still in development. 

Code is also available on Gumroad : https://grynger.gumroad.com/l/feogv

I'm an artist, you can follow my work on social media @victor.vimont and on my website : victorvimont.fr

It is my first add-on, feedback are appreciated.



##Features incoming :

- Use original mesh instead of a domain for brick génération if no domain are defined.
- Allow choosing if empty bricks should be deleted at the end of the process.
- Brick pattern section under brick panels.
- Pause and resume process
- Brick spacing
- French translation
