# Tiles
---

## Overview
This is an open-source project that allowes the addition of tiles to any webpage. Based off bootstrap, you can arrange your content into nice little tiles. Each  tile includes a background image, a title, and a description.

## Code Example
You would have a container with a bootstrap row object, and inside those place all your tiles. Here is what one tile would look like:

~~~
<div class="col-md-4">
	<div class="tile">
		<img src="images/myimage.jpg" alt="Picture">
		<div class="tile-description">
			<h1>This is the tile's heading</h1>
			<p>This is the tiles description</p>
		</div>
	</div>
</div>
~~~

## Origin
I was building my website, and wanted to add tiles as my main interface. I searched for a good library for tiles, and not finding anything to my liking, decided to make my own. After much work, I had what I wanted. I then thought if I already have all the code, why not make it open-source and help someone else in their search for the right tile library. So, here we are and here is the Tile library. ;)

## Demos
[Here](http://elishacoad.com/libraries/tiles/Demo/demo.html) is the showcase page for the library. Find an example of this library in use here at [Elisha Coad's website](http://elishacoad.com/).

## What needs done?
- Stop the font weight changing apon animation completion
- Have absolute tile sizes (not determined by img size)
- Include Prototype Pics (with it's dimensions included)
- Creat Colored Tiles
- Center Long titles

(if you find any other feature that would be cool, feel free to add the list!)
