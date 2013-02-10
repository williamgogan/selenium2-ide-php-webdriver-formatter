selenium2-ide-php-webdriver-formatter
=====================================

A Selenium2 IDE PHP WebDriver Formatter, which drives Element34's php-webdriver code.

This is very rudimentary, but it does work, and generates PHP Webdriver Backed code.

To use, download the JS file, and in the Selenium IDE click Options->Options. Go into Formats, click "Add". Name it whatever you want, and paste in the contents of the JS file.


Other Requirements..
====================

You should be using the excellent https://github.com/Element-34/php-webdriver code, as this is what will be generated.


Limitations
===================
I currently only needed a small subset of the IDE (verify text, elements, etc) so some other interactions may not work. Also, the code isn't pretty because I needed this quickly as it's a sub-sub-sub project of a real requirement for SE2 Grid.

Contributions welcomed!
