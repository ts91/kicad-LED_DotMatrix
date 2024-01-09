# kicad-LED_DotMatrix

### Update January 2024
The libraries have been migrated to KiCad 7.x and where needed, cleaned up a bit.

# Installation
Import the libraries via KiCad's Symbol Editor (File | Add Library).
Symbol and footprint files are available.
The 3D models are referenced using Kicad relative directories:

* ${KIPRJMOD}/3d_models/LED_1088.step (For the true component)
* ${KISYS3DMOD}/Socket_Strips.3dshapes/Socket_Strip_Straight_1x08_Pitch2.54mm.wrl (It is also possible to mount the matrix in 2.54mm headers).


# Symbols
These dotmatrix modules have a weird pinout, which makes them incredibly frustrating to work with.
![1088AS](images/1088AS.png?raw=true "1088AS")
![1088BS](images/1088BS.png?raw=true "1088BS")

# 3D renderings
![Top view of dot matrix module.](renders/1088-top.png?raw=true)
![Bottom view of dot matrix module.](renders/1088-bot.png?raw=true)