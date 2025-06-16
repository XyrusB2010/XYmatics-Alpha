# XYmatics Alpha
This is a COREXY CNC platform with a toolchanger system. Inspired by the quick tool changing system used by the Prusa XL and DAKSH-V2, this CNC platform can switch between a laser engraver, CNC router and FDM extruder without requiring direct interaction.

# Features
 - Physical dimensions: 600x600x400mm
 - Bed dimensions: 500x500x300mm
 - Laser engraver, CNC router and FDM printer combined
 - Fast and expandable toolchanger system
 - COREXY kinematics

# Why create XYmatics?
My college has FDM printers and laser engravers, but they are too bulky and take up lots of space. To solve this problem, I created XYmatics Alpha to unify these two systems into one machine, as well as an included CNC router.

# How does the tool changing work?
The tool changing system used in XYmatics Alpha is much similar to the Prusa XL and DAKSH-V2. A carriage mounted onto the X gantry contains slots and magnet for the tool to mount on. When mounting, the carriage aligns itself with the tool and moves toward it. Once connected, the tool is removed from the dock by sliding it towards the side. The docking process is similar, but is completed in reverse order. The dock is a simple frame placed on the right side of the tool. Like the carriage, it has pins and magnets to ensure that the tool will stay in place.

Because the tool changer system doesn't require electronics for mounting and docking, the tool will not fall off when power is lost, even while moving. This system is quite simple to expand, with the major obstacle being the size of the frame. Other tools, such as 3D scanners, can be added in the future.
