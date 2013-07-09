Fractal-Mosaics
===============

Fractal Mosaics is a rotation, scale, and translation invariant photomosaic algorithm (i.e., the images can be placed at arbitrary locations, can be scaled to any size, and can be rotated by any angle).

The figure below shows a Fractal Mosaic and traditional photomosaic made using the same target image and image set.

![Photomosaic New Algorithm Fractal Eye](https://raw.github.com/s-ben/Fractal-Mosaics/gh-pages/images/fractal_trad_compare.png?login=s-ben&token=174f9368670265a272b500a411d902da)

For a detailed description of the algorithm, see my adademic-style "[paper](http://s-ben.github.io/Fractal-Mosaics/)" on it and documentation below.

# Prerequisites

Fractal Mosaics is implemented in Matlab.  You’ll need a copy of Matlab with the Signal Processing toolbox - most versions should have the Signal Processing toolbox.


# Getting Started

1.  Clone the Fractal-Mosaics repository (or, if you don't have git, just download the [zip file](https://github.com/s-ben/Fractal-Mosaics/archive/gh-pages.zip)).
2.  Navigate to the /code folder and unpack the 'FractalMosaics_package' zip or tar.gz file.  This contains the demo example.
3.	Download the [example image set](https://docs.google.com/file/d/0B_2ApIVBvXm1Y0VMVTVqNUhCaVk/edit?usp=sharing) (9.1 GB database of greyscale images of graffiti).
4.	Unpack the zip file containing the example image set and copy its contents into the /library_images folder in the demo example.
5.	Navigate to the /m-files directory in the demo example. 
6.	Run ‘fractal_mosaic.m’. 

Your mosaic is now rendering.

WARNING:  it takes a long time to render a mosaic (~10.5 hrs on my macbook pro).  If you want to optimize it, please do ;)

The demo example creates a black and white mosaic.  This is because color takes ~3X as long.  To create a color mosaic, download the color image set and set Fractal Mosaics to color mode (see the [Variables](https://github.com/s-ben/Fractal-Mosaics/wiki/Variables) page for how to do this).  Due to file size limits in Google Drive, the color image set is divided into two zip files ([image set 1](https://docs.google.com/file/d/0B3M2Bu_2k-QSSnhSVzNWRERtenc/edit?usp=sharing), [image set 2](https://docs.google.com/file/d/0B3M2Bu_2k-QSTkxxbEVGay1Gcjg/edit?usp=sharing)).

# Documentation

* [Fractal Mosaic “paper”](http://s-ben.github.io/Fractal-Mosaics/):  academic-style paper explaining how the algorithm works.
* [Wiki](https://github.com/s-ben/Fractal-Mosaics/wiki): details on how to create your own mosaic.
* [Gallery](http://www.flickr.com/photos/travelingseth/sets/72157623789223762/):  Flickr page showing finished mosaics.

# Licencing

Fractal Mosaics is licensed under the GNU General Public License ([GPL](http://www.gnu.org/licenses/gpl.txt)).  Some functions used in Fractal Mosaics are from the Matlab File Exchange and use the [BSD license](http://opensource.org/licenses/bsd-license.php).  This license is "permissive" (can be used for any purpose, commercial or non). If you wish to use Fractal Mosaics for proprietary software, let's talk! (seth.benton@gmail.com)


[![githalytics.com alpha](https://cruel-carlota.pagodabox.com/80d211511c492cf9dce9dd9841acf603 "githalytics.com")](http://githalytics.com/s-ben/Fractal-Mosaics)
