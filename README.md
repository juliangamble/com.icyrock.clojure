You can see this running and read more about it here:
http://juliangamble.com/blog/2012/02/05/clojure-gui-demo-of-led-timer/

This site packages these up for Web Start. 

The point here is to add Java Web start to enable it to be demoed to a wider audience
and promote the clojure community.

----

# com.icyrock.clojure

Some [Clojure](http://clojure.org) programs.

## Running

You need [git](http://git-scm.com/) to clone the repository and [Leiningen](https://github.com/technomancy/leiningen) to be able to fetch the dependencies and optionally run the application. You can use your favorite IDE instead. If you are new to Clojure / Leiningen see [this](http://dev.clojure.org/display/doc/Getting+Started) page for the list of IDEs and tutorials on how to set them up for Clojure development.

Clone the repository locally with `git`:

    git clone git://github.com/icyrockcom/com.icyrock.clojure.git

You should get com.icyrock.clojure folder, `cd` into it and run the appropriate program. 

For example, to run the Seesaw LED-matrix clock example:

    cd com.icyrock.clojure
    lein run -m com.icyrock.clojure.seesaw.led-matrix

## License

Copyright (C) 2012 icyrock.com

Distributed under [Creative Commons CC BY-NC-SA license](http://creativecommons.org/licenses/by-nc-sa/3.0/)

