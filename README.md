# LaTex based CV
![CI](https://github.com/inglor/cv/workflows/CI/badge.svg)

## Description
LaTex based CV using [ModernCV](https://github.com/xdanaux/moderncv). The compilation is handled from [tectonic](https://tectonic-typesetting.github.io/en-US/)

## Dependencies:
- Font-Awesome v4.x : `moderncv` version 2.0.1 still use FontAwesome version 4. In Archlinux this is [otf-font-awesome-4](https://aur.archlinux.org/packages/otf-font-awesome-4/) 
- tectonic

## Build
`tectonic cv.tex`

## GitHub workflow
* Automatically build the `pdf` on each commit on `master` or PR against master
* Automatically create a new release when merged to `master` and upload the `pdf` artifact
