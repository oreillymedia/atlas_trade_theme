# Atlas Trade Theme

This repository collects the CSS styles for the "Trade" theme in the O'Reilly Atlas authoring system. This theme defines styles for all common book elements, for all output formats: PDF (print), EPUB (iPad, Nook, etc.), and MOBI (Kindle). Note that design changes will not be accepted for this theme. If you'd like to customize the design, consider building your own template, or adding oneoff customizations directly to your project.

## How Do the Styles Differ Between Formats?

We tried our best to maintain a similar look and feel between all formats. However, there are certain layout or design elements that simply do not translate across formats. Here's a list of the differences:

* Removed references to custom font faces in ebook files
* Removed strings and auto-generated text in ebook files
* Centered titlepage information in ebook files
* Lightened box and border color to gray in ebook files

This theme does not use any custom fonts within the EPUB or MOBI files. Instead, it relies on the system serif and sans-serif fonts installed on the device used to read the file. Device makers put much effort into optimizing their devices for the fonts they've installed, and so we choose to trust their system defaults rather than risk poor display by relying on custom embedded fonts.