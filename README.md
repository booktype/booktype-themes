# Themes for Booktype (print and digital)
This repository contains a number of themes for the publishing platform Booktype (www.booktype.pro).
The themes provide fonts, css styles and metainformation for PDF (using mpdf) and EPUB.

## Install themes ##

### Install themes on Booktype ###

Copy fonts to folders


### Configure mpdf ###

Two things need to happen: copy all fonts to the mpdf folder `ttfonts` and modify the file `config_fonts.php`.

To modify the file `config_fonts.php`, use the file in this repo:

`AA_fontconfig/theme_fonts_mpdf.php`

This file contains the list of all fonts used in this set of themes and needs to be added into the array beneath the line:
 
`$this->fontdata = array(`