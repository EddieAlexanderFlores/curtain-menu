# curtain-menu
Sample of a curtain menu created only with HTML and CSS, no JavaScript.
The animation of the curtain was created by using the :target pseudo-class. 
The Hamburger icon is inside an anchor element and has href="#sidenav" that points to the nav element with id="sidenav". The id selector must be used.
The Close icon is also inside an anchor element and has href="#". The # is needed in order prevent the page from reloading and for the animation to work properly.
Initially the nav element is hidden and the animation is done with css.
In the css file, we see the following:
#sidenav { width:0%; transition:0.5s; }
#sidenav:target { width:100%; transition:0.5s; }
Those are the important details for the curtain animation to work. Pretty simple.
