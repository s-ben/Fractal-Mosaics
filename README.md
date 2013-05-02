Fractal-Mosaics
===============

Fractal Mosaics is a rotation, scale, and translation invariant photomosaic algorithm (i.e., the images can be placed at arbitrary locations, can be scaled to any size, and can be rotated by any angle).

The figure below shows a Fractal Mosaic and traditional photomosaic made using the same target image and image set.

![Photomosaic New Algorithm Fractal Eye](https://raw.github.com/s-ben/Fractal-Mosaics/gh-pages/images/fractal_trad_compare.png?login=s-ben&token=174f9368670265a272b500a411d902da)

For a detailed description of the algorithm, see my "[paper](http://s-ben.github.io/Fractal-Mosaics/)" on it and documentation links below.

# Prerequisites

Fractal Mosaics is implemented in Matlab.  You’ll need a copy of Matlab with the Signal Processing toolbox installed (any version should work, most should come with the Signal Processing toolbox).


# Getting Started

1.  Download the [demo example](https://github.com/s-ben/Fractal-Mosaics/blob/gh-pages/code/FractalMosaics_package.zip).  This has all the code you need.  Simply modify the example to create your own mosaics.
2.	Download the [example image set](https://docs.google.com/file/d/0B_2ApIVBvXm1RlFjTmVwUXRIcms/edit?usp=sharing) (706 MB database of images of San Francisco).
3.	Unpack zip file with images into the /library_images folder in the demo example.
4.	Navigate to the /m-files directory 
5.	Run ‘fractal_mosaic.m’ 

Your mosaic is now rendering.

WARNING:  it takes a long time to render a mosaic (~6 to 8 hrs on my macbook pro).  If you want to optimize it, please do ;)

The demo example creates a black and white mosaic.  This is because color takes ~3X as long.  To create a color mosaic, download the [color image set](https://docs.google.com/file/d/0B_2ApIVBvXm1ckhjX3RibVVPdkk/edit?usp=sharing), and set Fractal Mosaics to color mode (see the Variables page for info on this).

# Documentation

* [Fractal Mosaic “paper”](http://s-ben.github.io/Fractal-Mosaics/):  academic-style paper explaining how the algorithm works
* [Wiki](https://github.com/s-ben/Fractal-Mosaics/wiki): includes pages with step-by-step instructions on how to create your own mosaic and description of variables used to tweak mosaic output.
* [Gallery](http://www.flickr.com/photos/travelingseth/sets/72157623789223762/):  Flickr page containing finished mosaics

# Licencing

Fractal Mosaics is licensed under the GNU General Public License ([GPL](http://www.gnu.org/licenses/gpl.txt)).  If you wish to use Fractal Mosaics for proprietary software, let's talk! (seth.benton@gmail.com)


[![githalytics.com alpha](https://cruel-carlota.pagodabox.com/80d211511c492cf9dce9dd9841acf603 "githalytics.com")](http://githalytics.com/s-ben/Fractal-Mosaics)
