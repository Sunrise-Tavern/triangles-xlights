xLights vehicle reference meshes
================================

Files:
  - usps_international_24ft_box_truck_cm.obj
  - m939_style_5ton_6x6_cm.obj
  - vehicle_materials.mtl

Coordinate convention:
  X = vehicle length
  Y = vehicle width
  Z = height
  Origin = center of overall vehicle footprint at ground level

Nominal dimensions:
  USPS International 24-foot box truck:
    1040 cm long x 256 cm wide x 370 cm high (mesh envelope, including bumpers)
    Cargo box length approximately 732 cm

  M939-style 5-ton 6x6:
    820 cm long x 264 cm wide x 290 cm high (mesh envelope, including bumpers and tires)

xLights notes:
  1. Keep each OBJ file and vehicle_materials.mtl in the same folder.
  2. Import the OBJ as a static 3D mesh/object.
  3. Use uniform scale on X, Y, and Z.
  4. These are intentionally simple reference models, not engineering-accurate vehicle models.
  5. If xLights imports the OBJ at an unexpected size, apply one uniform scale factor.
