all: png/banner-1000.png png/banner-500.png png/banner-email.png

png/banner-1000.png: banner-initial.svg
	convert -density 300 -resize 1000x banner-initial.svg png/banner-1000.png

png/banner-500.png: banner-initial.svg
	convert -density 300 -resize 500x banner-initial.svg png/banner-500.png

png/banner-email.png: banner-email.svg
	convert -density 300 -resize 1400x banner-email.svg png/banner-email.png
