# LaTex based CV
[![Build Status](https://travis-ci.com/inglor/cv.svg?branch=master)](https://travis-ci.com/inglor/cv)

## Description
LaTex based CV using [ModernCV](https://github.com/xdanaux/moderncv) as a submodule. The compilation of Tex is based on TeX Live distribution.

## Build instructions

Clone project
```
git clone https://github.com/inglor/cv.git
```
Initialize the submodule
```
git submodule update --init --recursive
```
Compile Tex and build PDF
```
make all
```
### Dependencies

Check `.travis.yml` for TeX Live packages required.

