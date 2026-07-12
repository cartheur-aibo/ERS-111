# ERS-111 Boot Experiments

The first custom payload should be a minimal OPEN-R proof, not a full
personality image.

R-Code can also be part of the early ERS-11x path. This is a basic
scripting language for ERS-110 and ERS-111, and it is comparable to
BASIC on an older computer. That makes it a useful lower-risk starting
point before attempting deeper OPEN-R object work.

## Focused Plan

- confirm the exact ERS-11x media and duplicate-media strategy before any write tests
- preserve and inspect the original media so the stock layout is documented first
- identify whether the first safe software step should be R-Code, stock AIBOware, or a minimal OPEN-R payload
- prefer R-Code or other stock-compatible behavior tests before custom low-level deployment
- only move to OPEN-R payload experiments after the media layout and rollback path are understood

## Tasks

- confirm whether the Sony OPEN-R SDK or community toolchains support the 11x series
- confirm what R-Code materials or tools explicitly support ERS-110 and ERS-111
- stage a minimal `R-CODE.R` test from the local `r-code/` package before attempting deeper OPEN-R payload work
- define the smallest possible ERS-111 test payload and install layout
- stage experiments only onto separate test media
- test in increasing-risk order: media recognition, passive boot, minimal object load, then deeper runtime work

## Rule

Use separate test media, never the original working media.
