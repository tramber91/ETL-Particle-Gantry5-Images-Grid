# WARNING in test phase

![Image](https://www.demo-gantry5.en-toutes-lettres.fr/images/demo/etl_particles_image_grid.jpg)

# Images grid particle for [Gantry] 5 Framework. 

The [En Toutes Lettres](https://www.en-toutes-lettres.fr/) Image Grid particle gives you the ability to quickly set up a clean, organized grid of images. A lot of options are available including usage of RokBox or Lightcase.

Go to [Gantry 5 demo website](https://www.demo-gantry5.en-toutes-lettres.fr/en/particles-en/grille-images-en) to see particle functionnality !


### WARNING : Installation package only for template Gantry 5 Hydrogen ([RocketTheme]) and CMS Joomla!. For other Gantry 5 template, unzip file and manage a manual installation

#### Manual Installation (General) - Joomla!
- UNZIP the file on your computer.
- You will find some directories (particles, scss, js, images)
- Copy the directories (including files) to ```root/templates/TEMPLATE_DIR/custom/``` via your FTP client (like FileZilla)

Afer installation, don't forget to add these 2 lines
```scss
@import 'dependencies';
@import 'etl_images_grid';
```
in your custom CSS file, **custom.scss** (/templates/g5_hydrogen/custom/scss/**custom.scss**)

or create this file and add these 2 lines with your text editor (/templates/g5_hydrogen/custom/scss/custom.scss)


# Changelog
All notable changes to this project.


## [2.0] - 2017-11-01

### Added
- Choice of "RokBox" or "Lightcase" popup system"
- Adding a new style, Style 4 opacity
- Options, choice of padding (space between each image)
- Options, choice of image Border Radius
- Images, Title and Subtitle
- Images, choice between opening in Popup or to a link

### Improved
- Class CSS responsive
- Class ```imagegrid-firstlarge``` and ```imagegrid-lastlarge```


## [1.1] - 2016-11-31

### Added
- Add CSS class to the title.


## [1.0] - 2015-11-31

- Initial release.



[RocketTheme]: https://rockettheme.com/
[Gantry]: http://gantry.org/
[Demo]: https://github.com/
