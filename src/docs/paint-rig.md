# ![paintrig Icon](img\duik-icons\automation\paintrig-icon-r.png) Paint Rig

![Paint rig panel](img\duik-screenshots\S-Rigging\S-Rigging-Automations\PaintRig.PNG)

Use the "Paint Rig" to rig brush strokes in the paint effect and adjust and animate them as if they were a single stroke.

## Setup

1. Select some paint strokes
2. Click on the "Paint Rig" button

You can adjust and animate the paint strokes in the effects of the layer.

## Effect

![Paint rig panel](img\duik-screenshots\S-Rigging\S-Rigging-Automations\Paintrig-effects.PNG)
![Paint rig example](img\duik-screenshots\S-Rigging\S-Rigging-Automations\automation-illustration\paintrig-example.png)

The start, end, Color and Diameter paramaters work like the same parameters in the individual stroles, but as controlling all of them as if they were a single one.

Diameter and Color are divided into two parameters to be able to interpolate from the first stroke to the last one, and act like a ramp through all the strokes.

You can change how this ramp works in the "Interpolation" section.

The order of the strokes can be changed at any time by reordering them in the layer stack.
