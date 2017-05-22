# cssmal 
/*Layout codes, please leave this line intact when copying the whole thing. Don't touch it. 
*/
/* General codes */
@import url(https://malcat-gen.appspot.com/series?preset=dataimagelinkbefore);
@import url(https://fonts.googleapis.com/css?family=Rancho);
@import url(https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.css);
@import url(https://fonts.googleapis.com/css?family=Kaushan+Script|Tangerine);
 
#advanced-options {
    position: fixed;
    top: 24px;
    left: 0;
    right: 0;
    background-color: rgba(255,255,255,1);
    display: none;
    width: 860px;
    margin: 0 auto;
    padding: 25px 0px 30px;
    -moz-box-shadow: 0px 2px 8px 0px rgba(0,0,0,0.3);
    -webkit-box-shadow: 0px 2px 8px 0px rgba(0,0,0,0.3);
    -o-box-shadow: 0px 2px 8px 0px rgba(0,0,0,0.3);
    -ms-box-shadow: 0px 2px 8px 0px rgba(0,0,0,0.3);
    box-shadow: 0px 2px 8px 0px rgba(0,0,0,0.3);
    color: #323232;
    text-align: left;
    font-family: 'Helvetica neue', Helvetica, "lucida grande", tahoma, verdana, arial, sans-serif;
    z-index: 1101;
    border: none;
background-image: url(http://i.imgur.com/cQJV4Oqg.png);
    background-repeat: no-repeat;
    background-size: contain;
    background-position: bottom right;  }
     
#advanced-options .advanced-options-header {
    width: 750px;
    margin: 0px auto;
    padding-bottom: 4px;
    border-bottom: 1px solid #BEBEBE;
    font-size: 16px;
    color:rgba(0,0,0,.6) !important;
}
 
 
#advanced-options .advanced-options-header .description {
    font-size: 12px;
    font-weight: normal;
    margin-left: 8px;
    color:rgba(0,0,0,.6) !important;
}
 
#advanced-options .sort-widget .widget-header, #advanced-options .filter-widget .widget-header, #advanced-options .filter-widget.aired-date .text, #advanced-options .filter-widget.published-date .text {
color:rgba(0,0,0,.6) !important;
}
 
#advanced-options select {
    -ms-appearance: none;
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    background-image: url(/img/pc/ownlist/icon_pulldown_triangle.png);
    background-repeat: no-repeat;
    background-position: center right;
    background-size: 18px 8px;
    background-color: #FFFFFF;
    display: inline-block;
    height: 25px;
    padding: 4px 20px 4px 4px;
    padding-right: 4px\0;
    border: #BEBEBE 1px solid;
    border-radius: 0px;
    font-size: 12px;
}
#advanced-options select::-ms-expand {
    display: none;
}
 
#advanced-options select:disabled {
    background-image: url(/img/pc/ownlist/icon_pulldown_triangle_disable.png);
    color: #9B9B9B;
}
 
#advanced-options input[type=text] {
    padding: 4px;
    border: #BEBEBE 1px solid;
}
 
#advanced-options input:focus {
    outline: none;
}
 
 
/* sort */
#advanced-options .sort-widget {
    margin: 0px auto;
    padding: 12px 0px 0px;
    width: 750px;
}
#advanced-options .sort-widget:last-of-type {
    padding-bottom: 45px;
}
 
#advanced-options .sort-widget select {
    width: 172px;
    margin-right: 8px;
}
 
#advanced-options .sort-widget input[type=radio] {
    display: none;
}
#advanced-options .sort-widget input[type=radio] + label {
    background-color: #FFFFFF;
    display: inline-block;
    width: 56px;
    padding: 5px 0px;
    border: #BEBEBE 1px solid;
    border-radius: 4px;
    color: #323232;
    font-size: 12px;
    text-align: center;
    cursor: pointer;
}
#advanced-options .sort-widget input[type=radio]:checked + label {
    background-color: #244291;
    border: #244291 1px solid;
    color: #FFFFFF;
}
#advanced-options .sort-widget input[type=radio]:disabled + label {
    border: #BEBEBE 1px solid;
    color: #9B9B9B;
}
#advanced-options .sort-widget input[type=radio]:checked:disabled + label {
    background-color: #FFFFFF;
    border: #BEBEBE 1px solid;
    color: #9B9B9B;
}
 
/* filter */
#advanced-options .filter-widget {
    margin: 0px auto;
    padding: 12px 0px 0;
    width: 750px;
}
 
#advanced-options .filter-widget select {
    margin-right: 8px;
    font-size: 12px;
}
 
#advanced-options .filter-widget.title input[type=text] {
    width: 360px;
}
 
#advanced-options .filter-widget.airing-status select,
#advanced-options .filter-widget.publishing-status select {
    width: 152px;
}
 
#advanced-options .filter-widget.producer select,
#advanced-options .filter-widget.magazine select {
    width: 360px;
}
 
#advanced-options .filter-widget.aired-date select.year,
#advanced-options .filter-widget.published-date select.year {
    width: 80px;
}
 
#advanced-options .filter-widget.aired-date select.month,
#advanced-options .filter-widget.published-date select.month,
#advanced-options .filter-widget.aired-date select.day,
#advanced-options .filter-widget.published-date select.day {
    width: 60px;
}
 
#advanced-options .filter-widget.aired-date .text,
#advanced-options .filter-widget.published-date .text {
    display: inline-block;
    margin-right: 4px;
    font-size: 12px;
}
 
#advanced-options .filter-widget.aired-season select.year {
    width: 80px;
}
 
#advanced-options .filter-widget.aired-season select.season {
    width: 110px;
}
 
#advanced-options .sort-widget .widget-header,
#advanced-options .filter-widget .widget-header {
    display: inline-block;
    width: 110px;
    font-size: 12px;
    font-family: 'Helvetica neue', Helvetica, "lucida grande", tahoma, verdana, arial, sans-serif;
}
 
#advanced-options .sort-widget:last-of-type,
#advanced-options .filter-widget:last-of-type {
    padding-bottom: 40px;
}
 
#advanced-options .advanced-options-button {
    width: 750px;
    margin: 0px auto;
    padding: 12px 0px 0px;
    border-top: 1px solid #BEBEBE;
    text-align: center;
}
 
#advanced-options .btn-apply,
#advanced-options .btn-clear {
    background-color: rgba(0,0,0, 0.8);
    display: inline-block;
    width: 135px;
    margin: 0 4px;
    padding: 6px 0px;
    border-radius: 4px;
    font-size: 12px;
    color: #FFFFFF;
    text-align: center;
    -moz-transition-property: all;
    -o-transition-property: all;
    -webkit-transition-property: all;
    transition-property: all;
    -moz-transition-duration: 0.3s;
    -o-transition-duration: 0.3s;
    -webkit-transition-duration: 0.3s;
    transition-duration: 0.3s;
    -moz-transition-timing-function: ease-in-out;
    -o-transition-timing-function: ease-in-out;
    -webkit-transition-timing-function: ease-in-out;
    transition-timing-function: ease-in-out;
}
 
#advanced-options .btn-apply:hover,
#advanced-options .btn-clear:hover {
  background-color: rgba(0,0,0, 0.8);
}
 
 
 
/**
 * General Styles
 */
  
  
td {
    line-height: 1.5em;
    height: 35px !important;
    border:none !important;
}
 
a {
    color: #000;
    text-decoration: none;
}
/*
a:hover {
    color: #fff !important;
    text-decoration: none;
}
 
*/
 
#copyright {
    font-size: 12px;
    color: #FFFFFF;
    padding-top: 3px;
    text-align: center;
}
 
/*
 * Header
 */
.header a {
    font-weight: bold;
    color: #fff !important;
}
.header a:hover {
    text-decoration: underline;
}
 
.header {
	top:0px !important;
    position: fixed;
    color: #fff;
    display: block;
    width: 100%;
    height: 40px;
    margin: 0 auto;
    background: -webkit-linear-gradient(rgba(0,0,0,.4), transparent); /* For Safari 5.1 to 6.0 */
    background: -o-linear-gradient(rgba(0,0,0,.4), transparent); /* For Opera 11.1 to 12.0 */
    background: -moz-linear-gradient(rgba(0,0,0,.4), transparent); /* For Firefox 3.6 to 15 */
    background: linear-gradient(rgba(0,0,0,.4), transparent); /* Standard syntax */
    -moz-transition-property: all;
    -o-transition-property: all;
    -webkit-transition-property: all;
    transition-property: all;
    -moz-transition-duration: 0.3s;
    -o-transition-duration: 0.3s;
    -webkit-transition-duration: 0.3s;
    transition-duration: 0.3s;
    -moz-transition-timing-function: ease-in-out;
    -o-transition-timing-function: ease-in-out;
    -webkit-transition-timing-function: ease-in-out;
    transition-timing-function: ease-in-out;
    z-index: 1 !important;
}

 
.header .header-menu {
    position: absolute;
    top: 5px;
    right: 4px
}
.header .header-menu.other {
    top: 5px;
}
 
 
 

 
 
