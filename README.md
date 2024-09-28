3D Printing Instructions

Material:
- PETG recommended
- PLA acceptable

Printer setup:
- 0.4mm nozzle, 0.2mm layers, smooth PEI bed

Caster roller:
- print upright
- set "Seam position" to Random
  - Prusa Slicer -> Print Settings -> Layers and perimeters -> Advanced -> Seam position
- enable brim
  - my PETG prints without brim on smooth PEI

Wheels:
- set "Seam position" to Random
  - Prusa Slicer -> Print Settings -> Layers and perimeters -> Advanced -> Seam position
- enable "External perimeters first"
  - Prusa Slicer -> Print Settings -> Layers and perimeters -> Advanced -> External perimeters first
- clean the tire groove from any leftover filament
- put on the tire ring and press the tire into the tire groove

Enclosure bottom:
- enable "Supports on build plate only"
  - my PETG prints without supports
- set "Overhang threshold" to 30 degrees
  - Prusa Slicer -> Print Settings -> Support material -> Support material -> Overhang threshold
- make sure the seam position is in the back of the part
  - turn the part if necessary

Enclosure top:
- if your print has too many "loose filament" defects on the inside
  - reduce perimeter print speed
  - decrease part fan speed (both PLA and PETG) to make filament stick better
  - enable "Supports on build plate only"
- make sure the seam position is in the back of the part
  - turn the part if necessary

LiDAR Posts
- enable brim
  - my PETG prints without brim on smooth PEI

Motor clamps
- print upside down

For all parts:
- optional, set "Combine infill every" to 2 layers
  - Prusa Slicer -> Print Settings -> Infill -> Reducing print time -> Combine infill every

