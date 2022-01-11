# kicad-LED_DotMatrix

# Installation #
Drag and drop the lib_fp, lib_sch and 3d_models folders into the project directory. This is where the .pro file is located. It is now be possible to use the symbol and footprint. The 3D models are referenced using Kicad relative directories:

* ${KIPRJMOD}/3d_models/LED_1088.step (For the true component)
* ${KISYS3DMOD}/Socket_Strips.3dshapes/Socket_Strip_Straight_1x08_Pitch2.54mm.wrl (It is also possible to mount the matrix in 2.54mm headers).


# Symbols #
This have the circuit diagram of the drawn onto the symbol. These dotmatrix modules have a weird pinout, which makes them incredibly frustrating to work with.
![1088AS](images/1088AS.png?raw=true "1088AS")
![1088BS](images/1088BS.png?raw=true "1088BS")

# 3D renderings #
![Top view of dot matrix module.](renders/1088-top.png?raw=true)
![Bottom view of dot matrix module.](renders/1088-bot.png?raw=true)