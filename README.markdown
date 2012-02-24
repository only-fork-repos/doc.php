Readme
------
doc.php is a small parser to display files inside a directory. It creates a list of files and folders to have an easy and fast access to them without building a HTML wire.
It was created by me [@makepanic](https://twitter.com/makepanic) to have a better organized notes. If you got suggestions, just message me :D

Config
------
Put the `index.php` file on your webspace. That's all, if you want to use it with default values.

Usage
-----
doc.php uses [PHP markdown by Michel Fortin](http://michelf.com/projects/php-markdown/) to parse [markdown syntax](http://daringfireball.net/projects/markdown/) to html.
Because of that it's really easy to write well formatted notes or text.

Modifiers
---------

	ROOT_DIR :	default: 'demo'

			   	is the directory where all your documents and folders are.
			   	i.e. if you want to use all files inside ./docs then change it 
			   	from
			   		define('ROOT_DIR','demo');
			   	to
			   		define('ROOT_DIR','docs');

	MAX_NAV  :  default: 4

				is the maximum of folders you want to display in the navigation bar

	SHORT_NAV:	default: 15

				is the amount of letters after it shortens the title

	DOTDOT	 :  default: false

				only change to true, if you really know what you're doing.
				This boolean value allows you to use .. as path.
 
### TODO ###

i'm going to add this later

1. Add a whitelist for file extensions
2. Htaccess options