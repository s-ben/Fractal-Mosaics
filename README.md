Fractal-Mosaics
===============

Fractal Mosaics is a rotation, scale, and translation invariant photomosaic algorithm (i.e., the images can be placed at arbitrary locations, can be scaled to any size, and can be rotated by any angle).

The figure below shows a Fractal Mosaic and traditional photomosaic made using the same target image and image set.

![Photomosaic New Algorithm Fractal Eye](https://raw.github.com/s-ben/Fractal-Mosaics/gh-pages/images/fractal_trad_compare.png?login=s-ben&token=174f9368670265a272b500a411d902da)

For a detailed description of the algorithm, see my adademic-style "[paper](http://s-ben.github.io/Fractal-Mosaics/)" on it and documentation below.

# Prerequisites

Fractal Mosaics is implemented in Matlab.  You’ll need a copy of Matlab with the Signal Processing toolbox - most versions should have the Signal Processing toolbox.


# Getting Started

1.  Download the demo example ([zip](https://github.com/s-ben/Fractal-Mosaics/raw/gh-pages/code/fractal_mosaics.zip), [tgz](https://github.com/s-ben/Fractal-Mosaics/raw/gh-pages/code/fractal_mosaics.tgz)).  
2.	Download the [example image set](https://docs.google.com/file/d/0B_2ApIVBvXm1RlFjTmVwUXRIcms/edit?usp=sharing) (9.1 GB database of greyscale images of graffiti).
3.	Unpack the zip file containing the example image set and copy its contents into the /library_images folder in the demo example.
4.	Navigate to the /m-files directory 
5.	Run ‘fractal_mosaic.m’ 

Your mosaic is now rendering.

WARNING:  it takes a long time to render a mosaic (~10.5 hrs on my macbook pro).  If you want to optimize it, please do ;)

The demo example creates a black and white mosaic.  This is because color takes ~3X as long.  To create a color mosaic, download the [color image set](https://docs.google.com/file/d/0B_2ApIVBv Xm1ckhjX3RibVVPdkk/edit?usp=sharing) (COMING SOON), and set Fractal Mosaics to color mode (see the [Variables](https://github.com/s-ben/Fractal-Mosaics/wiki/Variables) page for info on this).

# Documentation

* [Fractal Mosaic “paper”](http://s-ben.github.io/Fractal-Mosaics/):  academic-style paper explaining how the algorithm works
* [Wiki](https://github.com/s-ben/Fractal-Mosaics/wiki): details on how to create your own mosaic.
* [Gallery](http://www.flickr.com/photos/travelingseth/sets/72157623789223762/):  Flickr page showing finished mosaics

# Licencing

Fractal Mosaics is licensed under the GNU General Public License ([GPL](http://www.gnu.org/licenses/gpl.txt)).  Some functions used are from the Matlab File Exchange and use the [BSD license](http://opensource.org/licenses/bsd-license.php).  This license is "permissive" (can be used for any purpose, commercial or non). If you wish to use Fractal Mosaics for proprietary software, let's talk! (seth.benton@gmail.com)


[![githalytics.com alpha](https://cruel-carlota.pagodabox.com/80d211511c492cf9dce9dd9841acf603 "githalytics.com")](http://githalytics.com/s-ben/Fractal-Mosaics)
