<!DOCTYPE html>
<head>
<title>{Title} / about</title>

<link rel="shortcut icon" href="{Favicon}">
<link rel="alternate" type="application/rss+xml" href="{RSS}">
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<!---
    
    HYACINTH ABOUT PAGE BY SEYCHE.TUMBLR.COM
    
    CREDITS:
    -feather icons by Cole Bemis
	-icons from fontawesome
    -tippy.js tooltips by atomiks
    (full list of credits @ seyche.tumblr.com/credits)
    
--->

<link href="https://fonts.googleapis.com/css2?family=ABeeZee:ital@0;1&family=Barlow:ital,wght@0,400;0,700;1,400;1,700&family=Karla:ital,wght@0,400;0,700;1,400;1,700&family=Lato:ital,wght@0,400;0,700;1,400;1,700&family=Lora:ital,wght@0,400;0,700;1,400;1,700&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=PT+Sans:ital,wght@0,400;0,700;1,400;1,700&family=PT+Serif:ital,wght@0,400;0,700;1,400;1,700&family=Public+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&display=swap" rel="stylesheet">

<script src="//ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>

<script src="https://unpkg.com/feather-icons"></script>

<script src="https://kit.fontawesome.com/6ac5c36b23.js"></script>

<style type="text/css">

/*----- START EDITING HERE -----*/

/*----- VARIABLES: EDIT THIS SECTION!!!! -----*/

:root {
    
    /*----- colours -----*/
    
    --background: #f0f0f0;
    --content-background: #fff;
    --text: #575757;
    --links: #8c8c8c;
    --title: #212121;
    --borders: #e0e0e0;
    --accent: #9fa8da;
    --gradient-1: #7986cb;
    --gradient-2: #e1bee7;
    --icon-background: #f5f6ff;
    --sidebar-link-background: #f5f5f5;
    --statistics-background: #f5f5f5;
    
    --fave-colour-one: #a1cdf7;
    --fave-colour-two: #f5bad9; 
    --fave-colour-three: #abb6ff;
    --fave-colour-four: #ffc9dd;
    
    /*----- font styling -----*/
    
    --body-font: 'Public Sans', sans-serif;
    --font-size: 14px;
    
    /*----- body styling -----*/
    
    --content-corners: 10px;
    --drop-shadows: 1px 1px 3px var(--borders),
                -1px 1px 3px var(--borders);;
                
    /*----- section visiblity: change the values below to "none" instead of "block" to hide each section if you want to hide them -----*/
    
    --quote-box: block;
    --social-media-box: block;
    --skills-box: block;
    --favourites-box: block;
    --aesthetics-box: block;
    
}

/*----- END VARIABLES: you don't need to edit the css after here -----*/

@keyframes lazyload {
    0%   {opacity: 0;}
    100% {opacity: 1;}
}
 
@-webkit-keyframes lazyload {
    0%   {opacity: 0;}
    100% {opacity: 1;}
}
 
@-moz-keyframes lazyload {
    0%   {opacity: 0;}
    100% {opacity: 1;}
}
 
@-o-keyframes lazyload {
    0%   {opacity: 0;}
    100% {opacity: 1;}
}

body {
    font-family: var(--body-font);
    font-size: var(--font-size);
    color: var(--text);
    background-color: var(--background);
    text-align: left;
    line-height: 160%;
    word-wrap: break-word;
    letter-spacing: 0.2px;
    margin: 0;
    padding: 0;
    overflow-x: hidden;
    -webkit-animation: lazyload 2s;
    -moz-animation: lazyload 2s;
    -o-animation: lazyload 2s;
    animation: lazyload 2s;
}

a {
    color: var(--links); 
    text-decoration: none;
    -webkit-transition: all 0.3s;
    -moz-transition: all 0.3s;
    -ms-transition: all 0.3s;
    -o-transition: all 0.3s;
    transition: all 0.3s;
}

