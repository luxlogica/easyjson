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
This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or distribute this software, either in source code form or as a compiled binary, for any purpose, commercial or non-commercial, and by any means.

__THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OROTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.__

### Contributing
EasyJSON is an open source project. The script is thoroughly documented, and you are encouraged to study it, and improve on it.

If you do make any corrections or enhancements to the EasyJSON script, we ask you to please share your code back with the LiveCode community, by sending a pull request here on GitHub!

