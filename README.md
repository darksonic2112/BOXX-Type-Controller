# BOXX-Type Controller

This repository contains "building-block" stl-files to create a BOXX-Type controller.

## TL;DR
If you just care about the put-together BOXX:
The "Sample BOXX" file contains 3 files (backplate has to be printed twice). 
You need to carve out a way so you can connect your e.g. arduino with the outside world.
The "DARKSONIC BOXX" (No Name Alternative included) is customized for an Arduino micro and a 12mm x 6mm USB-C female.
Adjustments can be made with any tool that takes stl files (I used  https://www.tinkercad.com).


## Elements and Measurements of the modular components

### Raw half
- Carved out half of the controller without any keyswitch holes or reinforcements
- Outside: 180mm x 170mm x 30mm
- Inside:	170mm x 160mm x 25mm
- Edges and surface: 5mm thick

### Screw Reinforcements Corners
- Reinforcements for the screws at the corners and along the edges
- Reinfrocement blocks: 10mm x 10mm x 20mm
- Screw hole: 3mm diameter x 8mm depth

### Connection Pieces
- Connect both halfs through the middle
- Pin: 5mm diameter x 15mm length
- Pin-hole: 5.22mm diameter x 5mm depth
- Screw hole (big): 7mm
- Screw hole (small): (combined) 3mm each 
- Note: The connection pieces are intended to have a 10mm wall between them. The small screw hole is for the screw to be screwed in, while the big screw hole just indicates the spot and reduces the distance to the other connection piece

### Backplate
- Attaches to the back of the controller
- Backplate: 170mm x 160mm x 5mm
- Screw holes: 3mm diameter x 5mm depth

### Elevation
- Elevates and hides the screws from the backplate of the controller, so that the screws do not touch the surface its standing on.
- Elevation: 10mm diameter x 3mm (total 6mm) height
- Ring on top of elevation: 10mm diameter x 3mm height with a 7mm diameter x 3mm height carve in
- Screw hole: 3mm diameter x 3mm depth

### Support Beam
- Enhances durability of the backplates
- Support Beam: 10mm diameter x 20mm height

### Cable Management
- For the cables that connect the key-switches to the e.g. arduino
- Cable management structure: 10mm x 10mm
- Cable management hole: 5mm x 5mm

## BOXX Controllers

### Sample BOXX
- The Sample BOXX is all module components above (except cable management) put together. Since I couldn't find a good way to represent the key-switch-holes as a component, you have to arve them out yourself, if you are unhappy with the layout.
- Key-switch-holes 14mm x 14mm x 10mm (5mm outside of the controller + 5mm reinforcements)
- Key-switch-hole reinforcements: 5mm thick (custom shaped for each layout so no length/width)
- Hole at the connection point: 5mm (each side) x 80mm x 20mm

### DARKSONIC BOXX
- The DARKSONIC BOXX is a bit more customized to my liking. Includes cable magement, a spot for the Arduino-micro to fit in, and an oval hole that fits a 12mm x 6mm USB-C female. I generated the Text through "Text2STL" and used the font "Brown Beige" and reinforced it with a 5mm thick backplate. Additionally the Edges are smoothed out a bit.
- Has same measurements as the Sample BOXX
- A "No Name Alternative" is included, if you like the overall design but not the name :,)



