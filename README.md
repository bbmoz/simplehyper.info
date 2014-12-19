Copyright (c) 2014 simplehyper.info <br />
Copyright (c) 2011-2013 bitaddress.org <br />

SimpleHyper.info - Client-Side HYPER Vanilla Wallet
---------------------------------------

Hyper addresses and their corresponding private key can be conveniently 
generated in a web browser. However, users cannot receive stakes or manage their Hyper in any way, so  
they must ensure that the generated private key is stored in a safe location before using the generated public address.

The simplehyper.info project is inspired by the <a href="https://github.com/pointbiz/bitaddress.org"
target="_blank">bitaddress.org project</a>.

The simplehyper.info project provides an all-in-one HTML document with embedded
JavaScript/Css/Images. The JavaScript is readable (not minified) and contains
simple API GET requests to the <a href="http://hyper.blockexplorer.cc/chain/Hyper/q" target="_blank">Hyper block explorer</a>. 
The benefit of this technique is you can load the JavaScript locally and trust that the JavaScript did not change after being loaded. 

Here is a link to the BitcoinTalk.org forum topic discussing the original bitaddress.org project:
https://bitcointalk.org/index.php?topic=43496.0

Please send DONATIONS for the original bitaddress.org project to the Bitcoin Address: 
1NiNja1bUmhSoTXozBRBEtR8LeF9TGbZBN

END USER NOTES: 
  1. To print QRCode in IE8 you must enable the "Print Background Colors and Images" checkbox on the "Page Setup" screen.
  1. For Bulk Wallet I recommended using Google Chrome, it's the fastest.
  1. Requires IE8+, Firefox, Chrome or sufficient JavaScript support.
  1. Mobile Safari only works with iPhone4 or newer devices. Older devices timeout while executing JavaScript.
  1. DO NOT use Opera Mini it renders JavaScript output server side, therefore they might record the private key you generated.
  1. Art Wallet does not work properly in IE8 due to CSS limitations.

Notice of Copyrights and Licenses
---------------------------------------
The simplehyper.info project, software and embedded resources are copyright simplehyper.info. 
The simplehyper.info name and logo are not part of the open source license. Otherwise, the simplehyper.info software is available under The MIT License (MIT).

Portions of the all-in-one HTML document contain JavaScript codes that are the copyrights 
of others. The individual copyrights are included throughout the document along with their 
licenses. Included JavaScript libraries are separated with HTML script tags.

Summary of JavaScript functions with a redistributable license:

| JavaScript function	|	License |
|-------------------	|	-------------- |
|Array.prototype.map	|	Public Domain|
|window.Crypto	|		BSD License|
|window.SecureRandom	|	BSD License|
|window.EllipticCurve	|	BSD License|
|window.BigInteger	|	BSD License|
|window.QRCode		|	MIT License|
|window.Bitcoin	|		MIT License|

Permission is hereby granted, free of charge, to any person obtaining a copy of this 
software and associated documentation files (the "Software"), to deal in the Software 
without restriction, including without limitation the rights to use, copy, modify, 
merge, publish, distribute, sublicense, and/or sell copies of the Software, and to 
permit persons to whom the Software is furnished to do so, subject to the following 
conditions:

The above copyright notice and this permission notice shall be included in all copies 
or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, 
INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A 
PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT 
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION 
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE 
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
