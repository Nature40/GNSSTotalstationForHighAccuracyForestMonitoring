# Survey
geomax-guide: Documentation on DGPS and Total Station
Access to the webpage: [nature40.github.io/GPS-Documentation](https://nature40.github.io/GPS-Documentation)

## Docsy jekyll template crash course

This webpage uses the docsy template by 
[vsoch](https://github.com/vsoch). You can find a demo site and a very good explanation of the features [here](https://vsoch.github.io/docsy-jekyll/).

### Documents and Pages

Put your Tutorial markdown in the `\_docs` folder and a link will 
automatically appear in the "Documentation" subpage. Every documents 
need a yml header like the following:

```
title: Testpage  
layout: page  
permalink: /testperma/  
```

The permalink is used in other files to refer to this page (like in the 
table of contents).  
Markdowns in the `pages` folder work the same way but do not appear in 
the `Documentation` page and theresfore must be linked manually.

### Header and Sidebars

There are two files in the `navigation` folder. The `toc.yml` is the 
table of content on the left side. The `navigation.yml` are the links 
in the top panel. To include a page add its permalink 
with a name you want like this:

```
- title: Page to Test
  url: testperma
```

You can also add external links:

```
- title: Natur 4.0
  external_url: https://www.uni-marburg.de/de/fb19/natur40
```

The panel on the right generates automatically from the headings in the 
markdown. 



### Images

Images are stored under `assets/img`. To include a image in the 
markdown you need to add two dots to the filepath to start the path at the root 
of the repository `![image](../assets/img/image.png)`.




## To-Do List 

* [DGPS Rover](_docs/DGPS_Rover.md)
* DGPS Rover and Base
* [Total Station Set Up](_docs/Totalstation_Setup.md)
* Total Station and Rover (DGPS) Measurements
* Tree and Terrain Measurement Concepts
* Total Station Terrain
* Total Station Reflector Trees
* [Total Station Reflectorless Trees](_docs/Totalstation_and_Rover_Survey.md)

A complete manual can be found [here](https://www.i3map.fr/fr/index.php?controller=attachment&id_attachment=31).
