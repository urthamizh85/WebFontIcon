# CNSIcons


The premium icon font for [CNSI](http://www.cns-inc.com/). Designed by [@thiruk2014](https://twitter.com/thiruk2014).

Note: All brand icons are trademarks of their respective owners. The use of these trademarks does not indicate endorsement of the trademark holder by CNSI, nor vice versa.

Visit [CNSI](http://www.cns-inc.com/) and  check out the search feature, which has keywords identifying common icon names and styles. For example, if you search for “arrow” we call up every icon that could possibly be used as an arrow. We’ve also included each icon’s class name for easy copy/pasting when you’re developing!

We intend for this icon pack to be used with [Ionic](http://www.cns-inc.com/), but it’s by no means limited to it. Use them wherever you see fit, personal or commercial. They are free to use and licensed under [MIT](http://opensource.org/licenses/MIT).


## Getting Started

 1. Download and extract the font pack
 2. Copy the `cnsicons.css` to your project
 3. Copy the `fonts` folder to your project
 4. Ensure the font urls within `cnsicons.css` properly reference the `fonts` path within your project.
 5. Include a reference to the `cnsicons.css` file from every webpage you need to use it.

Or install with [component](https://github.com/component/component):

    $ component install urthamizh85/cnsicons
    
Or perhaps you're known to use [bower](http://bower.io/)?
   
    $ bower install cnsicons


## HTML Example

You can use [CNSI](http://www.cns-inc.com/) to easily find the icon you want to use. Once you've copied the desired icon's CSS classname, simply add the `icon` and icon's classname, such as `cnsi-home` to an HTML element.

    <i class="wf cnsi-home"></i>


## Build Instructions

This repo already comes with all the files built and ready to go, but can also build the fonts from the source. Requires Python, FontForge and Sass:

1) Install FontForge, which is the program that creates the font files from the SVG files:

    $ brew install fontforge ttfautohint

2) Install [Sass](http://sass-lang.com/)

    $ gem install sass

3) Add or subtract files from the `src/` folder you'd like to be apart of the font files.

4) Modify any settings in the `builder/manifest.json` file. You can change the name of the font-family and CSS classname prefix.

5) Run the build command:

    python ./builder/generate.py


## License

CNSIcons is licensed under the [MIT license](http://opensource.org/licenses/MIT).
