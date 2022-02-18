# https://github.com/hakimel/reveal.js/releases/tag/4.2.1
# rm -rf reveal.js/examples

all: index.html

# should really be 3840x2160 or downscaled (e.g. 1280x720) but it's not wide enough for code

index.html: talk.org overrides.css
	pandoc --standalone --write=revealjs --incremental \
	--variable revealjs-url=./reveal.js \
	--variable theme:serif \
	--variable width:1600 --variable height:720 --css overrides.css \
	--from org --output index.html \
	talk.org
