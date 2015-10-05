#Raccoony
A Firefox Addon that adds shiny new features (like automatic downloading) to art sites. 

##Features
 * Download any submission from a supported art site to your computer with a single click.
   Files are downloaded into folders organized like so: 
   `[service]/[username]/[id]_[filename]_by_[username].[ext]`
 * Easily view a downloaded submission or user's folder in the OS file manager.
 * Open all submissions in a given view in new tabs.

Many more features are planned. Check the issue tracker for some of them and please feel
free to suggest more.

##Supported sites

 * Fur Affinity
 * InkBunny
 * Weasyl
 * SoFurry
 * deviantArt

The architecture of the addon makes it very easy to add support for more sites, 
so if you see one not on the list, feel free to suggest or write your own plugin
for it. Just look at [one of the plugin js files](https://github.com/NatePri/Raccoony/blob/master/data/plugins/weasyl.js) 
to see an example.

##Download
THIS IS CURRENTLY VERY PRE-ALPHA SOFTWARE. USE AT YOUR OWN RISK.

[Download @raccoony-0.0.4.xpi](https://github.com/NatePri/Raccoony/blob/master/dist/@raccoony-0.0.3.xpi?raw=true)

##Change Log
 * 0.0.4
    - Added fullscreen preview feature.
    - Added option to open the fullscreen preview immediately when opening a submission page.
    - Fixed deviantArt downloading for submissions without a download button.
    - Fixed deviantArt "open all in tabs" support on watchlist notifications page.
 * 0.0.3
    - Enabled deviantArt support
    - Added Open in tabs feature (currently only accessible via page overlay)
    - More consistent filename normalization. Note that this breaks compatibility
      with existing filenames, so already downloaded submissions may show up as
      not downloaded.
    - Fixed a bunch of bugs and did some refactoring.
 * 0.0.2
    - Fixed bug with saving Inkbunny submissions with multiple pages.
 * 0.0.1
    - Initial release.

##Licence
The MIT License (MIT)

Copyright (c) 2015 NatePri

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
