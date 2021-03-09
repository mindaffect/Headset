# MindAffect Snap Electrodes Headband

Here you find the `.stl` print files and instructions on how to assemble the snap-electrodes low-cost EEG headband developed by MindAffect B.V.

# Components Required

To make this headband you will need:

 1. The main electrode holding piece.  This should be 3d-printed using a relatively flexible material following this [stl file](main.stl)
 2. The electrode cross-piece.  As well as holding 6 electrodes in the horizontal headband, our design allows for 2 vertically displaced electrodes around `Oz`.   These are held by the vertical piece.  This should be printed using a relatively flexible material following the stl file [vertical Piece](verticalPiece.stl)
 3. 8 sponge-tubes.  Our design uses water-soaked sponges to bridge the connection between the electrode-pellet and the scalp.  The sponges are held in the sponge tube.  You should print 8 of these with hard or flexible material using the [sponge-tube](sponge-tube.stl)
 4. 8 3mm x 8mm screws + bolts.  To hold the vertical piece and the expandable side pieces you will need 8 small bolts+screws.
 5. Left spring piece.  The headband must stretch to fit different head-sizes.  This with the spring pieces.  You should print with rubber-like material the [sprint-left](spring-left.stl)
 6. Right spring piece.  The headband must stretch to fit different head-sizes.  This with the spring pieces.  You should print with rubber-like material the [sprint-right](spring-right.stl)
 7. Forehead strap.  The forehead strap goes over the forehead between the 2 spring pieces.  This should be a strap of approx 20mm x 300mm and ~1mm thick.  If using the spring-pieces it does not *need* to be elasticated, though that may be more comfortable.
 8. (Option)  Instead of using the left/right spring pieces, 
 9. 8 Electrode-Pellets.  These sliver/sliver-chloride pellets provide the connection between the snap-connector wire and the water sponge.  For this design we have used the *Thought Technology SA9329*  pellets for ECG.  These can be ordered from [biomedical.com](https://bio-medical.com/ekgecg-pellets-for-sa9329.html)
 10. 8 Snap-electrode wires:  The electrode pellets easily damaged and need to be replaced.  So use the snap connector to connect to your amplifier.  Many possible snap cables are available, for example from here [din ecg cable snap]<https://www.google.com/search?q=Din+Holter+Ecg-kabel+10>.   Alternatively, you may just order the snap-connectors such as [ecg cable snap end](https://www.google.com/search?q=ecg+cable+snap+end) and make up the cables yourself.
 11. Electrode-wire to amplifier connector.  Depending on your amplifier and snap-connectors used, you may need a final connector between the cable and the amplifier.  For example to connect DIN ends to jumper ends on an openBCI amplifier.    When using the openBCI we have instead made up a cable end for direction connection with a 12x2 jumper header cable connector such as [12 x 2 header connector cable] (https://www.google.com/search?q=Jumper-12-x-2-header-cable-connector).

# 3d Print Instructions

As the headset should conform to a persons head, we recommend semi-flexible print materials.  Stiff material like PLA, PETG or ABS is too rigid and won't work.  We have used "Renkforce Flexible Filament" but any rubber-like semi-flexible material should work.

If using a home printer, we have used the following settings -- thought the best settings will depend on your particular printer.
  * Nozzle: 0.4mm
  * Extrusion width: .05mm
  * Layerheight: 0.25mm
  * Brim: 3mm
  * Speed: 20mm/s
  * Infill: 40% (Though this value should be adjusted for the flexibility of your material, use a higher value for more flexible materials.)
  * Perimeters: 5
  * Bottom layers: 5
  * Top layers: 5

# Assembly Instructions:

   1. 



# Support

If you run into issues, either raise  an issue directly on github, or contact the developers on [gitter](https://gitter.im/mindaffect) -- to complain,complement or just chat.

