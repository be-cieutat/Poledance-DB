# Poledance-DB
I've recently started poledance classes, and I was looking for a way to store and display figures I'm learning, so that I can share it with my friends easily.

See the latest compiled build here: [Poledance DB](https://be-cieutat.github.io/Poledance-DB/)

## TODO
 For moves.html, add an 'alternative names' field, an 'entries' field, remove the useless fields, find what to say in the notes section, change the layout.

 For moves-index.html, add tabs that sort the moves by date learned, by difficulty, by type

 For sessions.html, make the moves practiced clickable to get to the corresponding move.

 For sessions-index.html, add a session members field.

## Structure

Figures can be found inside `_moves/`. Each figure gets its own post, written and stored as a [Markdown](http://daringfireball.net/projects/markdown/basics) file.

To add a new figure, just follow these steps:

1. Make a new post inside `_posts/` for each new figure, and copy the formatting from another figure. Include an image and video if possible.
2. Submit a pull request for the figure(s) when you're finished, and that's it! Thank you so much. :)

## Build Instructions
You need ruby, gem, jekyll and bundler installed to compile this. Then simply run:
`bundle exec jekyll serve`

## Thanks
Thanks to the jekyll community for the ease of setup.
