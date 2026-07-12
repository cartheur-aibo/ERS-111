# ERS-110/111 R-Code

The local `r-code/` folder appears to be a Sony `R-CODE110/111`
package for `ERS-110/111`.

R-Code is a simplified scripting language for programming AIBO, and the
programmer manual describes it as a language similar to BASIC. For this
project, that makes R-Code the most practical low-risk software path to
try before deeper OPEN-R experiments.

## Why It Helps

- it is explicitly targeted at `ERS-110/111`
- it includes a runnable `Memory Stick` execution image under `r-code/MSImage`
- it includes manuals, references, and sample `.R` scripts
- it gives a simpler programming route than full native OPEN-R object development

## What The Package Contains

- `r-code/Document/readme.txt`
- `r-code/Document/Programmers.txt`
- `r-code/Document/Reference.txt`
- `r-code/Document/LED_Light_List.txt`
- `r-code/Document/Sound_List.txt`
- `r-code/Document/Tone_List.txt`
- `r-code/MSImage/OPEN-R`
- `r-code/sample`

## Operational Notes

- the package says it is only for `AIBO ERS-110/111`
- it says to use an `AIBO Programming Memory Stick`
- it says `8MB` or `16MB` sticks are usable
- it says `16MB or greater` is not usable due to hardware limits
- it expects a script named `R-CODE.R` to be placed in `\OPEN-R\`

## Suggested First Use

- preserve and inspect the original media first
- stage a separate R-Code test stick from `r-code/MSImage`
- start with a minimal sample such as sound or pose playback
- only move to more complex motion or OPEN-R work after the boot path is confirmed

## Limits

- this does not replace a full OPEN-R SDK for arbitrary native object work
- this does not by itself prove every media or adapter detail for the exact robot on hand
- this should still be treated as test media only, not a reason to alter original working media