.header .header-menu .list-menu {
    position: absolute;
    top: 25px;
    right: -4px;
    background-color: rgba(255,255,255,.8);
    display: none;
    border: none !important;
    -moz-box-shadow: rgba(0, 0, 0, 0.4) 0 0 10px;
    -webkit-box-shadow: rgba(0, 0, 0, 0.4) 0 0 10px;
    box-shadow: rgba(0, 0, 0, 0.4) 0 0 10px;
    z-index: 1;
}
 
.header .header-menu .list-menu .icon-menu {
    display: block;
    width: 150px;
    height: 30px;
    color: #000;
    font-size: 14px;
    font-weight: bold;
    text-decoration: none;
    -moz-transition-property: all;
    -o-transition-property: all;
    -webkit-transition-property: all;
    transition-property: all;
    -moz-transition-duration: 0.3s;
    -o-transition-duration: 0.3s;
    -webkit-transition-duration: 0.3s;
    transition-duration: 0.3s;
    -moz-transition-timing-function: ease-in-out;
    -o-transition-timing-function: ease-in-out;
    -webkit-transition-timing-function: ease-in-out;
    transition-timing-function: ease-in-out;
}
 
.header .header-menu .list-menu .icon-menu:hover {
    background-color: rgba(0,0,0,.5);
}
 

 
.header .header-menu .list-menu .icon-menu .text {
    position: absolute;
    left: 52px;
    top: 6px;
}
 
.header .header-menu .list-menu .icon-menu:hover .text {color:rgba(255,255,255,1) !important;
}
 
.header .header-menu .btn-menu {
display: block;
text-align: right;
color: transparent !important;
font-size:12px;
}



#header-menu-dropdown > a {color: rgba(0,0,0,.5) !important;}

/* customize top right menu */

/* login */
.header .header-menu .header-info a[href*="/login"] {
	position:fixed;
	top:0;
	right:25px;
	 background-image: url();
    display: block;
height: 40px;
width: 25px;
    background-size: cover;
    background-color: transparent;
	z-index:10;
	color:transparent !important;
}

.header .header-menu .header-info a[href*="/login"]:before {
	position:fixed;
	top:0;
	right:25px;
content: "\F090";
font-family: 'FontAwesome' !important;
display: block;
text-align: center !important;
color: #eee !important;
font-size:1.7em !important;
height: 40px;
width: 25px;
line-height: 40px;
z-index:9;
background-color: transparent;
}

/*history */

.header .header-menu .header-info a[href*="/history"] {
	position:fixed;
	top:0;
	right:25px;
	 background-image: url();
    display: block;
height: 40px;
width: 25px;
    background-size: cover;
    background-color: transparent;
	z-index:10;
	color:transparent !important;
}

.header .header-menu .header-info a[href*="/history"]:before {
	position:fixed;
	top:0;
	right:25px;
content: "\f1da";
font-family: 'FontAwesome' !important;
display: block;
text-align: center !important;
color: #eee !important;
font-size:1.7em !important;
height: 40px;
width: 25px;
line-height: 40px;
z-index:9;
background-color: transparent;
}

.header .header-menu .header-info {
	font-size: 10px;
    text-align: right;
	position:fixed;
	display:inline-block;
	top:0;
	right:50px;
	height:40px;
	width:120px;
	margin-right:4px !important;
}


/* register */
.header .header-menu .header-info a[href*="/register"] {
	position:fixed;
	top:0;
	right:50px;
	 background-image: url();
    display: block;
height: 40px;
width: 25px;
    background-size: cover;
    background-color: transparent;
	z-index:10;
	color:transparent !important;
}

.header .header-menu .header-info a[href*="/register"]:before {
	position:fixed;
	top:0;
	right:50px;
content: "\f2b9";
font-family: 'FontAwesome' !important;
display: block;
text-align: center !important;
color: #eee !important;
font-size:1.7em !important;
height: 40px;
width: 25px;
line-height: 40px;
z-index:9;
background-color: transparent;
}

.header .header-menu .header-info a[href*="/login"]:hover:before, .header .header-menu .header-info a[href*="/register"]:hover:before, .header .header-menu .header-info a[href*="/history"]:hover:before {
	text-shadow: 0 0 2px #00b7ff, 0 0 1px #00b7ff, 1px 1px 7px #00b7ff, 0 0 0 #00b7ff;
	color:#fff !important;
}



/*your user name */
.header .username {
	position:fixed;
	top:0;
	right:0px;
	 background-image: url();
    display: block;
height: 40px;
width: 25px;
    background-size: cover;
    background-color: transparent;
	z-index:10;
	color:transparent !important;
}

.header .username:before {
	position:fixed;
	top:0;
	right:0px;
content: "\f2be";
font-family: 'FontAwesome' !important;
display: block;
text-align: center !important;
color: #eee !important;
font-size:1.7em !important;
height: 40px;
width: 25px;
line-height: 40px;
z-index:9;
background-color: transparent;
}

.header .username:hover:before {
	color:#fff !important;
	text-shadow: 0 0 2px #00b7ff, 0 0 1px #00b7ff, 1px 1px 7px #00b7ff, 0 0 0 #00b7ff;
}
 
/**
 * Floating Menu
 */

.list-menu-float:before
{content: "\f0c9";
font-family: 'FontAwesome' !important;
display: block;
text-align: center !important;
text-indent: 10px;
color: #fff !important;
font-size:1.5em !important;
height: 40px;
width: 40px;
line-height: 40px;}
 
.list-menu-float:hover:before {
font-size:1.7em !important;
text-shadow: 0 0 2px #00b7ff, 0 0 1px #00b7ff, 1px 1px 7px #00b7ff, 0 0 0 #00b7ff;
-moz-transition-property: all;
    -o-transition-property: all;
    -webkit-transition-property: all;
    transition-property: all;
    -moz-transition-duration: 0.3s;
    -o-transition-duration: 0.3s;
    -webkit-transition-duration: 0.3s;
    transition-duration: 0.3s;
    -moz-transition-timing-function: ease-in-out;
    -o-transition-timing-function: ease-in-out;
    -webkit-transition-timing-function: ease-in-out;
    transition-timing-function: ease-in-out;
}
 
.list-menu-float
{position: fixed;
top: 0px;
left:0px;
width: 50px;
border: none;
opacity: 1;
height: 40px !important;
z-index:100;

}
 
.list-menu-float .icon-menu 
{display: block;
width: 120px;
background-color: #dfdfdf;
height: 30px;
line-height: 30px;
text-indent: 10px;
opacity:0;
margin-left:-120px; 
 }
 
.list-menu-float:hover .icon-menu
{opacity:1;
margin-left:0; 
-moz-transition-property: all;
    -o-transition-property: all;
    -webkit-transition-property: all;
    transition-property: all;
    -moz-transition-duration: 0.3s;
    -o-transition-duration: 0.3s;
    -webkit-transition-duration: 0.3s;
    transition-duration: 0.3s;
    -moz-transition-timing-function: ease-in-out;
    -o-transition-timing-function: ease-in-out;
    -webkit-transition-timing-function: ease-in-out;
    transition-timing-function: ease-in-out;
	}
 
.list-menu-float .icon-menu.profile
{background-image: none !important;} 
 
.list-menu-float .icon-menu.profile:before
{position:absolute;
width:120px !important;
content: "\f007\00a0Profile";
font-family: 'FontAwesome' !important;
margin-top:5px !important;
margin-left:-65px !important;
color: #000;
text-align: center;}
 
