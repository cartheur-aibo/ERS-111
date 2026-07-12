# ERS-111 Media Forensics

The first deliverable is a preserved image and boot-layout inventory.

## Tasks

- preserve the original media with a byte-for-byte image
- record filesystem, partition, and top-level directory layout
- inventory any `OPEN-R` tree, `OBJECT.CFG`, and `*.BIN` payloads
- compare the preserved layout against later ERS-7-era media from `openr-debian`

## Notes

- work from a read-only image whenever possible
- keep the original media out of the experiment loop after preservation