a:hover {
    color: var(--accent);
    -webkit-transition: all 0.3s;
    -moz-transition: all 0.3s;
    -ms-transition: all 0.3s;
    -o-transition: all 0.3s;
    transition: all 0.3s;
}

p a {border-bottom: 2px solid var(--accent);}

blockquote {
    padding: 0 0 0 1.25em;
    border-left: 1px solid var(--borders);
    margin: 1.25em 0 1.25em 1.25em;
}

h1, h2, h3, h4, h5, .title {
    color: var(--title);
    letter-spacing: 2px;
    line-height: 160%;
    font-weight: bold;
    text-transform: uppercase;
}

h1 a, h2 a, h3 a, h4 a, h5 a, .title a {color: var(--title);}
h1 a:hover, h2 a:hover, h3 a:hover, h4 a:hover, h5 a:hover, .title a:hover {color: var(--accent);}
h1, .title {font-size: 1.3em;}
h2 {font-size: 1.25em;}
h3 {font-size: 1.15em;}
h4 {font-size: 1.1em;}
h5 {font-size: 1em;}

small {font-size: 0.9em;}
big {font-size: 1.1em;}
b, bold, strong {color: var(--title);}
b a, bold a, strong a {color: var(--title);}
b a:hover, bold a:hover, strong a:hover {color: var(--accent);}

::-webkit-scrollbar {
    width: 17px; 
    height: 17px;
    background-color: var(--background);
}

::-webkit-scrollbar-track {border: 8px solid var(--background); background-color: var(--borders);}
 
::-webkit-scrollbar-thumb {
   border: 6px solid var(--background);
   background-color: var(--title);
   min-height: 24px;
   min-width: 24px;
}

.tippy-tooltip.custom-theme {
    background-color: var(--title);
    color: var(--content-background);
    text-align: center;
    font-family: inherit;
    font-weight: normal;
    text-transform: uppercase;
    letter-spacing: 1px;
    border-radius: 3px;
    font-style: normal;
    padding: 0.25em;
    margin: 20px auto auto 10px;
    font-size: 0.8em;
}

.tmblr-iframe-compact .tmblr-iframe--unified-controls {
    z-index: 999999999!important;
    opacity: 0.6;
    transform: scale(0.8);
    transform-origin: 100% 0;
    -webkit-transform: scale(0.8);
    -webkit-transform-origin: 100% 0;
    -o-transform: scale(0.8);
    -o-transform-origin: 100% 0;
    -moz-transform: scale(0.8);
    -moz-transform-origin: 100% 0;
    -ms-transform: scale(0.8);
    -ms-transform-origin: 100% 0;
    -webkit-transition: all 0.4s;
    -moz-transition: all 0.4s;
    -ms-transition: all 0.4s;
    -o-transition: all 0.4s;
    transition: all 0.4s;
}
 
.tmblr-iframe-compact .tmblr-iframe--unified-controls:hover {
    opacity: 1.0;
    -webkit-transition: all 0.4s;
    -moz-transition: all 0.4s;
    -ms-transition: all 0.4s;
    -o-transition: all 0.4s;
    transition: all 0.4s;
}

#k {
    text-align: center;
    margin: 100px auto;
}

/*----- SIDEBAR -----*/

#sidebar {
    width: 250px;
    text-align: center;
    height: 100%;
    position: fixed;
    top: 0;
    bottom: 0;
    left: 0;
    box-sizing: border-box;
    padding: 50px;
    box-shadow: var(--drop-shadows);
    background-color: var(--content-background);
    overflow: hidden;
}

#sidebar .icon {
    width: 80px;
    height: 80px;
    padding: 5px;
    display: inline-block;
}

#side-icon {
    background: linear-gradient(to bottom right, var(--gradient-1), var(--gradient-2));
    border-radius: 50%;
    padding: 5px;
    display: inline-block;
    margin-bottom: 1.25em;
}

#status-icon {
    position: absolute;
    margin: -16px auto auto 30px;
    width: 20px;
    height: 20px;
    padding: 6px;
    line-height: 20px;
}

