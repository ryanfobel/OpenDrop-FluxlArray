## OpenDrop-FluxlArray

DMF chip compatible with the [WheelerLab fork of OpenDrop](https://github.com/ryanfobel/OpenDrop)

### Don't click on the files!

Click on the "Download ZIP" Button to the right.
Then unpack the archive.

### Open Source Digital Microfluidics Bio Lab

[OpenDrop] is a new design for an open source digital microfludics platform for research purposes. The device uses recent electro-wetting technology to control small droplets of liquids. Potential applications are lab on a chip devices for automating processes of digital biology. How ever the present design should also open the technology to other field and allow experimentation to find new applications. Including the field of art, music, games and education.

Note that this version has been forked from [v2.1](https://github.com/GaudiLabs/OpenDrop/commit/5bb955d). This repository contains the passive DMF chip (which is now detachable using a slot-connector). The high-voltage driving electronics (i.e., the microcontroller, high-voltage boost converter, and switches) are contained in a [separate repository](https://github.com/ryanfobel/OpenDrop)). This version also provides software control of the driving voltage using a digital potentiometer (controlled via i2c) and adds the capability to insert high-pass filters on each of the output channels to support bipolar AC actuation.

### License

[OpenDrop], all design files and software are licensed under a GNU GENERAL PUBLIC LICENSE
See license file in the repository.

### Contributions ###

Original design by Urs Gaudenz ([GaudiLabs](http://www.gaudi.ch)) with modifications by [Ryan Fobel](https://github.com/ryanfobel) ([Wheeler Microfluidics Lab](http://microfluidics.utoronto.ca)).

[OpenDrop]: http://www.gaudi.ch/OpenDrop/


