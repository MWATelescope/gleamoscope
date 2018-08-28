Introduction
============

GLEAMoscope shows the radio sky as observed by the Murchison Widefield Array (MWA) for the GaLactic and Extragalactic All-sky MWA (GLEAM) survey. The Milky Way is visible as a band across the sky and the dots beyond are some of the 300,000 visible radio galaxies. Red indicates the lowest frequencies (72--103 MHz), green the middle frequencies (103--134 MHz) and blue the highest frequencies (139--170 MHz). Find out more on the [GLEAM homepage](http://mwatelescope.org/science/gleam-survey).

GLEAMoscope was largely adapted from [Chromoscope](http://www.chromoscope.net/), an easy tool that anyone can use to explore and understand the sky at multiple wavelengths. It was originally written for the [Planck/Herschel Royal Society Summer Exhibition 2009](http://royalsociety.org/From-the-oldest-light-to-the-youngest-stars-the-Herschel-and-Planck-Missions/). Developed as an educational resource. This Javascript web-application will run locally or can be run on a web server. The only part that requires an internet connection is the search tool which makes use of [LookUP](http://www.strudel.org.uk/lookUP/).
 
View the Universe
-----------------

GLEAMoscope uses six of Chromoscope's eight public-domain datasets from a number of all-sky astronomy projects. It lets you easily move around the sky and fade between wavelengths using a simple user-interface to illustrate the similarities and differences between what is visible at each wavelength.

Surveys include:

* Gamma ray ([Fermi](http://fermi.gsfc.nasa.gov/)),
* X-ray ([ROSAT](http://www.mpe.mpg.de/xray/wave/rosat/mission/rosat/index.php)),
* Optical ([DSS](http://stdatu.stsci.edu/dss/)/[Wikisky](http://www.wikisky.org/)), 
* Far Infrared ([IRAS](http://irsa.ipac.caltech.edu/IRASdocs/iras.html)),
* Microwave ([Planck](http://www.esa.int/planck)), 
* Radio ([GLEAM](http://mwatelescope.org/science/gleam-survey)).

You can [download these tile-sets for offline use](http://blog.chromoscope.net/download/).

Control the sky
---------------

To move the map around, simply 'grab' it with the cursor and drag around the screen. You can double-click (or use the plus and minus keys on your keyboard or a scroll wheel) to zoom in and out. A simple slider (or a set of keyboard shortcuts) allows you to fade gradually along the spectrum and to see structures and features change as they go. A set of labels can be toggled on and off (with the 'L' key) to guide people around the sky and, if an Internet connection is present, users can search for named objects and jump right to them.

No installation needed
----------------------

A standard, modern, web browser is all that you need to use GLEAMoscope so there is no need to install any extra software, plugins or learn a new interface (you will have to [download the tiles to use it offline](http://blog.chromoscope.net/download/)). Being platform independent means that whether you use Windows, Mac or Linux, it should still be accessible.

Note that the Chrome browser has extra security when running locally which will stop Chromoscope seeing KML and the language JS files even if they are in the same directory. If you want to use these features you should start Chrome with the option "--allow-file-access-from-files".

Other adaptations
--------

Thanks to Chromoscope's status as an open-source project, and the [documentation for Developers](http://chromoscope.net/dev/reference.html), there are other adaptations of Chromoscope elsewhere:
* The [Online Showcase of Herschel Images](http://oshi.esa.int/)
* [UK Herschel Outreach Website](http://herschel.cf.ac.uk/chromoscope/results)
* The [H2O southern Galactic Plane Survey](http://www.ast.leeds.ac.uk/hops/public/index.php)
* [Planckoscope](http://planck.cf.ac.uk/planckoscope)

Credits
-------

The GLEAM images were created by Natasha Hurley-Walker (Curtin University / ICRAR) and the GLEAM team, and the adaptation from Chromoscope was performed by Natasha. Chromoscope was created by Stuart Lowe, Chris North (Cardiff University) and Robert Simpson (Oxford University). [Translations](http://chromoscope.net/dev/translate.html) are provided by a variety of people; credits are in the translation files.
