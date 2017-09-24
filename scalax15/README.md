# scalax-shapeless-mortals

Slides for Scala eXchange 2015 "Shapeless for Mortals".

The exercises (which the audience are advised to clone in advance) are made available at https://github.com/fommil/shapeless-for-mortals

[Reveal.js](https://github.com/hakimel/reveal.js) is bundled as a submodule. The easiest way to get it is to run this after cloning:

```
git submodule update --init
```

To generate the talk, install [pandoc](http://johnmacfarlane.net/pandoc/) and run `./.scalax-shapeless-mortals.org.pandoc`. Note that pandoc 1.15.x is required, which at the time of writing is not available in Debian (`cabal update ; cabal install pandoc`).
