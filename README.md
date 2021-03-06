### Path Scrollbar Menu
A Javascript implementation of a Path inspired scrollbar menu

### Why?
At Jetsetter, we needed to enable the user to jump between sections of our homepage while still allowing for a large content area. We've always loved the design of Path, and thought a modified version of their scrollbar menu would allow us to achieve ease of use and the largest content area possible.

### How to use?
We use Mootools as our main framework, and as such, this class is written for use with Mootools. The only requirement is Mootools Core > 1.4. This class should be simple enough to port to a jQuery plugin, and if there is enough interest we will do so (or someone else can do it -- we won't complain). 

To instantiate the class simply call:

	new PathScrollbarMenu(options /* optional options object */);

The point of this class is to subclass it! Use this as a base for whatever your needs are.

### Options
We currently only support two options. FPS and whether to degrade in Internet Explorer. The performance in IE is not fantastic, so by default we hide the menu on scroll, and bring it back once the user is done scrolling. 

The default options are:

	options: {
		fps: 30,
		degradeIE: true 
	}

### Examples
We have included an example page in the examples folder within the project. You can also see the menu in use on the Jetsetter homepage at http://www.jetsetter.com.

Here is what the version on Jetsetter looks like:

![Examples from Jetsetter.com](http://i.imgur.com/1cAmA.png)