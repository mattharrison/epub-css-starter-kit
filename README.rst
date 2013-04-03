Epub CSS Starter Kit
========================

Creating epubs that work in multiple readers can be painful, like debugging web problems back 
in the glory days of ie6. Only this time there is no firebug.

Here's a css file to help alleviate the pain.

If you find that it doesn't work on a particular reader, please file an issue containing the 
following items:

* Reader platform and version
* Sample html
* Sample css
* Expected result

Some issues are ereader bugs. Some are css bugs. Ideally the css will look "good enough" on 
most devices. You can then take the css and tweak it for devices you want to focus on.

Focus
======

What platform is the focus of this effort? Oddly enough, the .mobi format for Kindle, is the least 
common denominator that we want to get working. Given that it has 70% of the market, it makes sense 
to put the effort there. Every effort has been made so that epubs using this css will generate clean
mobi's with kindlegen.

The other platforms of significance are nook and ibooks, in that order. Any other platform is icing 
on the cake. Support for other platforms will be given provided they don't break the top 3 platforms.
Otherwise it is suggested that these one off platforms be given custom css on top of the starter kit.


Examples
==============

* `rst2epub <https://github.com/mattharrison/rst2epub2>`_ uses this (there is a sample book to build there)
* `Ebook Formatting: KF8, Mobi & EPUB <http://www.amazon.com/Ebook-Formatting-Mobi-EPUB-ebook/dp/B00BWQXHU6/ref=sr_1_2?ie=UTF8&qid=1365027107&sr=8-2>`_ illustrates the CSS here and other intricacies of creating epubs/mobis


TODO
=====

How you can help

* Matrix of supported HTML http://wiki.mobileread.com/wiki/Device_Compatibility
* Matrix of supported eReaders
* Try out the css or sample book and file bugs/patches

Resources
==========
* Demo epub at http://manual.calibre-ebook.com/conversion.html#epub-advanced-formatting-demo
* http://www.paulsalvette.com/2011/08/epub-and-kindlegen-tutorial-ebook.html
* http://wiki.mobileread.com/wiki/CSS_template
* http://gbenthien.net/Kindle/index.html

License
==========

MIT License