#status-icon .feather {
    width: 20px;
    height: 20px;
}

#sidebar .title {display: block;}
#description {margin-top: 1.5em;}

#sidebar nav {
    margin-top: 2.25em;
    text-align: left;
}

#sidebar nav li {list-style-type: none; margin-bottom: 0.75em;}
.nav-txt {float: right;}

#sidebar nav a {
    width: 100%;
    display: block;
    border-radius: 1.75em;
    padding: 0.75em;
    box-sizing: border-box;
    background-color: var(--sidebar-link-background);
}

#sidebar nav a .feather {
    display: inline-block;
    vertical-align: middle;
    margin-right: 1em;
    width: 1.5em;
    height: 1.5em;
    color: var(--accent);
}

#sidebar nav a:hover {
    background-color: var(--accent);
    color: var(--content-background);
    box-shadow: var(--drop-shadows);
}

#sidebar nav a:hover .feather {
    color: var(--content-background);
}

/*----- COMMON -----*/

.icon, #social-media img, #about-header img {
    border-radius: 50%;
    display: inline-block;
    vertical-align: middle;
    background-color: var(--icon-background);
}

.icon-gradient {
    background: linear-gradient(to bottom right, var(--gradient-1), var(--gradient-2));
    border-radius: 50%;
    padding: 3px;
    display: inline-block;
}

.ui-icon {
    position: absolute; 
    background-color: var(--accent);
    border-radius: 50%;
    text-align: center;
}

.ui-icon .feather {color: var(--content-background);}

a .feather {
    -webkit-transition: all 0.3s;
    -moz-transition: all 0.3s;
    -ms-transition: all 0.3s;
    -o-transition: all 0.3s;
    transition: all 0.3s;
}

a:hover .feather {
    -webkit-transition: all 0.3s;
    -moz-transition: all 0.3s;
    -ms-transition: all 0.3s;
    -o-transition: all 0.3s;
    transition: all 0.3s;
}

.upper {
    text-transform: uppercase;
    letter-spacing: 1px;
    font-size: 0.9em;
}

.subtitle {
    text-transform: uppercase;
    letter-spacing: 1px;
    font-weight: bold;
    color: #212121;
    margin-bottom: 1em;
    font-size: 1.15em;
}

article .feather {
    width: 1.25em;
    height: 1.25em;
    color: var(--accent);
    display: inline-block;
    vertical-align: middle;
}

/*----- CONTENT -----*/

#container {
    position: relative;
    width: calc(99vw - 250px);
    margin-left: 250px;
}

#content-wrap {
    width: 700px; 
    margin: 50px auto;
    position: relative;
}

article {
    background-color: var(--content-background);
    position: relative;
    padding: 50px;
    box-sizing: border-box;
    border-radius: var(--content-corners);
    box-shadow: var(--drop-shadows);
}

/*----- MAIN CONTENT -----*/

#social-media img, #about-header img {
    width: 40px;
    height: 40px;
    padding: 3px;
    display: inline-block;
    vertical-align: middle;
}

article .title {
    display: inline-block;
    font-size: 1.25em;
    margin-left: 1em;
}

.main-flex {
    margin-top: 10px;
    display: flex;
    justify-content: flex-start;
    flex-direction: row;
}

.stats {width: 240px;}
.stats li {list-style-type: none; margin-bottom: 0.5em;}
.stats li:last-of-type {margin-bottom: 0;}

.stats span {
    text-transform: uppercase;
    letter-spacing: 1px;
    color: var(--accent);
    font-size: 0.9em;
    margin-right: 0.5em;
    background-color: var(--statistics-background);
    padding: 0.25em 0.5em;
    border-radius: 1em;
}

.summary {width: 450px; margin-left: 9px;}
.summary p:first-of-type {margin-top: 0;}
.summary p:last-of-type {margin-bottom: 0;}

/*----- QUOTE -----*/

#quote {
    margin-top: 10px; 
    text-align: center;
    display: var(--quote-box);
}

