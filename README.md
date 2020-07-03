# 3dprinting
My settings and files used in my 3d printing endeavors

Thingiverse profile: https://www.thingiverse.com/schraitle

# Upgrades
- X-belt tensioner: https://www.thingiverse.com/thing:1683070
  * Having a tight x-belt made all the difference in the world. I actually had to manually tighten it before I could even print this tensioner. Before tightening it down, I couldn't create good circles and it prevented me from making a lot of other upgrades.
- Y-belt tensioner: https://www.thingiverse.com/thing:1959208
- Front frame brace: https://www.thingiverse.com/thing:1857991
- T-corner brace: https://www.thingiverse.com/thing:1672959
- Centered fan duct: https://www.thingiverse.com/thing:1620630
- Wingnut knobs: https://www.thingiverse.com/thing:2000216
  * they really are pretty useful
- Bed spring washers: https://www.thingiverse.com/thing:1895223
  * seemed like a waste of time, I'm not sure if they actually make anything better, but they do keep the springs straight
- Extruder button: https://www.thingiverse.com/thing:1935151
- Offset Y Belt Holder - https://www.thingiverse.com/thing:3085862
- X Belt Holder - https://www.thingiverse.com/thing:2016779
- X Cable Guide - https://www.thingiverse.com/thing:3852355
- Scrap Catch Tray - https://www.prusaprinters.org/prints/17835-anet-a8-scrap-catch-tray
- Z Height Jig - https://www.thingiverse.com/thing:2538266
  * useful to use every once in a while to make sure the gantry is level

# Planned upgrades

# Installed hardware
- Solid Polymer bearing replacement: https://www.amazon.com/gp/product/B06XPRCMJS
- MOSFET: https://www.amazon.com/gp/product/B01HEQVQAK
- Raspberry Pi 3B+: https://www.amazon.com/gp/product/B07BDR5PDW
  * installed octopi on it: https://octoprint.org/download/
- fiber reinforced belts - https://www.amazon.com/gp/product/B071K8HYB4
- auto bed leveler - https://www.amazon.com/gp/product/B073XC5T7B
  * using https://3dprint.wiki/reprap/anet/a8/improvement/autobedleveling#sensor_support for reference
  * will require sensor support for extruder: https://www.thingiverse.com/thing:1911146
  * also requires a wiring connector which I don't have: https://www.amazon.com/gp/product/B01M28QHF7
  * and need to rethink the cooling duct because most won't fit anymore due to the sensor support.
- PEI bed surface - https://www.amazon.com/dp/B07695DLL9/
  * Initial concern was that the extra thickness would interfere with bed leveling. It isn't an issue though, and leveling still works great.
- Wall mounted spool holder
  * Made from a closet rod set from Home Depot, holds a bunch of spools and works great.
  * Custom printed endcaps for the pipes so that the spools can't fall off.
    * https://www.prusaprinters.org/prints/20110-closet-rod-endcap
  
# Software
- Modeling: https://www.autodesk.com/products/fusion-360/overview
  * free for hobbyists, tons of youtube videos and tutorials online 
- Slicing: https://ultimaker.com/en/products/ultimaker-cura-software
- Marlin: http://marlinfw.org/
  * using the a8 example configuration with auto bed leveling set with the PROBE_MANUALLY flag
- Klipper: installed Klipper and am using the config file in klipper/printer.cfg

# Unused upgrades
- Filament guide: https://www.thingiverse.com/thing:1764285
  * I printed it draft, and it was very scratchy sounding while filament was going through so I took it off. I also didn't like how filament could get stuck in the gap for loading filament into the loop.
- X cable chain - https://www.thingiverse.com/thing:2104821
  * noticed that the cable stretching over the top of the frame caused the ABL to misread on the left side, need a solution for cable stretching, cable chain seems good
    - abandoned the cable chain, it was flexing the ABL cable too much and causing inconsistent leveling. I'll look further into better ways to hang the cable over the top of the frame
  * motor mount doesn't need to have a z endstop, will use this one - https://www.thingiverse.com/thing:2055872
- Universal spool holder: https://www.thingiverse.com/thing:767317
- Top mounted spool holder: https://www.thingiverse.com/thing:2162266
  * a little wobbly, I've read that top mounted spools create instability on the frame so we'll see how it goes. It saves desk space though, so I'm keeping it for now.
  * it actually moves laterally quite a bit, I tried to make a brace for it but I don't think it's going to help

