# Medusa-Toolhead (Apex Mod)

This project adds several features to [Ch4rlesB's Medusa Toolhead](https://github.com/Ch4rlesB/Medusa-Toolhead/tree/main).

- **New clip-in belt mount design**
- **Optional bottom support brace**
- Added support for ebb36 toolhead board (keeps original support for umbilical and Hartk board)
- Lowered X endstop so that it activates against the Y carriage block (removes need for endstop flag)
- Strengthened zip tie slots
- Added right-side support arm
- Resized heat insert slots from 3.9D -> 3.8D

https://github.com/ApexArray/Medusa-Toolhead/assets/91706106/2dc37877-ce4a-4b54-b629-3e299c2d5c1f

New files are under the ./Apex_Mod folder:
- [STLs](./Apex_Mod/stls/)
- [CAD](./Apex_Mod/CAD/)

All other STLs (not modified by me) can be found in the original [./stls](./stls) directory

## New clip-in belt mount design

I'm not a fan of most toolhead belt mounting designs. I designed this solution to be:
- Light-weight
- Strong
- Semi-toolless
- Easy to assemble

Insert the belt into the cavity, and slide in a printable clip to hold it in place.

![Clip-in belt](img/apex_clip-in_belt.jpg)
![Clip-in belt weight](img/apex_clip-in_belt_weight.jpg)

https://github.com/ApexArray/Medusa-Toolhead/assets/91706106/179e2e59-fea6-49be-8833-3ce2743f321f

**Installation tip:** The two front clips sit between the belt and X gantry, and might be difficult to install if you have big fingers. I use a screwdriver or thin wrench to keep the clip aligned while sliding it into the cavity.

## (optional) Bottom support block

**UNTESTED**

The original toolhead seemed to have excessive Y wobble during fast printing. The fan duct provides some support, but the duct itself is cantilevered from the back and seemed to result in a "diving board" board effect.

This support block aims to reinforce the front of the toolhead and minimize any bouncing/wobbling.

The block is attached using two m3x35mm screws, so it does add some weight. More testing is needed to determine if it provides any real improvement.

![apex support block transparent](img/apex_support_block_transparent.png)
![apex support block](img/apex_support_block.png)

## CAD

I tried to keep a tidy f360 timeline on this project. With some exceptions, most features are contained in their own group and labeled accordingly. You should be able to delete/change most features without affecting the rest of the model.

![apex f360 timeline](./img/apex_f360_timeline.png)

## BOM

Uses the same hardware from the original project, plus:
- 2x m3x35mm screws (optional - bottom support block)
- +2 heat inserts (bottom support block)
- +2 heat inserts (for ebb36 + hartk/umbilical support)

## TODO

- Input shaper testing (with and without bottom support block)
- Add support for 1515 gantry
- Beta testing - any volunteers? 🙂

## LICENSE
All files released under the same [GNU General Public License v3.0](./LICENSE) as the original project.