#quote b {font-size: 1.25em;}
#quote .upper {color: var(--links); margin-top: 1.5em;}

#quote b::before, #quote b::after {
    content: '❝';
    color: var(--accent);
    font-size: 1.5em;
    display: inline-block;
    position: absolute;
}

#quote b::before {margin-left: -0.75em;}

#quote b::after {
    -webkit-transform: rotate(180deg);
    -moz-transform: rotate(180deg);
    -ms-transition: rotate(180deg);
    -o-transition: rotate(180deg);
    transform: rotate(180deg);
    margin: -0.35em auto auto 0.25em;
}

/*----- BOTTOM BOXES -----*/

.flexing {
    display: flex;
    justify-content: flex-start;
    flex-direction: row;
}

.flex-left, .flex-right {width: 345px;}
.flex-right {margin-left: 10px;}
.flexing article {margin: 10px 0;}

/*----- SOCIAL MEDIA -----*/

#social-media {display: var(--social-media-box);}

#social-wrap a {
    font-size: 1.75em;
    color: var(--accent);
    list-style-type: none; 
    display: inline-block;
    margin: auto 0.75em 0.75em auto;
}

#social-wrap a:hover {color: var(--title);}

.sideblog {
    margin-top: 1.25em;
    display: flex;
    justify-content: flex-start;
    align-items: flex-start;
    flex-direction: row;
}

.sideblog img {width: 2em; height: 2em;}

.sideblog-desc {
    display: inline-block;
    vertical-align: middle;
    margin-left: 1em;
}

.sideblog b, .sideblog i {display: block;}
.sideblog i {color: var(--links);}

/*----- SKILLS -----*/

#skills {display: var(--skills-box);}

.skill-bar {
    width: 100%;
    height: 15px;
    background-color: var(--sidebar-link-background);
    margin-top: 0.5em;
    border-radius: 15px;
    border: 1px solid var(--borders);
    overflow: hidden;
    padding: 3px;
    box-sizing: border-box;
}

#skills li {list-style-type: none; margin-top: 1.5em;}
#skills li:first-of-type {margin-top: 0;}

.skill-bar div {
    background: linear-gradient(to right, var(--gradient-1), var(--gradient-2));
    height: 7px;
    border-radius: 10px;
}

#progress-one {width: var(--skill-one-progress);}
#progress-two {width: var(--skill-two-progress);}
#progress-three {width: var(--skill-three-progress);}

/*----- FAVOURITES -----*/

#favourites {display: var(--favourites-box);}

#favourites li {
    list-style-type: none;
    display: inline-block;
    margin-left: 0.5em;
}

#favourites .upper {margin-top: 1em;}
#favourites li::after {content: ',';}
#favourites li:last-of-type::after {content: '.';}

/*----- AESTHETICS -----*/

#aesthetics {display: var(--aesthetics-box);}

.moodboard {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: space-between;
    border-radius: 5px;
    overflow: hidden;
}

.moodboard img {
    width: 120px;
    height: 120px;
    object-fit: cover;
    overflow: hidden;
    margin-top: 5px;
}

.moodboard img:nth-child(1), .moodboard img:nth-child(2) {
    margin-top: 0;
}

.colours {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: space-between;
    margin-top: 1em;
}

.colours div {
    width: 50px;
    height: 50px;
    border-radius: 3px;
}

#col-1 {background-color: var(--fave-colour-one);}
#col-2 {background-color: var(--fave-colour-two);}
#col-3 {background-color: var(--fave-colour-three);}
#col-4 {background-color: var(--fave-colour-four);}

/*---- MOBILE HEADER -----*/
 
#mobile-header {
    position: fixed;
    z-index: 100;
    padding: 1.75em 2em;
    top: 0;
    left: 0;
    right: 0;
    box-sizing: border-box;
    box-shadow: var(--drop-shadows);
    background-color: var(--content-background);
    display: none;
}
 
