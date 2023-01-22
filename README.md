# Neverball package repository

Neverball is a 3D rolling-ball game that we all love. You can make custom levels for it.

This is a repository of downloadable Neverball level sets.

## Why are the compiled SOL files included?

Currently the package system uses MD5 checksums to detect package updates. Unfortunately `mapc`, the map compiler, does not generate deterministic output; in other words, the generated SOL files are not identical between different builds of mapc. So the MD5 checksums can change even without the levels having changed. SOL file inclusion is, at this point, a workaround for that.
