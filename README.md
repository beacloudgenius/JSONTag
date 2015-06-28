#JSONTag

##Description
Writes properties from a given JSON file into the ID3 tags of a given audio file

##Supported Properties
* Title (string)
* Artist (string)
* Album (string)
* Year (int)
* Track Number (int)
* Genre (string)
* Comment (string)
* Artwork (string) (path to PNG file)

##Depenencies
* **[taglib](http://developer.kde.org/~wheeler/taglib.html)**
`brew install taglib`
* **[taglib-ruby](http://robinst.github.com/taglib-ruby/)**
`gem install taglib-ruby`
* **[json](http://flori.github.com/json/)**  
`gem install json`

##Usage

###Command-line arguments:

		ruby jsontag.rb allcloudsconsidered.json allcloudsconsidered.mp3

###Interactive:

		ruby jsontag.rb
		> Location of JSON file to read from:
		-> allcloudsconsidered.json
		> Location of audio file to save to:
		-> allcloudsconsidered.mp3
