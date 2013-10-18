CodecJLayerMP3
==============
MP3 codec library for Paulscode's 3D Sound System. It is based on parts of the JLayer (MPEG decoder), MP3SPI, and Tritonus libraries.

## Using it
If you use a IDE, add the codec plugin to your build path.

For use in your source, add the following to your imports:

    import de.cuina.fireandfuel.CodecJLayerMP3;

Add the below to your codecs setup of your class where PaulsCode is used:

    SoundSystemConfig.setCodec("mp3", CodecJLayerMP3.class);

## The license
CodecJLayerMP3 is licensed under the [GNU Lesser General Public License Version 3][License].

## Getting the source
The latest and greatest source can be found here on [GitHub][Source].

If you are using Git, use this command to clone the project:

    git clone git://github.com/Legacy/CodecJLayerMP3.git

Or download the [latest zip archive][Source Download].

## Compiling the source
This project uses Maven to handle its dependencies.

* Install [Maven 2 or 3](http://maven.apache.org/download.html)  
* Checkout this repo and run: `mvn clean package`

[License]: http://www.gnu.org/licenses/lgpl.html
[Source]: https://github.com/Legacy/CodecJLayerMP3
[Source Download]: https://github.com/Legacy/CodecJLayerMP3/archive/master.zip
