# Colorful Words

:art: :zap: Creates word-color associations.
***<pic here>***

### Try it out!

Go ahead. Type in a word. Get its associated color palette. :fire: Try it [here](https://greenlantern101.github.io/word-color/)

### How it works

1. Scrapes top 20 google images search of the word.
2. For each image, use [MMCQ (modified median cut quantization)](https://en.wikipedia.org/wiki/Median_cut)) to extract a palette of dominant colors.
3. Average palettes of all images to get final palette.
4. Obviously going to be [very very slow](https://giphy.com/gifs/disneyzootopia-l2JHVUriDGEtWOx0c). Don't worry, optimizations are coming.