# Material icons for ExtJS

ExtJS package to use [Material Design Iconic Font](http://zavoloklom.github.io/material-design-iconic-font/index.html) in a ExtJS application or workspace by Richard Styles.

Current version of Material Design Icons: 2.2.0

## Adding package to workspace or app
Download [material-icon.pkg](https://github.com/RichardStyles/ExtJS-Material-Icons/releases/) from releases [1.0.0]

copy: .pkg file to workspace of your project

run: ```sencha package add material-icons.pkg```

add 'material-icons' to your app.json

```
   "requires": [
      "font-awesome",
      "material-icons"
   ],
```
run: ```sencha app refresh```

## Usage

Just like using font awesome you must use the css ```x-mi``` class before the material icon class you wish to use.

#### Important 
The class names have been updated from **zmdi** to **mi** when converting the css from the Material Design Iconic Font to scss for compiling with Sencha cmd.

```
zmdi zmdi-rss
```
Becomes

```
x-mi mi-rss
```
All classes should be prefixed using ```x-mi``` and the icon specific css class should begin with ```mi-``` instead of ```zmdi-```.

#### Example 

```
iconCls: "x-mi mi-rss"
```

## Licences
* All licences for Fonts and code from [Material Design Iconic Font by Sergey Kupletsky](http://zavoloklom.github.io/material-design-iconic-font/index.html).  remain valid. See [here for licence infomation](http://zavoloklom.github.io/material-design-iconic-font/license.html) for the fonts used in this package. 
* Code for ExtJS package release under MIT

## About
This package was created to allow additional fonts to be used, just like font-awesome.

ExtJS Package built by [Richard Styles](https://twitter.com/camerastyles).