.menu-button {
    display: inline-block;
    cursor: help;
    vertical-align: middle;
    -webkit-transition: all 0.3s;
    -moz-transition: all 0.3s;
    -ms-transition: all 0.3s;
    -o-transition: all 0.3s;
    transition: all 0.3s;
}
 
.menu-button .feather, .close a .feather {
    color: var(--content-background);
    width: 1.5em;
    height: 1.5em;
    background-color: var(--accent);
    border-radius: 50%;
    padding: 0.75em;
    -webkit-transition: all 0.3s;
    -moz-transition: all 0.3s;
    -ms-transition: all 0.3s;
    -o-transition: all 0.3s;
    transition: all 0.3s;
}
 
.menu-button:hover .feather, .close a:hover .feather {
    background-color: var(--title);
    -webkit-transition: all 0.3s;
    -moz-transition: all 0.3s;
    -ms-transition: all 0.3s;
    -o-transition: all 0.3s;
    transition: all 0.3s;
}
 
#mobile-header .subtitle {
    display: inline-block;
    font-size: 1.15em;
    margin-left: 1em;
}
 
#mobile-flex {
    display: flex;
    justify-content: space-between;
    align-items: center;
}
 
.mobile-controls a .feather {
    width: 1.75em;
    height: 1.75em;
    -webkit-transition: all 0s;
    -moz-transition: all 0s;
    -ms-transition: all 0s;
    -o-transition: all 0s;
    transition: all 0s;
}
 
.mobile-controls a {margin-left: 1em;}
 
.close {
    display: none;
    text-align: right;
    margin-bottom: 1em;
}
 
.close a {cursor: help;}

/*---- RESPONSIVENESS -----*/

@media only screen and (max-width: 1100px) {
    #mobile-header, .close {display: block;}
   
    #sidebar {
        left: -250px;
        z-index: 9999;
        -webkit-transition: ease-in-out 0.7s;
        -moz-transition: ease-in-out 0.7s;
        -ms-transition: ease-in-out 0.7s;
        -o-transition: ease-in-out 0.7s;
        transition: ease-in-out 0.7s;
    }
   
    #sidebar.show {left: 0;}
   
    #container {
        width: 100%;
        margin: 150px auto 50px auto;
    }
}

@media only screen and (max-width: 800px) {
    #content-wrap {width: 90vw;}
    
    article, .stats, .summary {width: 100%;}
    
    .main-flex {flex-direction: column;}
    
    .summary {margin: 10px auto auto auto;}
}

@media only screen and (max-width: 780px) {
    .flexing {flex-direction: column;}
    .flexing article {margin: 10px auto auto auto;}
    
    .flex-left, .flex-right {width: 100%;}
    .flex-right {margin: auto;}
    
    .moodboard img {border-radius: 5px; width: 24%; height: 24%;}
    .moodboard img:nth-child(3), .moodboard img:nth-child(4) {
        margin-top: 0;
    }
}
 
@media only screen and (max-width: 500px) {
    
    #content-wrap {width: 100vw;}
     
    article {
        width: 100%;
        padding: 30px;
        border-radius: 0;
    }
   
    #sidebar {width: 80vw; left: -80vw;}
}

</style>
</head>

<body>

<!----- HEADER FOR MOBILE LAYOUT: do not edit this section ----->
 
<header id="mobile-header">
    <div id="mobile-flex">
        <div id="mobile-left">
            <div class="menu-button" title="open menu"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-menu"><line x1="3" y1="12" x2="21" y2="12"></line><line x1="3" y1="6" x2="21" y2="6"></line><line x1="3" y1="18" x2="21" y2="18"></line></svg></div>
            <div class="subtitle">about</div>
        </div>
        <div class="mobile-controls">
            <a href="https://www.tumblr.com/follow/{Name}" title="follow"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-plus-square"><rect x="3" y="3" width="18" height="18" rx="2" ry="2"></rect><line x1="12" y1="8" x2="12" y2="16"></line><line x1="8" y1="12" x2="16" y2="12"></line></svg></a>
            <a href="https://www.tumblr.com/message/{Name}" title="message">
