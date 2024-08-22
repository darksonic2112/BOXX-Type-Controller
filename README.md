# BOXX-Type Controller

This repository contains "building-block" stl-files to create a BOXX-Type controller, and a few put-together examples of BOXXes. 

## TL;DR
If you just care about the put-together BOXX's:
The "Sample BOXX" file contains 4 files for the 2 fronts and 2 backplates. 
You need to carve out a way so you can connect your e.g. arduino with the consol/PC, and you need a way to connect the two halfes.

The "DARKSONIC BOXX" (No Name Alternative included) is customized for an Arduino micro and a 12mm x 6mm USB-C female.
Adjustments can be made with any tool that takes stl files (I used https://www.tinkercad.com).

## My Expirience putting the BOXX together
Here I want to share my experience putting the BOXX together and provide a bit of guidance in the assembling process. Read especially if you just want to copy the design.
### All-Boxes:
- The key-switch holes for the most part were right on the edge of being too lose, with 3 of them being too lose. Since I used the same "drill out" for every key-switch hole, it must be an inconsistent print. Regardless, consider printing them a bit tigher (take of 0.5mm - 1mm on both length and width).

### DARKSONIC BOXX / No Name Alternative
- The connection pieces hold the two halfes together very well. I needed a hammer to get them together. There is a slight gap (>1mm, still visible tho) that could be resolved by changing the position of the connection pieces or the depth of the holes. The 4mm screw hole on the Connection_Piece_A is too lose and should be 3mm. As it is, you can screw the screw in at its not lose (you cant hear it when shaking), but it doesn't feel like its holding a lot.
- The USB-C hole holds the USB-C female in place and is tight. Could be reinforced with glue, but is not necessary as far as i can tell.
- Getting rid of the holes inside the connection pieces requires a relatively small plier. If you decide to use letters, the pin holes for the letters required a drill (for me at least). After putting the letters in they fit very well and it feels stable.
- The cable management feels nice, but gets tight after 7 cables. If you decide to use them for all cables, the hole should be a bit bigger (7mm x 7mm). Also consider you need more cable, especially for the edges, if you use the cable management.
- The Arduino-Micro fits well in the placeholder, as long as the cables soldered into the Arduino doesnt strain the Arduino too much.
- The backplates are a little bit different due to the connection pieces. If you want them to be perfectly even, you should re-drill them.

## Bought components for the BOXX 
- Screws: https://www.amazon.de/100-St%C3%BCck-Spanplattenschrauben-3x16-Holzschrauben/dp/B07MZXY4BF/ref=sr_1_8?crid=22LCMUKAWQKCP&dib=eyJ2IjoiMSJ9.i3L52VrZmGBCB-ok7lppPkHq2hkHK5nQcFBF0FH_1rZNVSHtM5XIJvVryZu625tpWsa-vSkyCybq8qfu78kJHWnc4lwbdmjmLPTUsPp-OHlwkiKnfq9tcxXCvC6DiUeO54JfVSQM4lo9Xl1bQdWh8CuHT8ebj47gL1vTBGEb80Jzbl1TYywApqL-aerzdCAwSUGRFxTBNTqkCklqN3IS7vX5A-SHA3RhV0sYjc4CiGob7G77d8z4rMVvRb7LWIZL09Xf0GcLR4RSBTz4zVO_6S20zRUHJyWYws_41QpYbY4.vCiy1hQkRZ-K9hRs87U5pWB8adM1zw_V787V0zRIPY0&dib_tag=se&keywords=screw%2B3x16&qid=1724330831&sprefix=screw%2B3x16%2Caps%2C88&sr=8-8&th=1 The Screws were okay, but I think there are better ones out there. Especially the head of the screw requires a star-screw driver or star allen key, which maybe doesn't lie around in every household. Would not recommend.
- USB-C Male to Female: https://www.amazon.de/gp/product/B0CG19V466/ref=ox_sc_act_title_3?smid=A1ADA6OYVN5V19&psc=1 I liked the design, its short and cheap. Would recommend.

## Elements and Measurements of the modular components

### Raw half
- Carved out half of the controller without any keyswitch holes or reinforcements.
- Outside: 180mm x 170mm x 30mm
- Inside:	170mm x 160mm x 25mm
- Edges and surface: 5mm thick

### Screw Reinforcements Corners
- Reinforcements for the screws at the corners and along the edges.
- Reinfrocement blocks: 10mm x 10mm x 20mm
- Screw hole: 3mm diameter x 8mm depth

### Connection Pieces
- Connect both halfs through the middle.
- "Connection Piece A" goes into "Connection Piece B"
- Pin: 5mm diameter x 15mm length
- Pin-hole: 5.22mm diameter x 5mm depth
- Screw hole (big): 7mm diameter
- Connection_Pice_A Screw hole (small): 4mm diameter (Note: After assembling I find this too lose for the specific screws I used. 3mm diameter is prolly better.)
- Connection_Pice_B Screw hole (small): 3mm diameter 
- Note: The connection pieces sould be strong enough to hold on their own, but can be reinforced with a 16mm x 3mm screw. The connection pieces are intended to have a 10mm thick wall, with a 3mm diameter screw hole between them. The small screw hole is for the screw to be screwed in, while the big screw hole just indicates the spot and reduces the distance to the other connection piece.

### Backplate
- Attaches to the back of the controller
- Backplate: 170mm x 160mm x 5mm
- Screw holes: 3mm diameter x 5mm depth
- Note: There is a "right" and "left" backplate, which are slightly different and I was too lazy to adjust.

### Elevation
- Elevates and hides the screws from the backplate of the controller, so that the screws do not touch the surface its standing on.
- Elevation: 10mm diameter x 3mm (total 6mm) height
- Ring on top of elevation: 10mm diameter x 3mm height with a 7mm diameter x 3mm height carve in
- Screw hole: 3mm diameter x 3mm depth

### Support Beam
- Enhances durability of the backplates
- Support Beam: 10mm diameter x 20mm height

### Cable Management
- For the cables that connect the key-switches to the e.g. arduino.
- Cable management structure: 10mm x 10mm
- Cable management hole: 5mm x 5mm
- Note: I fit a maximum of 7 1mm diameter cables through one of the cable management holes and it was getting tight. Adjust the size if you want to fit more than 7 cables.

## BOXX Controllers

### Sample BOXX
- The Sample BOXX is very basic put together BOXX. You need a way to connect your e.g. arduino with the consol/PC. Besides that, you also need a way to connect the two halfes, for example through the Connection Pieces that are provided as an stl. Since I couldn't find a good way to represent the key-switch-holes as a component, you have to carve them out yourself, if you are unhappy with the layout.
- Key-switch-holes 14mm x 14mm x 10mm (5mm outside of the controller + 5mm reinforcements)
- Key-switch-hole reinforcements: 5mm thick (custom shaped for each layout so no length/width)

### DARKSONIC BOXX
- The DARKSONIC BOXX is a bit more customized to my liking. Includes cable magement, a spot for the Arduino-micro to fit in, and an oval hole that fits a 12mm x 6mm USB-C female. I generated the Text through "Text2STL" and used the font "Brown Beige" and reinforced it with a 5mm thick backplate. Additionally the Edges are smoothed out a bit.
- Has same measurements as the Sample BOXX
- Hole at the connection point: 10mm (each side 5mm) x 80mm x 20mm
- A "No Name Alternative" is included, if you like the overall design but not the name. :,)