.list-menu-float .icon-menu .text
{opacity: 1;
width: auto;
left: 20px;
top: 0;
color: #555555;}
 
.list-menu-float .icon-menu:hover
{width: 120px !important;
background-color:rgba(0,0,0,1) !important;}
 
.list-menu-float .icon-menu:hover .text, .list-menu-float .icon-menu:hover:before, .list-menu-float .icon-menu:hover:after
{color: #fff;
text-shadow: 0 0 2px #00b7ff, 0 0 1px #00b7ff, 0 1px 7px #00b7ff, 0 0 0.5px #00b7ff;
width: auto;}
 
.list-menu-float .icon-menu.logout
{border-radius: 0 0 4px 4px;}
 
.list-menu-float .icon-menu.setting
{display:none;}
 
.list-menu-float .icon-menu svg.icon
{top: 7px !important;
left: 5px !important;
width: 15px;
height: 15px;}
 
.list-menu-float .icon-menu.setting svg.icon-setting {display:none;}
#header-menu-button {display:none;}

.list-menu-float .icon-menu:hover svg.icon {
	fill:#fff !important;
-webkit-filter: drop-shadow( 0 0 2px #00b7ff);
            filter: drop-shadow( 0 0 2px #00b7ff);}

.header .header-menu .list-menu .icon-menu svg.icon {
    position: absolute;
   
    left: 12px;
    top: 4px;
}
 
.header .header-menu .list-menu .icon-menu:hover svg.icon {
    
	text-shadow: 0 0 2px #00b7ff, 0 0 1px #00b7ff, 0 1px 7px #00b7ff, 0 0 0.5px #00b7ff;
}

/**
 * List Container
 */

.list-container {
    position: absolute;
    background-color: transparent;
    width: 1010px;
    left: 0;
    right: 0;
    margin: auto;
	margin-top:100px;
	box-shadow: 0 0 2px #000, 0 0 1px #000, 1px 1px 7px #000, 0 0 0 #000; 
	margin-bottom:30px;
}



/**
 * List Container - Cover Block
 */
.cover-block {
	position:relative;
    display: block;
    width: 1010px;
    margin: 0 auto;
	height:auto;
    text-align: center;
    vertical-align: middle;
	/*box-shadow: 0 0 2px #000, 0 0 1px #000, 1px 1px 7px #000, 0 0 0 #000;*/
	padding-bottom:0;
	
}

.cover-block .image-container {
    display: block;
    width: 1010px;
	height:auto;
	padding-top:0;
}

.cover-block .image-container.hide {
    display: none;
}

.cover-block .image-container img {
    max-width: 1010px;
	height: auto;
}

/* cover image */

#cover-image{

  margin:auto;
  width:1010px !important;
  height:auto;
  background-color:transparent;
  background-size: cover !important;
  background-position: 50% 50%;
 
}

/* setting icon */
.cover-block .image-container .btn-list-setting {
    display: none;
}

.cover-block .image-container:hover .btn-list-setting {
    display: block;
    position: absolute;
    top: 20px;
    right: 28px;
    padding: 8px;
    border: rgba(255,255,255,0) 1px solid;
    font-size: 14px;
    color: #ffffff;
    font-family: 'Helvetica neue', Helvetica, "lucida grande", tahoma, verdana, arial, sans-serif;
}

.cover-block .image-container .btn-list-setting:hover {
    position: absolute;
    top: 20px;
    right: 28px;
    background-color: rgba(0,0,0,0.6);
    padding: 8px;
    border: none;
    -moz-box-shadow: 0 0 4px #000000;
    -webkit-box-shadow: 0 0 4px #000000;
    -o-box-shadow: 0 0 4px #000000;
    -ms-box-shadow: 0 0 4px #000000;
    box-shadow: 0 0 4px #000000;
    font-size: 14px;
    color: #ffffff;
    text-shadow: #323232 1px 1px 1px;
}

.cover-block .image-container .btn-list-setting .fa-camera {
    font-size: 16px;
    -moz-text-shadow: #000000 1px 1px 3px;
    -webkit-text-shadow: #000000 1px 1px 3px;
    -o-text-shadow: #000000 1px 1px 3px;
    -ms-text-shadow: #000000 1px 1px 3px;
    text-shadow: #000000 1px 1px 3px;
    -ms-filter:"progid:DXImageTransform.Microsoft.DropShadow(color=#000000,offx=1,offy=1)";
}

.cover-block .image-container .btn-list-setting .icon-plus-circle {
    position: absolute;
    top: 4px;
    left: 18px;
    background-color: rgba(0,0,0,0.6);
    border-radius: 50%;
    -moz-box-shadow: -1px 1px 0px 0px #323232;
    -webkit-box-shadow: -1px 1px 0px 0px #323232;
    -o-box-shadow: -1px 1px 0px 0px #323232;
    -ms-box-shadow: -1px 1px 0px 0px #323232;
    box-shadow: -1px 1px 0px 0px #323232;
    font-size: 10px;
}

.cover-block .image-container .btn-list-setting .text {
  display: none;
}

.cover-block .image-container .btn-list-setting:hover .text {
  display: inline-block;;
  margin-left: 4px;
}


/**
 * List Container - Status Menu
 */
.status-menu-container {
    width: 1010px;
    height:0;
    background-color: transparent;
	background-image:url();
	background-repeat:repeat;
    border-bottom: none;
    z-index: 1;
	margin-top:0px;
}

.status-menu-container.fixed {
    position: absolute;
    display: none !important;
top: 0; }


.status-menu-container.fixed + div.list-block {
    margin-top: 0px;
}

.status-menu-container .status-menu {
    display: table;
    margin: 0 auto;
    border-collapse: separate;
    border-spacing: 0px 0;
}

.status-menu-container .status-menu .status-button {
	padding:0 !important;
    position: relative;
    display: table-cell;
    font-family: 'Tangerine', cursive;
    text-align: center;
    vertical-align: bottom !important;
    font-size: 22px;
	font-weight:600 !important;
     color: transparent;
	content: none;
	width:125px;
	height:125px;
	z-index:10;
	background-size:cover;
	background-position:50% 50%;
	background-repeat:no-repeat;
	border-radius:50%;
	
	box-shadow: 0 0 5px black inset; 
	  -moz-transition-property: all;
-o-transition-property: all;
-webkit-transition-property: all;
transition-property: all;
-moz-transition-duration: 0.3s;
-o-transition-duration: 0.3s;
-webkit-transition-duration: 0.3s;
transition-duration: 0.3s;
-moz-transition-timing-function: ease-in-out;
-o-transition-timing-function: ease-in-out;
-webkit-transition-timing-function: ease-in-out;
transition-timing-function: ease-in-out;
}


/* status button */
/* all_anime */
.status-menu-container .status-menu .status-button.all_anime {
background-image:url(http://i.imgur.com/lId0VHr.png);	
left:-45px;
bottom:10px;
}

.status-menu-container .status-menu .status-button.all_anime:hover {
background-image:url(http://i.imgur.com/vjU14tt.gif);	
}

.status-menu-container .status-menu .status-button.all_anime.on {
background-image:url(http://i.imgur.com/vjU14tt.gif);	
}

/* watching */

.status-menu-container .status-menu .status-button.watching {
background-image:url(http://i.imgur.com/t7lMD3n.png);	
left:-10px !important;
bottom:15px;
}

.status-menu-container .status-menu .status-button.watching:hover {
background-image:url(http://i.imgur.com/L0mcV1o.gif);		
}

.status-menu-container .status-menu .status-button.watching.on {
background-image:url(http://i.imgur.com/L0mcV1o.gif);		
}

/* completed */

.status-menu-container .status-menu .status-button.completed {
background-image:url(http://i.imgur.com/AEDbcNs.png);	
left:25px !important;
bottom: 20px;
}

.status-menu-container .status-menu .status-button.completed:hover {
background-image:url(http://i.imgur.com/XjXl6jC.gif);	
}

.status-menu-container .status-menu .status-button.completed.on {
background-image:url(http://i.imgur.com/XjXl6jC.gif);	
}

/* on-hold */

.status-menu-container .status-menu .status-button.onhold {
background-image:url(http://i.imgur.com/fvPsFlG.png);	
left:55px !important;
bottom:45px;
}

.status-menu-container .status-menu .status-button.onhold:hover {
background-image:url(http://i.imgur.com/Ev0n5gL.gif);	
}

.status-menu-container .status-menu .status-button.onhold.on {
background-image:url(http://i.imgur.com/Ev0n5gL.gif);	
}

/*dropped */

.status-menu-container .status-menu .status-button.dropped {
background-image:url(http://i.imgur.com/5A8KuyO.png);
left:85px !important;
bottom:75px;
}

.status-menu-container .status-menu .status-button.dropped:hover {
background-image:url(http://i.imgur.com/Y5OrVpa.gif);
}

.status-menu-container .status-menu .status-button.dropped.on {
background-image:url(http://i.imgur.com/Y5OrVpa.gif);
}

/* plan to watch */

.status-menu-container .status-menu .status-button.plantowatch {
background-image:url(http://i.imgur.com/Zk43uJX.png);
left:115px !important;
bottom:105px;
}

.status-menu-container .status-menu .status-button.plantowatch:hover {
background-image:url(http://i.imgur.com/wibV6Up.gif);
}

.status-menu-container .status-menu .status-button.plantowatch.on {
background-image:url(http://i.imgur.com/wibV6Up.gif);
}


.status-menu-container .status-menu .status-button.on, .status-menu-container .status-menu .status-button.on:hover {
   content:none !important;
   color:transparent;
   border: #fff 2px solid;
   box-shadow: 0 0 2px #000, 0 0 1px #000, 1px 1px 4px #000, 0 0 0 #000;
}

.status-menu-container .status-menu .status-button:hover {
	content:none !important;
	color:transparent;
box-shadow: 0 0 2px #000, 0 0 1px #000, 1px 1px 4px #000, 0 0 0 #000;
  -moz-transition-property: all;
-o-transition-property: all;
-webkit-transition-property: all;
transition-property: all;
-moz-transition-duration: 0.3s;
-o-transition-duration: 0.3s;
-webkit-transition-duration: 0.3s;
transition-duration: 0.3s;
-moz-transition-timing-function: ease-in-out;
-o-transition-timing-function: ease-in-out;
-webkit-transition-timing-function: ease-in-out;
transition-timing-function: ease-in-out;
}

/*
.status-menu-container .status-menu .status-button.all_anime.on, .status-menu-container .status-menu .status-button.all_anime.on:hover, .status-menu-container .status-menu .status-button.all_anime:hover
{
	content:none !important;
	color:transparent;
box-shadow: 0 0 2px #e6ee00, 0 0 1px #e6ee00, 1px 1px 4px #e6ee00, 1px 1px 5px #e6ee00;
}

.status-menu-container .status-menu .status-button.watching.on, .status-menu-container .status-menu .status-button.watching.on:hover, .status-menu-container .status-menu .status-button.watching:hover {
	content:none !important;
	color:transparent;
box-shadow: 0 0 2px #1d9af2, 0 0 1px #1d9af2, 1px 1px 4px #1d9af2, 1px 1px 5px #1d9af2;
}

.status-menu-container .status-menu .status-button.completed.on, .status-menu-container .status-menu .status-button.completed.on:hover, .status-menu-container .status-menu .status-button.completed:hover {
	content:none !important;
	color:transparent;
box-shadow: 0 0 2px #ff5151, 0 0 1px #ff5151, 1px 1px 4px #ff5151, 1px 1px 5px #ff5151;
}

.status-menu-container .status-menu .status-button.onhold.on, .status-menu-container .status-menu .status-button.onhold.on:hover, .status-menu-container .status-menu .status-button.onhold:hover {
	content:none !important;
	color:transparent;
box-shadow: 0 0 2px #d611c6, 0 0 1px #d611c6, 1px 1px 4px #d611c6, 1px 1px 5px #d611c6;
}

.status-menu-container .status-menu .status-button.dropped.on, .status-menu-container .status-menu .status-button.dropped.on:hover, .status-menu-container .status-menu .status-button.dropped:hover {
	content:none !important;
	color:transparent;
box-shadow: 0 0 2px #eee, 0 0 1px #eee, 1px 1px 4px #eee, 1px 1px 5px #eee;
}

.status-menu-container .status-menu .status-button.plantowatch.on, .status-menu-container .status-menu .status-button.plantowatch.on:hover, .status-menu-container .status-menu .status-button.plantowatch:hover {
	content:none !important;
	color:transparent;
box-shadow: 0 0 2px #63cb0f, 0 0 1px #63cb0f, 1px 1px 4px #63cb0f, 1px 1px 5px #63cb0f;
}


 .status-menu-container .status-menu .status-button.on:after, .status-menu .status-button:hover:after {
    opacity: 0
}

*/

/*test */

.status-menu-container .status-menu .status-button:after {
    position: absolute;
    top: -38px;
    left: 0px;
    background: transparent; /* Standard syntax */
    display: block;
    width: 125px;
    height: 100px;
	color: #fff !important;
	font-size: 30px !important;
	font-family:Tangerine;
	text-align: center;
vertical-align: middle;
line-height: 50px !important; 
 text-shadow: 0 0 2px #000, 0 0 1px #000, 1px 1px 7px #000, 0 0 0 #FFF !important;
 font-weight: bold;
    opacity: 0;
    -moz-transition-property: all;
    -o-transition-property: all;
    -webkit-transition-property: all;
    transition-property: all;
    -moz-transition-duration: 0.3s;
    -o-transition-duration: 0.3s;
    -webkit-transition-duration: 0.3s;
    transition-duration: 0.3s;
    -moz-transition-timing-function: ease-in-out;
    -o-transition-timing-function: ease-in-out;
    -webkit-transition-timing-function: ease-in-out;
    transition-timing-function: ease-in-out;
	z-index:60;
}

.status-menu .status-button:hover:after {
    opacity: 1;
	top: -38px !important;
	 -webkit-transition:all 0.2s ease-in-out 0.2s;
transition: all 0.2s ease-in-out 0.2s;
 -moz-transition-property: all 0.2s ease-in-out 0.2s;
    -o-transition-property: all 0.2s ease-in-out 0.2s;
}




/* */

.status-menu-container .status-menu .status-button.on:after {
    position: absolute;
    top: -38px;
    left: 0px;
    background: transparent; /* Standard syntax */
    display: block;
    width: 125px;
    height: 100px;
	color: #fff !important;
	font-size: 30px !important;
	font-family:Tangerine;
	text-align: center;
vertical-align: middle;
line-height: 50px !important; 
 text-shadow: 0 0 2px #000, 0 0 1px #000, 1px 1px 7px #000, 0 0 0 #FFF !important;
 font-weight: bold;
    opacity: 1;
    -moz-transition-property: all;
    -o-transition-property: all;
    -webkit-transition-property: all;
    transition-property: all;
    -moz-transition-duration: 0.3s;
    -o-transition-duration: 0.3s;
    -webkit-transition-duration: 0.3s;
    transition-duration: 0.3s;
    -moz-transition-timing-function: ease-in-out;
    -o-transition-timing-function: ease-in-out;
    -webkit-transition-timing-function: ease-in-out;
    transition-timing-function: ease-in-out;
	z-index:60;
}

.status-menu-container .status-menu .status-button.all_anime:after, .status-menu-container .status-menu .status-button.all_anime.on:after {
	content:"All Anime";
}

.status-menu-container .status-menu .status-button.watching:after, .status-menu-container .status-menu .status-button.watching.on:after {
	content:"Watching";
}

.status-menu-container .status-menu .status-button.onhold:after, .status-menu-container .status-menu .status-button.onhold.on:after {
	content:"On Hold";
}

.status-menu-container .status-menu .status-button.completed:after, .status-menu-container .status-menu .status-button.completed.on:after {
	content:"Completed";
}

.status-menu-container .status-menu .status-button.plantowatch:after, .status-menu-container .status-menu .status-button.plantowatch.on:after {
	content:"Plan to Watch";
}

.status-menu-container .status-menu .status-button.dropped:after, .status-menu-container .status-menu .status-button.dropped.on:after {
	content:"Dropped";
}



/* .status-menu-container .status-menu .status-button.watching:before, .status-menu-container .status-menu .status-button.reading:before {
content: "\f152\00a0\00a0";
float: left;
font-size: 1.5em;
font-family: 'FontAwesome' !important;
}

.status-menu-container .status-menu .status-button.completed:before {
content: "\f05d\00a0\00a0";
float: left;
font-size: 1.5em;
font-family: 'FontAwesome' !important;
}

.status-menu-container .status-menu .status-button.onhold:before {
content: "\f017\00a0\00a0";
float: left;
font-size: 1.5em;
font-family: 'FontAwesome' !important;
}

.status-menu-container .status-menu .status-button.plantowatch:before, .status-menu-container .status-menu .status-button.plantoread:before {
content: "\f073\00a0\00a0";
float: left;
font-size: 1.5em;
font-family: 'FontAwesome' !important;
}

.status-menu-container .status-menu .status-button.dropped:before {
content: "\f00d\00a0\00a0";
float: left;
font-size: 1.5em;
font-family: 'FontAwesome' !important;
}

.status-menu-container .status-menu .status-button.all_anime:before {
content: "\f022\00a0";
float: left;
font-size: 1.5em;
font-family: 'FontAwesome' !important;
}*/


/*scroll bar*/

::-webkit-scrollbar
{height: 5px;
width: 7px;
background-color: #eee;}
::-webkit-scrollbar-thumb
{border: 2px solid #fff;
border-radius: 2px;
background-color: #00b7ff;}

/**
 * List Container - Status Menu - Search
 */
.status-menu-container .search-container {
    position: absolute;
    right: 5px;
	z-index:20;
	margin-top: 33px;
}
.status-menu-container .search-container #search-button {
    display: inline-block;
    height: 22px;
    margin-top: 10px;
    color: #fff;
    font-size: 1.6em;
    vertical-align: middle;
}

.status-menu-container .search-container #search-box {
    display: inline-block;
    width: 0;
    height: 22px;
    overflow: hidden;
    margin-top: 5px;
    -webkit-transition: width 0.3s;
    -moz-transition: width 0.3s;
    transition: width 0.3s;
    -webkit-backface-visibility: hidden;
    vertical-align: middle;
}

.status-menu-container .search-container #search-box.open {
    display: inline-block;
    width: 130px;
}

.status-menu-container .search-container #search-box input {
    width: 100%;
    height: 100%;
    box-sizing: border-box;
}



/**
 * List Container - List Block
 */
.list-block {
    margin: 0;
	min-height:265px;
}

.list-unit {
    background-color:rgba(255,255,255,.6);
	background-image:url(http://i.imgur.com/pOCClzN.png);
	background-size:contain;
	background-position:50% 0;
	background-attachment:fixed;
	background-repeat:no-repeat;
	width: 1010px;
	min-height:865px;
	/*box-shadow: 0 0 2px #000, 0 0 1px #000, 1px 1px 7px #000, 0 0 0 #000;*/
}

/**
 * List Container - List Status Title (with Stats)
 */

 
.list-unit.all_anime .list-status-title, .list-unit.completed .list-status-title, .list-unit.dropped .list-status-title {
    position: relative;
    display: table-cell;
    width: 1010px !important;
   height:189px;
   background-color:rgba(255,255,255,0);
   background-image:url(http://i.imgur.com/hQGGjNq.png);   
   background-size:cover;
    background-repeat: no-repeat;
}

.list-unit.watching .list-status-title, .list-unit.onhold .list-status-title, .list-unit.plantowatch .list-status-title {
    position: relative;
    display: table-cell;
      width: 1010px !important;
   height:189px;
   background-color:rgba(255,255,255,0);
   background-image:url(http://i.imgur.com/hQGGjNq.png);   
   background-size:cover;
   background-repeat: no-repeat;
}

.list-unit .list-status-title .text {
    display: block;
	position:absolute;
    width: 1010px;
    height: 38px !important;
	 font-family: 'Kaushan Script', cursive;
    font-size: 22px;
    color: #fff;
    text-align: center;
    vertical-align: middle;
font-weight: 500;
letter-spacing: 0.5px;
border:none;
text-shadow: 0 0 2px #000, 0 0 1px #000, 1px 1px 7px #000, 0 0 0 #FFF !important;
 font-style: bold;
margin-top: 135px !important;
margin-left:20px !important;
}






.list-unit .list-status-title .stats a.filterd {
    text-shadow: 0px 0px 2px #FFF;
}

.list-unit .list-status-title .stats a:hover {
	background:rgba(0,0,0,.5);
padding:8px;
 -moz-transition-property: all;
    -o-transition-property: all;
    -webkit-transition-property: all;
    transition-property: all;
    -moz-transition-duration: 0.3s;
    -o-transition-duration: 0.3s;
    -webkit-transition-duration: 0.3s;
    transition-duration: 0.3s;
    -moz-transition-timing-function: ease-in-out;
    -o-transition-timing-function: ease-in-out;
    -webkit-transition-timing-function: ease-in-out;
    transition-timing-function: ease-in-out;
}


.list-unit .list-stats {
background-color: rgba(255,255,255,.8);
margin-top: -20px !important;
color : #000;
height: 25px;
margin:auto;
position: absolute;
width: 1010px;
z-index: 1 !important;
}

.list-unit .list-status-title .stats {
    position: absolute;
    height: 40px;
    line-height: 40px;
	width:180px;
    right: -35px;
	margin-top:30px;
	z-index: 2;
}

.list-unit .list-status-title .stats a {

    color: #fff;
	padding:8px;
	margin:0 !important;
	text-shadow: 0 0 2px #9B9B9B, 0 0 1px #9B9B9B, 1px 1px 7px #9B9B9B, 0 0 0 #9B9B9B;
}


/**
 * List Container - List Table
 */

.list-table {
    width: 100%;
    margin: 0 auto;
    border-collapse: collapse;
	background-color:transparent !important;
	color: #fff !important;
	border:none;
}

/* columns background color*/

.list-table > tbody:nth-of-type(2n+1) {
     background-color: rgba(0,0,0,0) !important;
}

.list-table > tbody:nth-of-type(2n) {
background-color: rgba(0,0,0,0) !important;
}
 
 /**
 * List Container - List Table - Header
 */
 
.list-table .list-table-header:before {content: "\f0dc\00a0SORT";
display: block;
text-align: center !important;
font-family: 'FontAwesome' !important;
text-indent: 0px;
color: #9B9B9B !important;
font-weight: 700 !important;
width: 57px;
line-height: 40px;
height:40px;
margin-left:0px !important;
}

.list-table .list-table-header:hover:before {color:#fff !important;
background-color:rgba(0,0,0,.5);}

.list-table .list-table-header {
position: absolute;
    display: block;
margin-left:0;
margin-top:-198px;
z-index:200 !important;	
}

.list-table .list-table-header .header-title {
     background: #F6F6F6 url("/img/pc/ownlist/bar-table-header.png") no-repeat right 7px / 1px 22px;
    border-bottom: 0;
    height: 39px;
    text-align: center;
    vertical-align: middle;
	z-index:60 !important;
	display: none;
}

.list-table .list-table-header:hover .header-title {display: block;
-moz-transition-property: all;
    -o-transition-property: all;
    -webkit-transition-property: all;
    transition-property: all;
    -moz-transition-duration: 0.3s;
    -o-transition-duration: 0.3s;
    -webkit-transition-duration: 0.3s;
    transition-duration: 0.3s;
    -moz-transition-timing-function: ease-in-out;
    -o-transition-timing-function: ease-in-out;
    -webkit-transition-timing-function: ease-in-out;
    transition-timing-function: ease-in-out;}

.list-table .list-table-header .header-title:last-child {
    background-image: none;
}

.list-table .list-table-header .header-title.status,.list-table .list-table-header .header-title.number,.list-table .list-table-header .header-title.image,.list-table .list-table-header .header-title.tags  {
    background-image: none;
    display:none !important;
}

.list-table .list-table-header .header-title.title {
    text-align: center;
	width:90px;
	line-height: 40px;
	padding:0 !important;
}

.list-table .list-table-header .header-title.score {
   text-align: center;
	width:90px;
	line-height: 40px;
	padding:0 !important;
}

.list-table .list-table-header .header-title.type {
   text-align: center;
	width:90px;
	line-height: 40px;
	padding:0 !important;
}

.list-table .list-table-header .header-title.progress {
   text-align: center;
	width:90px;
	line-height: 40px;
	padding:0 !important;
}

.list-table .list-table-header .header-title.chapters {
   text-align: center;
	width:90px;
	line-height: 40px;
	padding:0 !important;
}

.list-table .list-table-header .header-title.volumes {
   text-align: center;
	width:90px;
	line-height: 40px;
	padding:0 !important;
}

.list-table .list-table-header .header-title.rated {
   text-align: center;
	width:90px;
	line-height: 40px;
	padding:0 !important;
}

.list-table .list-table-header .header-title.started {
  display:none;
}

.list-table .list-table-header .header-title.finished {
  text-align: center;
	width:90px;
	line-height: 40px;
	padding:0 !important;
}

.list-table .list-table-header .header-title.days {
   text-align: center;
	width:90px;
	line-height: 40px;
	padding:0 !important;
}

.list-table .list-table-header .header-title.storage {
    text-align: center;
	width:90px;
	line-height: 40px;
	padding:0 !important;
}

.list-table .list-table-header .header-title.retail {
   text-align: center;
	width:90px;
	line-height: 40px;
	padding:0 !important;
}

.list-table .list-table-header .header-title.priority {
    text-align: center;
	width:90px;
	line-height: 40px;
	padding:0 !important;
}

.list-table .list-table-header .header-title .link {
    font-size: 11px;
    color: #323232;
    text-decoration: none
	height:40px;
	width:90px;
}

.list-table .list-table-header .header-title.studio {
  display:none !important;
}

.list-table .list-table-header .header-title .link.sort {
    position: relative;
    display: inline-block;
    color: #323232;
	height:40px;
	width:90px;
    white-space: nowrap;
    -moz-transition-property: all;
    -o-transition-property: all;
    -webkit-transition-property: all;
    transition-property: all;
    -moz-transition-duration: 0.3s;
    -o-transition-duration: 0.3s;
    -webkit-transition-duration: 0.3s;
    transition-duration: 0.3s;
    -moz-transition-timing-function: ease-in-out;
    -o-transition-timing-function: ease-in-out;
    -webkit-transition-timing-function: ease-in-out;
    transition-timing-function: ease-in-out;
}

.list-table .list-table-header .header-title .link.sort:hover {
	text-shadow: 0 0 2px #00b7ff, 0 0 1px #00b7ff, 0 1px 7px #00b7ff, 0 0 0.5px #00b7ff;
    color: #fff;
	background-color: rgba(0,0,0,.5);
	height:40px;
	width:90px;
}

.list-table .list-table-header .header-title .sort-icon {
    color: #fff;
}


/* customize list */

.list-table .list-table-data {

}





.header a:hover,.list-table .list-table-data a:not(.edit-disabled):hover {
text-decoration:underline;
}


/**
 * List Container - List Table - Items
 */


.list-table .list-table-data .data {
    display: table-cell;
    padding:0;
    text-align: center;
    vertical-align: middle;
	color: #000 !important;
	border:none;
}


.list-table .list-table-data a:not(.edit-disabled):hover {
    text-decoration: underline;
    color: #fff !important;
}

.list-table .list-table-data a.edit-disabled {
    cursor: text;
    color: #000;
}

.list-table .list-table-data .tags .edit {
    display: block;
    width: 100%;
    text-align: center;
    color:  #2db039;
    font-size: 10px;
    font-family: 'Helvetica neue', Helvetica, "lucida grande", tahoma, verdana, arial, sans-serif;
	display:none;
}
.list-table .list-table-data .tags .edit:hover {
    display:none;
}

.list-table .list-table-data .tags textarea {
    box-sizing: border-box;
    width: 100%;
    height: 60px;
}


.list-table .list-table-data .data.image a {
    display:inline-block!important;
	}


.list-table .list-table-data .data.image {
width:0;
 }

.list-table .list-table-data .data.image .image {
    width: 28px !important;
    height: 27px !important;
	background-size:cover;
	border:1px solid #fff;
	-webkit-box-shadow:2px 2px 8px -3px rgba(0,0,0,.76);
	-moz-box-shadow:2px 2px 8px -3px rgba(0,0,0,.76);
	box-shadow:2px 2px 8px -3px rgba(0,0,0,.76);
	border-radius:5px;
/*display:inline-block!important;*/
display:none !important;
}

/*
.list-table .list-table-data:hover .data.image .image {
display:inline-block!important;
margin-left:-30px;
    opacity: 0;
    -moz-transition-duration: 0.3s ease-in-out;
    -o-transition-duration: 0.3s ease-in-out;
    -webkit-transition-duration: 0.3s ease-in-out;
    transition-duration: 0.3s ease-in-out;
    -moz-transition-timing-function: ease-in-out;
    -o-transition-timing-function: ease-in-out;
    -webkit-transition-timing-function: ease-in-out;
    transition-timing-function: ease-in-out
	-moz-transition:all .3s ease;-webkit-transition:all .3s ease;-o-transition:all .3s ease;transition:all .3s ease; 
	display:none;
} 
*/


/* */
.list-table .list-table-data .data.season * {
	color:#000;
}


.list-table .list-table-data .data.title {
    padding-left: 8px;
    text-align: left;
	width:60%;
	
}

.list-table .list-table-data .data.title a {
line-height:35px !important;
display: inline-block;	
min-width:0;
max-width: 450px; /* the width of your titles */
white-space: nowrap;
text-overflow: ellipsis;
overflow: hidden;	}

.list-table .list-table-data .data.title .link {
    font-size: 17px !important;
 text-decoration: none !important;
font-family: 'Rancho', sans-serif;
font-weight:100 !important;
transition: all 0.3s ease 0s;
color: #000;

}

.list-table .list-table-data:hover .data.title .link {
  letter-spacing: 0.5px;
  transition: all 0.3s ease 0s;
  color: #fff !important;
}
  
.list-table .list-table-data .data.title .rewatching, .list-table .list-table-data .data.title .rereading, .list-table .list-table-data .data.title .content-status {
    text-shadow: 0 0 2px #1a1aff, 0 0 1px #1a1aff, 1px 1px 7px #1a1aff, 0 0 0 #1a1aff !important;
	color: #fff !important;
    font-size: 0.8em !important;
	margin-left:5px;
	display:inline-block;
	margin-top:8px !important;
	position:absolute;
}

.list-table .list-table-data .data.score .link {
    font-size: 1.1em;
    font-weight: bold;
}

.list-table .list-table-data .data.score {
width: 21px !important;
height: 21px !important;

background-repeat: no-repeat;
background-size:contain;
background-position: 50% 50%;
}

.list-table > tbody:nth-of-type(2n+1) .data.score {
	background-image: url(http://i.imgur.com/udzEw6G.png);
}

.list-table  > tbody:nth-of-type(2n+1):hover .data.score {
	background-image: url(http://i.imgur.com/EQcGOeO.png);
}

.list-table > tbody:nth-of-type(2n) .data.score {
	background-image: url(http://i.imgur.com/XbXA3Q5.png);
}

.list-table  > tbody:nth-of-type(2n):hover .data.score {
	background-image: url(http://i.imgur.com/6JtEyjR.png);
}

.list-table .list-table-data:hover .data.score {
	text-shadow: 0 0 2px #000, 0 0 1px #000, 1px 1px 4px #000, 0 0 0 #000;
}

.list-table .list-table-data .data.score a {color:#fff !important;}

td.td1.borderRBL {
color:#fff;
}

/*add edit */

.list-table .list-table-data .data.title .add-edit-more {
    float: right;
    margin-right: 10px;
   font-size:0 !important;
  margin-top:10px;
}


.add-edit-more {
    opacity: 0;
	transition: all 0.2s ease 0s;

}
.list-item:hover .add-edit-more {
    opacity: 1;
	transition: all 0.2s ease 0s;
}

.list-table .list-table-data .data.title .edit a {
	background-image: url(http://i.imgur.com/OT1yCLP.png);
	display: inline-block;
width: 15px;
height: 15px;
	background-size: cover;
	color: transparent !important;
	margin-right: 7px !important;
}

.list-table .list-table-data .data.title .more a {
	background-image: url(http://i.imgur.com/cUAaila.png);
	display: inline-block;
width: 15px;
height: 15px;
	background-size: cover;
	color: transparent !important;
}

.list-table .list-table-data .data.title .add a {
	background-image: url(http://i.imgur.com/AoTgUAL.png);
	display: inline-block;
width: 15px;
height: 15px;
	background-size: cover;
	color: transparent !important;
	margin-right: 7px !important;
}


/* */
.list-table .list-table-data .data.title .more {
    position: relative;
}

.list-table .more-info {
    display: none;
}

.list-table .more-info .more-content {
    padding: 10px;
}

/* */
.list-table .list-table-data .data.number {
	width:2% !important;
}

.list-table .list-table-data:hover .data.number {
	opacity:0;
}

/* review section */

.list-table .list-table-data .data.tags {
	 position: fixed;
    right: calc( 50% + 515px);
top: calc(20% + 230px);
    opacity: 0;
display: inline !important;
line-height: 16px !important;
font-family: Segoe UI, Atilla, Arial, Helvetica, sans-serif;
text-align:left;
width:150px !important;
height:auto !important;
	background-color:rgba(0,0,0,.5);
	 box-shadow: 0 0 2px #000, 0 0 1px #000, 1px 1px 4px #000, 0 0 0 #000;
pointer-events: none;
/* animation */
transition: opacity .3s linear, margin-left .5s ease, transform 1s ease-in-out;
z-index: 6;
}

.list-table .list-table-data .data.tags span:after {
   position: fixed;
   
    right: calc( 50% + 515px);
top: calc(20% + 230px);
    opacity: 0;
display: block !important;
content:'';
width:150px !important;
height:auto;
pointer-events: none;
/* animation */
 transition: opacity .3s linear, margin-left .5s ease, transform 1s ease-in-out;
}

.list-table .list-table-data:hover .data.tags, .list-table .list-table-data:hover .data.tags span:after {
 opacity: 1;
 padding:5px;
 box-sizing: border-box;
 right: calc( 50% + 515px);
 transition: opacity .3s linear, margin-left .5s ease, transform 1s ease-in-out;

}



.list-table .list-table-header .header-title.tags {
display:none;
}

.link.sort + a {display: none;} /* remove watch buttons */

.list-table .list-table-data .data.studio {
position:fixed;
width: 150px;
text-align:center;
right: calc( 50% + 516px);
top: calc(20% + 192px);
height: 30px !important;
opacity:0;
z-index: 60 !important;
background-color: transparent;
	background: rgba(0,0,0,0);
	background: -moz-linear-gradient(top, rgba(0,0,0,0) 0%, rgba(0,0,0,.7) 100%);
	background: -webkit-gradient(left top, left bottom, color-stop(0%, rgba(0,0,0,0)), color-stop(100%, rgba(0,0,0,.7)));
	background: -webkit-linear-gradient(top, rgba(0,0,0,0) 0%, rgba(0,0,0,.7) 100%);
	background: -o-linear-gradient(top, rgba(0,0,0,0) 0%, rgba(0,0,0,.7) 100%);
	background: -ms-linear-gradient(top, rgba(0,0,0,0) 0%, rgba(0,0,0,.7) 100%);
	background: linear-gradient(to bottom, rgba(0,0,0,0) 0%, rgba(0,0,0,.7) 100%);	
	pointer-events:none;
}

.list-table .list-table-data:hover .data.tags, .list-table .list-table-data:hover .data.studio {opacity:1;}

.list-item .data.studio * {
text-shadow: 0 0 2px #000, 0 0 1px #000, 1px 1px 7px #000, 0 0 0 #000 !important;
font-weight: bold !important;
color:#fff !important;

}

   /**
* Large full-res hover images
*/


.data.image a:before
{content: "";
display: block !important;
position: fixed;
top:20%;
right: calc( 50% + 535px);
width: 150px;
height: 221px;
background-color: rgba(0,0,0,.3);
background-position: center !important;
background-repeat: no-repeat !important;
background-size: cover;
border: 1px solid #ffffff;
box-shadow: 0 2px 5px rgba(0,0,0, 0.7);
visibility: hidden;
opacity: 0;
transition: opacity .8s linear, margin-left .5s ease, transform 1s ease-in-out;
z-index: 5;}



.list-table .list-table-data:hover .data.image a:before {
visibility: visible;
opacity: 1;
right: calc( 50% + 515px);
transition: .3s ease-out;}

/* */

.list-table .list-table-data .data.status {
    width: 4px;
}

.list-table .list-table-data .data.status .text {
    font-size:1.5em;
}

.list-table .list-table-data .data.status.reading, .list-table .list-table-data .data.status.watching {
    /*background-color: #2db039 */
	background-color:transparent;
}

.list-table .list-table-data .data.status.plantoread, .list-table .list-table-data .data.status.plantowatch {
     /*background-color: #c3c3c3 */
	background-color:transparent;
}

.list-table .list-table-data .data.status.completed {
     /*background-color: #26448f */
	background-color:transparent;
}

.list-table .list-table-data .data.status.onhold {
     /*background-color: #f1c83e */
	background-color:transparent;
}

.list-table .list-table-data .data.status.dropped {
     /*background-color: #a12f31 */
	background-color:transparent;
}

/* list status */
.list-table .list-table-data .data.status.completed:before, .list-table .list-table-data .data.status.reading:before, .list-table .list-table-data .data.status.watching:before,.list-table .list-table-data .data.status.plantoread:before, .list-table .list-table-data .data.status.plantowatch:before,.list-table .list-table-data .data.status.onhold:before,.list-table .list-table-data .data.status.dropped:before {
display: inline-block !important;
position: absolute;
margin-left:8px;
margin-top:-7px;
z-index: 100 !important;
content: "";
pointer-events: none;
opacity: 0;
text-align:center !important;
}

.list-table .list-table-data:hover .data.status.completed:before, .list-table .list-table-data:hover .data.status.reading:before, .list-table .list-table-data:hover .data.status.watching:before,.list-table .list-table-data:hover .data.status.plantoread:before, .list-table .list-table-data:hover .data.status.plantowatch:before,.list-table .list-table-data:hover .data.status.onhold:before,.list-table .list-table-data:hover .data.status.dropped:before {
	opacity: 1;
	text-align:center !important;
	  -moz-transition-property: all;
    -o-transition-property: all;
    -webkit-transition-property: all;
    transition-property: all;
    -moz-transition-duration: 0.3s;
    -o-transition-duration: 0.3s;
    -webkit-transition-duration: 0.3s;
    transition-duration: 0.3s;
    -moz-transition-timing-function: ease-in-out;
    -o-transition-timing-function: ease-in-out;
    -webkit-transition-timing-function: ease-in-out;
    transition-timing-function: ease-in-out;
 }

.list-table .list-table-data:hover .data.status.completed:before {
/* background-color: #26448f !important; */
color:#fff;
content: "\f05d";
font-size: 1.5em;
font-family: 'FontAwesome' !important;
}

.list-table .list-table-data:hover .data.status.watching:before, .list-table .list-table-data:hover .data.status.reading:before
{
	/*background-color: #2db039 !important;*/
color:#fff;
content: "\f152";
font-size: 1.5em;
font-family: 'FontAwesome' !important;}

.list-table .list-table-data:hover .data.status.plantowatch:before, .list-table .list-table-data:hover .data.status.plantoread:before
{/*background-color: #c3c3c3 !important;*/
color:#fff;
content: "\f073";
font-size: 1.5em;
font-family: 'FontAwesome' !important;}

.list-table .list-table-data:hover .data.status.onhold:before
{/*background-color: #f1c83e !important;*/
color:#fff;
content: "\f017";
font-size: 1.5em;
font-family: 'FontAwesome' !important;}

.list-table .list-table-data:hover .data.status.dropped:before
{/*background-color: #a12f31 !important;*/
color:#fff;
content: "\f00d";
font-size: 1.5em;
font-family: 'FontAwesome' !important;}





/* */



.list-unit .loading-space {
     background-color:rgba(0, 0, 0, 0);
     color: #fff !important;
     display: inline-block;
     margin: auto;
    width: 1000px;
    font-size: 11px;
    line-height:15px;
    text-align: middle !important;
	padding-top: 0px;
 margin-bottom: 0px;
  height:250px;
  background-attachment:scroll;
  background-image:url();
  background-repeat: no-repeat no-repeat;
  background-position: 0% 100%;
}

/*override codes*/
.header .header-info *{color:transparent !important;}
.header .header-info a{color:#eee !important;}
.header .header-menu {color: rgba(255,255,255,0.8) !important;}
.username {color: rgba(255,255,255,0.8) !important;}

.header a {
    font-weight: bold;
    color: #fff !important;
}
.icon-watch, .icon-watch-pv {display:none !important;}


/* */
.header .header-title {
position: absolute;
top: 0px;
left: 40px;
background-image: url("http://i.imgur.com/39cRtfK.png");
background-position: left top;
background-repeat: no-repeat;
background-size: auto 40px;
display: block;
width: 40px !important; 
height: 40px;
text-indent: -9999px;
overflow: hidden
}

/* customization */

/* The list background */


* {cursor: url(http://cur.cursors-4u.net/cursors/cur-11/cur1054.cur), progress !important;}

/* */



 span a[href*="&tag=!"], span a[href*="&tag=%40"], span a[href*="&tag=~"] {display: none !important;}

/* favorite */
@media entrytags-favorites {}
a[href$="&tag=*"]
{position: absolute;
left: 0;
width: 150px;
height: 0;
font-size: 15px;
top: 0px;
color: transparent !important;

}

a[href$="&tag=*"]:after
{content: '\f005';
font-family: 'FontAwesome' !important;
display: inline-block;
pointer-events: all;
/* change the position below, and add in margin-whatever if it's not enough */
position: absolute;
top: -224px; 
left: 130px;
/* change the size of font */
font-size: 1.1em;
color: #fff !important;
text-shadow: 0 0 2px #000, 0 0 1px #000, 1px 1px 7px #000, 0 0 0 #fff !important;
pointer-events:none;
}



/* Intro animation */
@keyframes intro {
  from {
    opacity: 0;
  }
  16% {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
.list-container {
  animation: intro 2s;
}



/* */

footer {
	position: fixed;
	bottom: 0px;
	left: 0px;
	width: 100%;
	height:30px !important;
	z-index: 9998;
	
}

#footer-block {
display:block;
	background-color: transparent;
	background: rgba(0,0,0,0);
	background: -moz-linear-gradient(top, rgba(0,0,0,0) 0%, rgba(0,0,0,.6) 100%);
	background: -webkit-gradient(left top, left bottom, color-stop(0%, rgba(0,0,0,0)), color-stop(100%, rgba(0,0,0,.6)));
	background: -webkit-linear-gradient(top, rgba(0,0,0,0) 0%, rgba(0,0,0,.6) 100%);
	background: -o-linear-gradient(top, rgba(0,0,0,0) 0%, rgba(0,0,0,.6) 100%);
	background: -ms-linear-gradient(top, rgba(0,0,0,0) 0%, rgba(0,0,0,.6) 100%);
	background: linear-gradient(to bottom, rgba(0,0,0,0) 0%, rgba(0,0,0,.6) 100%);	
}

#copyright {
	color: #FFF;
	letter-spacing: 1px;
	text-shadow: 0px 3px 3px #000;
	font-size:10px;
}

#copyright::after {
	content: "Koe no Katachi - Layout designed by Takana no Hana"
}


/*Character renders*/

/*

.list-unit.watching:after, .list-unit.onhold:after, .list-unit.plantowatch:after  {
background-image: url("http://i.imgur.com/iYbcDct.png");
background-repeat: no-repeat;
background-size: contain;
height: 100%;
background-position: right;
display: inline-block !important;
margin: auto !important;
position: fixed !important;
left: 0 !important;
right: 0 !important;
top: 0 !important;
z-index: -5 !important;
content: "";
pointer-events: none;
opacity: 1 !important;
}

.list-unit.completed:after, .list-unit.dropped:after, .list-unit.all_anime:after {
background-image: url("http://i.imgur.com/mX9zg7K.png");
background-repeat: no-repeat;
background-size: contain;
height: 100%;
background-position: right;
display: inline-block !important;
margin: auto !important;
position: fixed !important;
left: 0 !important;
right: 0 !important;
top: 0 !important;
z-index: -5 !important;
content: "";
pointer-events: none;
opacity: 1 !important;
}

*/

/*backgrounds for each category list*/

/*status watching, etc background*/

/*
.list-unit.completed .list-status-title:after {
color: transparent;
height: 432px !important;
width: 800px! important;
background-image: url("http://i.imgur.com/zMH3u2y.png");
background-repeat: no-repeat;
background-size: contain;
position: absolute !important;
display: block !important;
left: 0 !important;
right: 0 !important;
top: 0 !important;
content: "";
z-index: -1 !important;
margin-bottom: 20px !important;
pointer-events: none;
}

.list-unit.watching .list-status-title:after {
color: transparent;
height: 432px !important;
width: 800px! important;
background-image: url("http://i.imgur.com/ctgGmhu.png");
background-repeat: no-repeat;
background-size: contain;
position: absolute !important;
display: block !important;
left: 0 !important;
right: 0 !important;
top: 0 !important;
content: "";
z-index: -1 !important;
margin-bottom: 20px !important;
pointer-events: none;
}

.list-unit.onhold .list-status-title:after {
color: transparent;
height: 432px !important;
width: 800px! important;
background-image: url("http://i.imgur.com/NrPQ2XO.png");
background-repeat: no-repeat;
background-size: contain;
position: absolute !important;
display: block !important;
left: 0 !important;
right: 0 !important;
top: 0 !important;
content: "";
z-index: -1 !important;
margin-bottom: 20px !important;
pointer-events: none;
}

.list-unit.dropped .list-status-title:after {
color: transparent;
height: 432px !important;
width: 800px! important;
background-image: url("http://i.imgur.com/t4n76fz.png");
background-repeat: no-repeat;
background-size: contain;
position: absolute !important;
display: block !important;
left: 0 !important;
right: 0 !important;
top: 0 !important;
content: "";
z-index: -1 !important;
margin-bottom: 20px !important;
pointer-events: none;
}

.list-unit.plantowatch .list-status-title:after {
color: transparent;
height: 432px !important;
width: 800px! important;
background-image: url("http://i.imgur.com/XQbL1KI.png");
background-repeat: no-repeat;
background-size: contain;
position: absolute !important;
display: block !important;
left: 0 !important;
right: 0 !important;
top: 0 !important;
content: "";
z-index: -1 !important;
margin-bottom: 20px !important;
pointer-events: none;
} */

/* Character render on the right list */
/* footer::after {
  content: "";
  display: block;
  width: 20%;
  height: 100%;
  position: fixed;
  bottom: 0px;
  left: calc( 50% + 465px);
  background: url(http://i.imgur.com/MO8goKt.png) no-repeat bottom left;
  pointer-events: none;
 z-index: 3; }
 
 @media screen and (max-height: 835px) {
	 footer::after {
		 background-size: 182px 680px;
	 }
	 
 }*/

/*Change your backgrounds here*/
body[data-query*='"status":1'],
body[data-query*='"status":2'],
body[data-query*='"status":3'],
body[data-query*='"status":4'],
body[data-query*='"status":6'],
body[data-query*='"status":7'] { 
   background-attachment: fixed !important;
  background-position: 50% 50%;
  background-repeat: no-repeat !important;
  background-size:cover;
  background-color:#fff;
   background-image:url(http://i.imgur.com/2T5Xax4.png);
}

body {
	overflow: auto;
}

/* picture at the bottom of your list 
** please note that default is a seiren picture even if you delete the image url below(it's just a sample image which you need to replace). 
** if you don't want this section, type "display:none;" without the quotation marks below background-image line of code
*/
.list-unit .loading-space {
height:20px;
width:1010px;
background-image:url();
}

/*
**Your desired avatar
**Note that the best resolution is 120px * 120px


.cover-block::after {
height: 120px !important;
width: 120px! important;
background-repeat: no-repeat;
background-size: contain;
position: absolute;
display:block !important;
margin-left:57px;
margin-top:-70px;
content: "";
z-index: 2 !important;
padding: 5px;
background-color:#fff;
box-shadow: 0px 2px 8px 0px rgba(0,0,0,0.3);
border-radius:5px;
border: #fff 2px solid;
}

.cover-block::after {background-image: url("http://i.imgur.com/SG9ilbZ.gif");}
*/

/* Your name that displays next to the avatar
** Replace content with "display:none;" if you want to get rid of it
*/
.cover-block::before {
position: absolute;
display:block !important;
margin:auto;
top:0;
width: 1010px;
text-align:center;
color: #fff !important;
font-size: 18px !important;
font-family: Rancho;
text-shadow: 0 0 2px #9B9B9B, 0 0 1px #9B9B9B, 1px 1px 7px #9B9B9B, 0 0 0 #9B9B9B !important; 
letter-spacing: 0 !important; 
}

.cover-block::before {
content: "... If only we could have heard each other's voices from the beginning ...";
z-index:10 !important;
}

.list-table .list-table-data:hover .data {
color: #fff !important;

}

.list-table .list-table-data:hover {
 text-shadow: 0 0 2px #00b7ff, 0 0 1px #00b7ff, 0 1px 7px #00b7ff, 0 0 0.5px #00b7ff;
  color:#fff !important;
  transition: .1s linear;
background-color:rgba(0,0,0,.4);
}

.list-table .list-table-data:hover .data.season *, .list-table .list-table-data:hover .data.score, .list-table .list-table-data:hover .data.progress *{
	color:#fff !important;
}

.list-table .list-table-data .data.tags * {color: #fff !important;
text-shadow: none !important;}
