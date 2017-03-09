#DemoStrings

Contains the strings used in https://github.com/dtvcfinc/demoTwine.

# Steps to use it

Install twine.

	$ gem install twine

Clone this repository.

	$ git clone https://github.com/dtvcfinc/demoStrings.git
  
Generate a new .po translation.

	$ cd demoStrings
	$ twine generate-localization-file demo.ini spanish.po --lang es
  
Install Poedit, then open the *.po file with Poedit, translate some strings and save.

	$ sudo apt-get install poedit
 
Update the .ini with the new translations 

	$ twine generate-localization-file demo.ini spanish.po --lang es

Push the changes in demo.ini to this repository and update the submodule in https://github.com/dtvcfinc/demoTwine

Compile https://github.com/dtvcfinc/demoTwine and the strings should be there :)

