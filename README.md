bfawk
=====

brainfuck interpreter written in gawk

most of the code is basically portable (or trivially converted to portable
code) but gawk simplifies things

optimizations
---

- setting a value `[-]+++`
- simple dead code elimination `+-` `<>` `++++[-]` `[-][...]`
- scan loops `[<]`
- run length encoding

license
---

whatever i don't even care
