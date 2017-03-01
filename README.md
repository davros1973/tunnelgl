# Fork by David Bayliss: changes 2017 Feb

I'm using this fork in an iframe at:  https://blog.xarta.co.uk/contact

Unfortunately I made the changes haphazardly / experimenting to make it work (rather blindly) and outside of source control.  I can see all the changes I made comparing the fork to the later changes, but can't remember why I made them.  I don't know why there is the different library versions r46 vs r47, as I reference the latest version on my contact page:
<script src="https://ajax.googleapis.com/ajax/libs/threejs/r83/three.min.js"></script>

I'll have to check sometime what library it's actually using in practice!

Also the index page referenced the DragPanControls.js file in the Vendor folder, but something else seemed to require it in the threex (extension) folder so I made a copy.

I didn't use the boilerplate (going against the author's suggestion) as I just wanted something working quickly and didn't want to invest too much time learning all of this from such a low starting-position.

And in the index page I removed the title and stats - as I wanted a clean effect in the iframe.

Working in latest (at this time ... Feb 2017):
* Chrome
* Edge
* Firefox
* Chrome mobile (on Note 4)

But not Internet Explorer 11.5

There are still errors reported in Console.

My entire webpage works fine on a (year) 2009 Core 2 Duo laptop (in Chrome!).
The same laptop struggles with it in Edge.

Needs work. (I'm only just restarting to relearn JavaScript let alone three.js or WebGL ... so it's all a "work in progress")


# Original author's ReadMe

[boilerplate for three.js](https://github.com/jeromeetienne/threejsboilerplate)
is a template to get you started. You download it and modify it until it fits your needs.
It is a fast way to start a clean project with [three.js](https://github.com/mrdoob/three.js/).
It avoids repetitive tasks, following DRY principles.
It includes various good practices and compatibilities features.
More details [here](http://learningthreejs.com/blog/2011/12/20/boilerplate-for-three-js/).

# Get Started
```
git clone https://github.com/jeromeetienne/threejsboilerplate.git
```

And start updating ```index.html``` until it fits yours need.






