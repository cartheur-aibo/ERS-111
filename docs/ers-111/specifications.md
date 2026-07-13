# ERS-111 Technical Specifications

This table consolidates the ERS-111 hardware details shown in the
included Sony documentation set. The bundled ERS-111 owner's manual
explicitly notes that some illustrations use ERS-110 photos, but the
specification values below match the ERS-111 platform described there.

| Category | Detail | Location / Notes |
| --- | --- | --- |
| CPU | 64-bit RISC processor | Platform spec |
| Main memory | 16 MB | Platform spec |
| Program memory | 8 MB Memory Stick (`ERA-111M`) | Accessory media |
| Moving parts | Mouth: 1 degree of freedom | Total: 18 |
| Moving parts | Head: 3 degrees of freedom | Total: 18 |
| Moving parts | Legs: 3 degrees of freedom x 4 | Total: 18 |
| Moving parts | Tail: 2 degrees of freedom | Total: 18 |
| Internal sensor | Video input: 180,000 pixel color CCD camera x1 | Head |
| Internal sensor | Audio input: stereo microphone | Head |
| Internal sensor | Audio output: speaker x1 | Head |
| Internal sensor | Heat detector: heat sensor x2 | Torso |
| Internal sensor | Range finder: infra-red range finding sensor x1 | Head |
| Internal sensor | Acceleration detector: spatial acceleration sensor x1 | Legs |
| Internal sensor | Rotation detector: angular velocity sensor x1 | Legs |
| Internal sensor | Contact detectors: touch sensor x1, switch x4 | Head, legs |
| Power source | DC 7.2 V lithium ion battery (`ERA-110B`) | Battery pack |
| Energy consumption | 12.6 W | Autonomous mode reference |
| Operating time | Approx. 1.5 hours | Fully charged battery, autonomous mode |
| Dimensions | Approx. 274 x 156 x 266 mm | Not including tail |
| Weight | About 1.4 kg | Body only |
| Weight | About 1.6 kg | Including Memory Stick and battery |

## Supplemental Details

- Software architecture: OPEN-R modular software design running on
  Sony's Aperios real-time operating system.
- Autonomy and control modes: autonomous behavior plus `game` and
  `performance` modes via the Sound Commander remote.
- Included package context from the launch material: station, AC
  adapter, two `ERA-110B` Li-ion batteries, Sound Commander remote,
  8 MB pre-recorded Memory Stick, colored ball, and accessories.
- Initial launch context from the referenced ERS-110 page: announced
  for Japan and the United States on June 1, 1999, with limited-run
  online sales and an optional `ERF-510` AIBO Performer Kit.

## Sensor Behavior Notes

- Touch sensor: recognizes petting or impact-style tactile input.
- Color CCD camera: detects object color and shape during approach and
  avoidance behavior.
- Range finder: estimates object distance.
- Stereo microphone: detects sound direction and receives Sound
  Commander tones.
- Speaker: outputs AIBO sounds.
- Acceleration sensor: supports balance maintenance and recovery.
- Angular velocity sensor: detects rotary motion.

## Source Notes

- `docs/ers111_manual.pdf` confirms the ERS-111 model, 8 MB Memory
  Stick accessory, 18 total degrees of freedom, built-in camera,
  stereo microphone, speaker, thermometric sensor, infrared distance
  sensor, 3-axis acceleration sensing, `ERA-110B` battery pack,
  approximate 1.5 hour battery life, 156 x 266 x 274 mm dimensions,
  and approximately 1.6 kg mass.
- The Aibo Repairs ERS-110 page mirrors the same Sony-style technical
  specification table and adds launch-package details, software stack
  notes, and short descriptions of what the onboard sensors do:
  <https://aibo-repairs.com/aibo-info/aibo-models/item/11-the-sony-aibo-ers-110>
- The CPU, main memory, and detailed sensor breakout are captured here
  to match the supplied Sony-style technical spec table for the
  ERS-111.