<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-message-square"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"></path></svg></a>
            <a href="https://www.tumblr.com/dashboard" title="dashboard"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-compass"><circle cx="12" cy="12" r="10"></circle><polygon points="16.24 7.76 14.12 14.12 7.76 16.24 9.88 9.88 16.24 7.76"></polygon></svg></a>
        </div>
    </div>
</header>

<!----- ================================
   
    SIDEBAR
           
====================================== ----->

<aside id="sidebar">

    <!--- mobile close button: don't touch --->
    
    <div class="close"><a title="close menu"><svg xmlns="http://www.w3.org/2000/svg" width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-x"><line x1="18" y1="6" x2="6" y2="18"></line><line x1="6" y1="6" x2="18" y2="18"></line></svg></a></div>
    
    <!----- START EDITING HERE ----->
    
    <div id="side-icon">
    
        <!--- by default, your blog icon shows up in the sidebar. to change it, replce {PortraitURL-128} below with the url of whatever image you want. --->
        
        <img src="{PortraitURL-128}" class="icon"/>
        <div class="ui-icon" id="status-icon"><i data-feather="user" aria-hidden="true"></i></div>
        
    </div>
    
    <!--- sidebar title --->
        
    <div class="title">about</div>
    
    <!--- sidebar links: to change the icons, go to feathericons.com and change the name of the icon below to whatever icon you want --->
        
    <nav class="upper">
    
        <li><a href="/">
            <i data-feather="home"></i>
            <span class="nav-txt">home</span>    
        </a></li>
        <li><a href="/ask">
            <i data-feather="mail"></i>
            <span class="nav-txt">message</span>    
        </a></li>
        <li><a href="/archive">
            <i data-feather="grid"></i>
            <span class="nav-txt">archive</span>
        </a></li>
        <li><a href="/">
            <i data-feather="star"></i>
            <span class="nav-txt">one</span>
        </a></li>
        
    </nav>
    
    <!--- 
    
    adding more sidebar links:
    
    copy and paste this template:
    
    <li><a href="/">
        <i data-feather="link"></i>
        <span class="nav-txt">link/span>
    </a></li>
    
    and put it above "</nav>" in the space above. you can copy and paste as many times as you want,
    
    --->
    
</aside>

<!----- ================================
   
    END OF SIDEBAR
           
====================================== ----->

<!----- MAIN CONTENT ----->

