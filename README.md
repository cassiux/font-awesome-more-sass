# Font Awesome More 3.0.2 + SASS

These files was built to help those which want to use [Font Awesome More](http://gregoryloucas.github.com/Font-Awesome-More)
and have all CSS running with **SASS**.

## Setup

Each **SASS** file have a variable to define the fonts path for, you just need be careful with the correct
font path inside each file.

- Default Icons - `$fontAwesomePath`
- Social Icons`$fontAwesomeSocialPath`
- Coprorate Icons`$fontAwesomeCorpPath`
- Extra Icons`$fontAwesomeExtPath`

##Issue

You might run in a problem if you use Font Awesome with CDN based website.

There is a issue with FireFox when you use Font Awesome and cross domains, so before you
get crazy searching for a valid solution here is a tip:

Add a `.htaccess`file or directly to apache config with the following content:

    <FilesMatch "\.(ttf|otf|eot|woff)$">
    <IfModule mod_headers.c>
    Header set Access-Control-Allow-Origin "*"
    </IfModule>
    </FilesMatch>

##License
- The Font Awesome font is licensed under the SIL Open Font License - http://scripts.sil.org/OFL
- Font Awesome CSS, LESS, and SASS files are licensed under the MIT License - http://opensource.org/licenses/mit-license.html
- The Font Awesome pictograms are licensed under the CC BY 3.0 License - http://creativecommons.org/licenses/by/3.0/
- Attribution is no longer required in Font Awesome 3.0, but much appreciated: "Font Awesome by Dave Gandy - http://fortawesome.github.com/Font-Awesome"

## More information

You can find the full suite of pictographic icons, examples, and documentation at:
http://fortawesome.github.com/Font-Awesome/

For more information about Font Awesome More please [click here.](http://gregoryloucas.github.com/Font-Awesome-More)
