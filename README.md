![picture alt](http://www.tikalk.com/files/upload/1/tikal_com_logo45n45.png "Tikal Community") reveal.js tikal theme
======================

Theme based on the simple theme  
This theme introduces some minor changes to

* img, link & blockquote attributes 
* background for alm domain add css class to <secion> of almbg
* default background is the grap background appended to the <secion> tag automatically 
  see ./lib/js/tikal.js for more details

	├── README.md
	├── css
	│   ├── images
	│   │   ├── bg_gray.png
	│   │   ├── br_red_ALM.png
	│   │   ├── logo_white.png
	│   │   └── quote.png
	│   ├── source
	│   │   └── tikal.scss
	│   └── theme
	│       └── tikal.css
	└── lib
	    └── js
	        ├── jquery-1.9.1.min.js
	        └── tikal.js


## How to use this with reveal.js 

* git clone this repository
* place files under ./css/... into your reveal.js/css/...
* place files unde ./lib/... into your reveal.js/lib/...

In your index.html header choose the tikal theme like so:

	<link rel="stylesheet" href="css/theme/tikal.css" id="theme">

Add the tikal.js at the __botom__ of your index.html like so:
	
	<script src="lib/js/tikal.js"></script>

Add jquery support like so:

	<script src="lib/js/jquery-1.9.1.min.js" type="text/javascript"></script>

You should be good togo.


## TODO

Add background for other domains ... [ js, java, ror ... ]