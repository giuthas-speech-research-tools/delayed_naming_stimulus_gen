# Stimulus List Generation

This Python package provides stimulus list generation for phonetics
experiments, delayed naming etc. This is not meant as a replacement of programs
like PsychoPy, but rather for easing work when experiments are run by, for
example, AAA (from Articulate Instruments) or RASL by (Steven Lulich of Indiana
University).

Current version generates stimulus lists for delayed naming in AAA. Future
versions will be more versatile.

## Overview

- Stimulus lists are generated from block specification files and shuffled
  while preventing across-block-boundary repeats by resampling.
- Optional beeps with a randomised (or rather shuffled) silent delay are
  generated into .wav files.
- Lists are written out for AAA (in DOS format) and will be written also for
  RASL.

## Roadmap to 1.0 - the current version

- [x] Convert stimulus list randomisation from R to Python.
- [x] Convert beep / delay generation from Matlab to Python.
- [x] Write exporter to AAA format.
- [x] Include a markdown license file and link to it when there is some actual
  code here.

## Roadmap to 2.0

- [ ] Main modernization:
  - [x] Start using branches in git
  - [ ] Come up with a better package name and check that it is available on PyPi
  - [ ] Move the code to source directory
  - [ ] Get a package management tool
    - [ ] Create environments for at least: stable version, development, testing
    - [ ] Proper python packaging for installation
    - [ ] Provide an entry point for installation
    - [ ] Upload on PyPi
  - [ ] Start using license headers
- [ ] Smaller details
  - [ ] Add option of using end_calibration as an input file
  - [ ] Write exporter to RASL format
  - [ ] Provide examples

Possibly also:

- [ ] testing, which might rely on the examples

## Copyright and License

Copyright (c) 2022-2024 Pertti Palo

[GPL 3.0](LICENSE)