<section id="container">
    
    <!----- ================================
    
    START EDITING ABOUT CONTENT HERE
    
    ====================================== ----->
    
    <div id="content-wrap">
    
        <!----- ABOUT HEADER ----->

        <article id="about-header">
        
            <!--- by default, your blog icon shows up in the sidebar. to change it, replce {PortraitURL-128} below with the url of whatever image you want. --->
        
            <div class="icon-gradient">
                <img src="{PortraitURL-128}"/>
            </div>
            
             <div class="title">name</div>
             
        </article>
        
        <!----- END OF ABOUT HEADER ----->
            
        <div class="main-flex">
            
            <!----- STATISTICS BOX ----->
            
            <article class="stats">
                
                <div class="subtitle">details</div>
                
                <!--- to add more, copy and paste everything between and including <li></li> as many times as you need. --->
                
                <li>
                    <span>statistic</span>
                    text
                </li>
                    
                <li>
                    <span>statistic</span>
                    text
                </li>
                    
                <li>
                    <span>statistic</span>
                    text
                </li>
                    
                <li>
                    <span>statistic</span>
                    text
                </li>
                    
            </article>
            
            <!----- END OF STATISTICS BOX ----->
            
            <!----- ABOUT SUMMARY ----->
                
            <article class="summary">
                
                <div class="subtitle">about me</div>
                    
                <p>
                    Write your description here. Don't forget to use < p> < /p> (without the spaces) to separate paragraphs. Here's what <b>bold</b>, <i>italicized</i>, and <u>underlined</u> text looks like.
                </p>
                    
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
                </p>
                
            </article>
            
            <!----- END OF ABOUT SUMMARY ----->
            
        </div>
            
        <!----- ================================
    
            END OF MAIN ABOUT 
            
        ====================================== ----->
        
        <!----- QUOTE BOX ----->
            
        <article id="quote">
            
            <b>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</b>
                
            <div class="upper">source</div>
                
        </article>
        
        <!----- END OF QUOTE BOX ----->
            
        <!----- ================================
    
            BEGINNING OF BOTTOM CONTENT
            
        ====================================== ----->
            
        <div class="flexing">
            
            <div class="flex-left">
            
                <!----- SOCIAL MEDIA ----->
                    
                <article id="social-media">
                        
                    <div class="subtitle">elsewhere</div>
                    
                    <div id="social-wrap">
                    
                        <!-----
                        
                        ADDING MORE SOCIAL MEDIA LINKS: the icons are from fontawesome. to change them or add more, go to https://fontawesome.com/icons, find the name of the new icon, and enter it below.
                        
                        the template for a social media lin looks like this:
                        
                        <a href="/" title="@username">
                            <i class="fab fa-icon-name"></i>
                        </a>
                        
                        copy and paste it as many times as you want. make sure to add your url, username, and fontawesome icon - those are the only places you need to edit.
                        
                        ----->
                    
                        <a href="/" title="@twitter">
                            <i class="fab fa-twitter"></i>
                        </a>
                        
                        <a href="/" title="@instagram">
                            <i class="fab fa-instagram"></i>
                        </a>
                        
                        <a href="/" title="@discord">
                            <i class="fab fa-discord"></i>
                        </a>
                        
                        <a href="/" title="@snapchat">
                            <i class="fab fa-snapchat-ghost"></i>
                        </a>
                        
                        <a href="/" title="@spotify">
                            <i class="fab fa-spotify"></i>
                        </a>
                        
                        <a href="/" title="@pinterest">
                            <i class="fab fa-pinterest-p"></i>
                        </a>
                        
                        <a href="/" title="@goodreads">
                            <i class="fab fa-goodreads-g"></i>
                        </a>
                        
                        <a href="/" title="@ko-fi">
                            <i class="fas fa-mug-hot"></i>
                        </a>
                        
                        <a href="/" title="@letterboxd">
                            <i class="fas fa-ellipsis-h"></i>
                        </a>
                    
                    </div>
                    
                    <!--- end of social media links --->
                    
                     <!-----
                     
                     SIDEBLOGS: if you don't want these, delete this section from here to the end. the template for adding more sideblogs looks like:
                     
                     <div class="sideblog">
                    
                        <div class="icon-gradient"><img src="https://via.placeholder.com/30x30.png"/></div>
                        
                        <div class="sideblog-desc">
                            <b><a href="/">@username</a></b>
                            <i>description</i>
                        </div>
                        
                    </div>
                    
                    add as many as you want.
                     
                     ----->
                    
                    <!--- sideblog one --->
                    
                    <div class="sideblog">
                    
                        <div class="icon-gradient"><img src="https://via.placeholder.com/30x30.png"/></div>
                        
                        <div class="sideblog-desc">
                            <b><a href="/">@username</a></b>
                            <i>description</i>
                        </div>
                        
                    </div>
                    
                    <!--- sideblog two --->
                    
                    <div class="sideblog">
                    
                        <div class="icon-gradient"><img src="https://via.placeholder.com/30x30.png"/></div>
                        
                        <div class="sideblog-desc">
                            <b><a href="/">@username</a></b>
                            <i>description</i>
                        </div>
                        
                    </div>
                    
                    <!-----
                    
                    END OF SIDEBLOG SECTION. if you want to add more sideblogs, add them above this line. if you want to delete them, make sure you delete everything above this line.
                    
                    ----->
                        
                </article>
                
                <!----- 
                
                SKILLS: the template for a new skill looks like:
                
                <li>
                    <div class="upper">add your skill title here</div>
                    <div class="skill-bar">
                        <div style="width: 30%;"></div>
                    </div>
                </li>
                
                the only things you need to edit here are the skill titles and the width of the progress bar (the part contained in style="width: 30%;". make sure you give it a percentage value. 
                
                ----->
                
                <article id="skills">
                    
                    <div class="subtitle">skills</div>
                    
                    <li>
                        <div class="upper">skill one</div>
                        <div class="skill-bar">
                            <div style="width: 30%;"></div>
                        </div>
                    </li>
                    
                    <li>
                        <div class="upper">skill two</div>
                        <div class="skill-bar">
                            <div style="width: 85%;"></div>
                        </div>
                    </li>
                    
                    <li>
                        <div class="upper">skill three</div>
                        <div class="skill-bar">
                            <div style="width: 10%;"></div>
                        </div>
                    </li>
                    
                </article>
                
                <!----- END OF SKILLS ----->
                    
            </div>
                
            <div class="flex-right">
            
                <!----- LIKES AND DISLIKES ----->
            
                <article id="favourites">
                
                    <div class="subtitle">favourites</div>
                    
                    <div class="upper">
                        <i data-feather="heart"></i>
                        <li>like</li>
                        <li>like</li>
                        <li>like</li>
                        <li>like</li>
                    </div>
                    
                    <div class="upper">
                        <i data-feather="thumbs-up"></i>
                        <li>activity</li>
                        <li>activity</li>
                        <li>activity</li>
                        <li>activity</li>
                    </div>
                    
                    <div class="upper">
                        <i data-feather="thumbs-down"></i>
                        <li>dislike</li>
                        <li>dislike</li>
                        <li>dislike</li>
                        <li>dislike</li>
                    </div>
                
                </article>
                
                <!----- END OF LIKES AND DISLIKES ----->
                
                <!----- AESTHETICS ----->
                
                <article id="aesthetics">
                    
                    <div class="subtitle">aesthetics</div>
                    
                    <!----- 
                    
                    add the urls of four pictures below. if you add pictures larger than 120px x 120px or pictures that don't have a square ratio, the images will resize without being distorted or stretched. the colours of your favourite colours can be added in the css variables at the top of the theme. 
                    
                    ----->
                    
                    <div class="moodboard">
                        <img src="https://via.placeholder.com/120x120.png"/>
                        <img src="https://via.placeholder.com/120x120.png"/>
                        <img src="https://via.placeholder.com/120x120.png"/>
                        <img src="https://via.placeholder.com/120x120.png"/>
                    </div>
                    
                    <!----- STOP EDITING AFTER HERE ----->
                    
                    <div class="colours">
                        <div id="col-1"></div>
                        <div id="col-2"></div>
                        <div id="col-3"></div>
                        <div id="col-4"></div>
                    </div>
                    
                </article>
                
                <!----- END OF AESTHETICS ----->
                
            </div>
            
            <!----- DO NOT TOUCH ANYTHING AFTER HERE ----->
                
        </div>
        
    </div>
    
    <div id="k" class="upper"><a href="https://seyche.tumblr.com/" title="hyacinth">page by seyche</a></div>
    
</section>

<!----- TOOLTIPS ----->

<script src="https://unpkg.com/popper.js@1"></script>
<script src="https://unpkg.com/tippy.js@5/dist/tippy-bundle.iife.js"></script>

<script>

$(document).ready(function() {
    
    /// SLIDE-IN MOBILE SIDEBAR
   
   $('.menu-button').click(function(){
        $('#sidebar').addClass('show', 700);
    });
   
    $('.close').click(function(){
        $('#sidebar').removeClass('show', 700);
    });
    
    /// TOOLTIPS

    tippy('[title]', {
        theme: 'custom',
        arrow: false,
        followCursor: true,
        delay: 100,
        placement: 'bottom-start',
        zIndex: 9999999999,
        maxWidth: 400,
    
        content(reference) {
          const title = reference.getAttribute('title');
          reference.removeAttribute('title');
          return title;
        },
    });
});

    feather.replace()
    
</script>

</body>
</html>
