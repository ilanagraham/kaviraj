# jQuery-Carousel

>一个简单的jQuery 轮播插件

## Introduction

Based on `jQuery`

[demo](http://chenli94.coding.me/demo/carousel/index.html)

## Install
`clone this repo`

## Usage
### The following HTML structure is used for this plugin: 
```
<link rel="stylesheet" href="carousel.css"/>
	<!-- ... -->
    <div class="carousel">
        <ul class="ct clearfix">
            <li><a href="#"><img src="img/beauty-min.jpeg"></a></li>
            <li><a href="#"><img src="img/fish-min.jpeg"></a></li>
            <li><a href="#"><img src="img/mountain-min.jpeg"></a></li>
            <li><a href="#"><img src="img/young-min.jpeg"></a></li>
            <!-- ... -->
        </ul>
        <a href="#" class="arrow pre"><</a>
        <a href="#" class="arrow next">></a>
        <ul class="bullet">
            <li class="active"></li>
            <li></li>
            <li></li>
            <li></li>
            <!-- ... -->
        </ul>
    </div>
    <!-- ... -->
	<script src="jquery.js">
	<script src="carousel.js">
```

###And this is how the carrousel is initialized:
```
$('.carousel').carousel()
```
### The following options are available:
```
// carousel on / off
autoplay    : false,

// time between transitions
interval    : 2000
```

