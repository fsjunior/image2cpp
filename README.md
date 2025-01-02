## image2cpp

An online version of this tool is live at [http://fsjunior.github.io/image2cpp/](http://fsjunior.github.io/image2cpp/)


image2cpp is a simple tool to change images into byte arrays (or your array back into an image) for use with (4-bit grayscale) displays suchs as EPDs, like those from Lily Go T5. This is a fork of the javl image2cpp project.



### Running the tool
You don't need any special dependencies / internet connection; all the necessary parts sit in a single .html file. So just open this index.html page in a (recent) browser to run the tool.
Or you can use the online version at http://fsjunior.github.io/image2cpp/

### Example Arduino code
You can find a simple Arduino example sketch [over here](https://github.com/fsjunior/image2cpp/blob/master/oled_example/oled_example.ino) in the repository.

### Screen types
I wrote the code with my 960x540 pixel grayscale EPD display in mind, but it should work with most similar displays. You might need to change some export settings; those are explained in the tool.

### Credit
Initial code by [javl](https://github.com/javl) with aditional code by (in alphabetical order):
* [akumpf](https://github.com/akumpf)
* [Daniyal Warraich](https://github.com/daniyalw)
* [davidalim](https://github.com/davidalim)
* [dotcypress](https://github.com/dotcypress)
* [Harry48225](https://github.com/harry48225)
* [hurricaneJoef](https://github.com/hurricaneJoef)
* [jochenderwae](https://github.com/jochenderwae)
* [plewka](https://github.com/plewka)
* [Sebski123](https://github.com/Sebski123)
* [whoisnian](https://github.com/whoisnian)
* [wiredolphin](https://github.com/wiredolphin).

The example sketch is based on code by [Adafruit](https://github.com/adafruit). Dithering code from [stellar-L3N-etag](https://github.com/reece15/stellar-L3N-etag).

### License
image2cpp is released under GPL v3. This means you can use the project in any way you want (use, adapt, distribute, etc.) as long as you share any changes and link back to this repo. See [LICENSE.md](https://github.com/fsjunior/image2cpp/blob/master/LICENSE.md) for more info.
