# The-Summit
Open source foldout key holder designed for FFF in Autodesk Fusion

Keychains are bulky and ugly looking, make a lot of noise and can damage other stuff in your pocket.
Swiss Army knife-style key holders exist but like a good wallet they cost a premium.

Enter **The Summit**: A free, open-source key holder you can download, print, modify and gift to friends (or sell for that matter, it's WTF licensed so who cares?)

![Design_full](/Image/Design_full.png)
Project is also available on [Printables](https://www.printables.com/model/924801)

## Inspiration
This project is inspired quite heavily by [The Ridge keyring (get it?)](https://ridgewallet.eu/collections/keycase) but instead of premium, pricey, pristine machined aluminum you can make it out of petty PLA plastic (or even nifty Nylon, if you like)
Similar 3d printed projects do exist, I've been using [this one](https://www.printables.com/model/159941) for quite a while now but the opposing sides and thin ring haven't been very good.

## Parts
Project is located under [Summit.f3d](/Summit.f3d).  
Output files (STLs and STEP) are located under [Output](/Output).  
Sample image files with recommended orientation etc. can be found in [Image](/Image)

You can open Summit.f3d and adjust the size and number of keys you need in the Modify > Change Parameters menu.

#### Exported STLs are for:
- 3 Keys 
- 80\*28\*2.8 (length\*width\*thickness) this is the longest any of your keys can be, others can be smaller obviously but max count is what you set in Key_Count

#### Model consists of 5 parts:
- Plate_top/bottom: the two faceplates of your key holder, PLA works but ABS/PETG is more durable
	- Infill: >40% recommended, 3 walls
	- Layer height: 0.15-0.2
	- Orientation: outward face pointing up
	- Adhesion: skirt recommended
	- Support: only the edge where the D-plate screws into, do support with 0.2-0.4mm gap
- Keyhole_cap: Print **two** of these in some contrasting/complimentary color to your body plates, they will cover up the M3 hole and nut
	- Layer height: <0.2mm preferred
	- Orientation: either face-up or face-down, whichever works best
	- Support: only if you print it face-up
- D_plate: Plate that holds the keyring and bottom M3 nut in place
	- Layer height: 0.2
	- Orientation: big overhang on the top side
	- Support: definitely, try not to block the screw holes though
- Midpost: Central standoff for holding the keyring in place
	- Orientation: Upright (if you can print it otherwise I will be impressed)

### Non-printable parts needed:
- 2x M3 hex machine screws with matching nuts. Length depends on config, default is 20mm
- 2x M2.5 flat, thin capped screws for holding the D-plate. Length depends on config, default is 8mm
- 1x M2.5x3 flat, thin capped screw for holding the bottom hex nut in place
- M3/M4 washers, one for each key or as you see fit.
- 24mm or similarly sized large keyring for attaching other stuff, carabiner clip or flair of your choice.

## Assembly
- Clean all supports thoroughly, especially under the two faceplates
- Screw one M3 bolt through the top of Plate_top
- Put keys and washers through in an alternating fashion or as needed
- Put hex nut in small pocket of D-plate, add D-plate on top of the faceplate and screw in the little back side hole with the M2.5x3 screw
- Screw D-plate with M2.5 screw from top side
- Screw second M3 bolt through Plate_bottom and add the midpost tube around it
- Press-fit hex nut on the pocket of the top side of the plate tightly
- Bring the two plates together, tighten all screws, check play on keys and adjust tension as needed
- Add Keyhole caps to top and bottom plates
- Welcome to the Top of the Mountain
![Printed_full](/Image/Printed_full.jpg)

This project is licensed under the WTFPL license, which can be read in full in [LICENSE.md](/LICENSE.md)

