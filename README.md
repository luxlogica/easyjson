EasyJSON
========

### What is EasyJSON?
EasyJSON is a JSON parser for LiveCode, written solely in LiveCode. Use it to put JSON data directly into LiveCode arrays, and to turn a LiveCode array into a valid JSON document.

### Alternatives to EasyJSON
Because it is a LiveCode script, EasyJSON can run relatively slowly, compared to an external library, written in a lower-level language. The prolific Monte Goulding has produced an external JSON parser for LiveCode, mergJSON, which runs many orders of magnitude faster than EasyJSON. His acclaimed externals can be found on http://mergext.com.

EasyJSON is based on a LiveCode JSON library originally written by the late Mark Smith. That library can still be found and downloaded online. Some of the code in the script was based on some great code originally developed by Andre Garzia (http://www.andregarzia.com).

### How to Use EasyJSON
To use EasyJSON within your LiveCode Server script, just _include easyjson.lc_ in your script.

To use EasyJSON in a LiveCode stack, just copy the contents of the easyjson.lc file - without the opening _<?lc_ and the closing _?>_ tags - into your stack script. 

There are only 2 functions that you are likely to ever need:

  * jsonFromArray( _pArray_ ) - takes in a LiveCode array, and returns a valid JSON document string.
  * arrayFromJSON( _pJson_ ) - takes JSON data and returns a valid LiveCode array. It expects the JSON data to be presented as a valid JSON document, as described in http://json.org.

These 2 functions in turn require other functions that are part of the EasyJSON library, but you are unlikely to use them directly. If you want more detailed information on how these functions work, have a look at the (heavily commented) script.

### License
EasyJSON is given to the world under public domain. You are free to use it in any project, open source or commercial, as you wish. 

The only thing you are not allowed to do, is to sue the authors and contributors of EasyJSON, for any damage or loss that the library may cause you - that is, you assume all legal responsibility for its usage and consequences. 

__USE AT YOUR OWN RISK__
No promises are made of suitability or dependability on this code, for any purpose.
You cannot hold the authors liable for any damage or loss due to any use or application of this code.

### How to Contribute
EasyJSON is an open source project. The code is thoroughly documented, and you are encouraged to study it, and improve on it. 

If you do make an improvement, please share your code back with the LiveCode community! 
