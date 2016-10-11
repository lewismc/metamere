# Metameres
A Python toolkit providing utility ortibal mechanics functions and calculations relevant to remote sensing.

## Introduction
The metameres toolkit is an effort to develop something useful to help myself and others engaged in the study of 
the Physics of Remote Sensing as taught by [Dr. Jakob van Zyl](http://www.jpl.nasa.gov/about/bio_zyl.php) 
in his [EE/Ae 157 Introduction to the Physics of Remote Sensing course](http://www.its.caltech.edu/~ee157/) 
at the California Institute of Technology in Pasadena, CA, U.S.A. I had the pleasure of taking this class throughout
2016 and into 2017.

The EE/Ae 157 syllabus provides an overview of the physics behind space remote sensing instruments. 
Topics include the interaction of electromagnetic waves with natural surfaces, including scattering of microwaves, 
microwave and thermal emission from atmospheres and surfaces, and spectral reflection from natural surfaces and 
atmospheres in the near-infrared and visible regions of the spectrum. 

The class also discusses the design of modern space sensors and associated technology, including sensor design, 
new observation techniques, ongoing developments, and data analysis and interpretation. Examples of applications 
and instrumentation cover geology, planetology, oceanography, astronomy, and atmospheric research.

Metameres will provide a Python API for programmatic executution of all calculations as covered within EE/Ae 157.

## Installation
Make sure you have Python installed and run from the Cheeseshop
```
$ pip install metameres
```
alternatively you can install from source
```
$ git clone https://github.com/lewismc/metameres.git
$ cd metameres && python setup.py install
```

## License
Metameres is permissively licensed under the [Apache License v2.0](http://www.apache.org/licenses/LICENSE-2.0).
A copy of that licsense also ships with this software.

## What does Metameres mean?
It doesn't one in persuit of an education within Remote Sensing long before they stumble across the name [James Clark Maxwell](https://en.wikipedia.org/wiki/James_Clerk_Maxwell). Maxwell (13 June 1831 – 5 November 1879) was a Scottish scientist in the field of mathematical physics. His most notable achievement was to formulate the classical theory of electromagnetic radiation, bringing together for the first time electricity, magnetism, and light as manifestations of the same phenomenon. Maxwell's equations for electromagnetism have been called the "second great unification in physics" after the first one realised by Isaac Newton.

As most physicists of the time, Maxwell had a strong interest in psychology. He was particularly interested, following the steps of Isaac Newton and Thomas Young, in the study of colour vision. From 1855 to 1872, he published at intervals a series of investigations concerning the perception of colour, colour-blindness, and colour theory, and was awarded the Rumford Medal for On the Theory of Colour Vision.

Isaac Newton had demonstrated, using prisms, that white lights, such as sunlight, are composed of a number of monochromatic components which could then be recombined into white light.[102] Newton also showed that an orange paint made of yellow and red could look exactly like a monochromatic orange light, although being composed of two monochromatic yellow and red lights. Hence the paradox that puzzled physicists of the time: two complex lights (composed of more than one monochromatic light) could look alike but be physically different, called metameres. Thomas Young later proposed that this paradox could be explained by colours being perceived through a limited number of channels in the eyes, which he proposed to be threefold, the trichromatic color theory. Maxwell used the recently developed Linear algebra to prove Young's theory. Any monochromatic light stimulating three receptors should be able to be equally stimulated by a set of three different monochromatic lights (in fact, by any set of three different lights). He demonstrated that to be the case, inventing color matching experiments and Colorimetry.

<img src="https://en.wikipedia.org/wiki/James_Clerk_Maxwell#/media/File:Tartan_Ribbon.jpg" width="300" />

The image above shows the first durable colour photographic image, demonstrated by James Clerk Maxwell in an 1861 lecture. The image is of a Scottish bow clearly dipicting the beautiful colours present within the tartan pattern. 
