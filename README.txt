README

This is a readme for Steganogra-py a free steganography tool written in python and created by Zachary Varberg, 2010.  For a fomatted (and most up to date) version of this readme please visit http://code.google.com/p/steganogra-py/wiki/Readme

EXECUTION

    RUN

    Simply run Steganogra-py.exe to start the program. There are two tabs, encode and decode. These are used for their obvious purposes. 

    ENCODING

    On the encode page you will find options for which file you wouldlike to encode (currently only .txt files are supported), what image you would like to encode it in (currently only .png files are supported), and where you would like to save the newly encoded image (also .png only). You are given the option to choose how many of each colors bits you would like to use for encoded data with the remainder of the 8 to be used for the original images color data.These start with the least significant bit and move towards more significant bits.Once everything is set press the encode button, and it will do the rest. 

    DECODING

    The decoding precess is very similar to encoding. You choose image file with the encoded data, and the file where you would like to save the output. You choose the number of bits of each color that were encoded (NOTE: it is important that you choose the same number for each color that was chosen when encoding, otherwise the output will be garbage), and press decode. 

NEW TO 1.1

    * Threading: Steganogra-py is now a multi-threaded app with logic running on a seperate thread than the GUI, this allows the UI to remain responsive. 

    * Progress Dialog: Previously, once the encode button was pressed there was noindication to the user that anything was happening. With 1.1 there is now a progress dialog. The progress dialog does NOT actually display 0-100 percent completion of the task. It DOES however provide some feedback showing that the application is working. 

    * Optimizations: There were a variety of optimizations that went into this version of Steganogra-py. Without boring you with the low-level details the encoding portion was sped up by nearly 20% in tests. This may or may not be the norm, but the application was certainly sped up. 

And that's it! This is hopefully a very simple to use steganography app. While a number of improvements were made for v1.1 they were mostly cosmetic and performance issues. The feature set was not significantly expanded. BUT, development continues and future features include, suggested encoding styles, random encoding, steganography detection (this one is rather difficult so it may or may not happen), as well as support for other file-types. If you have any requests for future features, please don't hesitate to let me know at Zach.Varberg (at) Gmail (dot) com!

The source code is available at http://code.google.com/p/steganogra-py/downloads/list

Stegosaurus icon provided by http://www.fasticon.com
Licensing Information

Copyright (C) 2010 Zachary Varberg author: Zachary Varberg

Steganogra-py is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

Steganogra-py is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with Steganogra-py. If not, see <http://www.gnu.org/licenses/>. 