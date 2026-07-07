# Poledance-DB
I've recently started poledance classes, and I was looking for a way to store and display figures I'm learning, so that I can share it with my friends easily.

See the latest compiled build here: [Add link]

## Structure

Figures can be found inside `_posts/`. Each figure gets its own post, written and stored as a [Markdown](http://daringfireball.net/projects/markdown/basics) file. The date is arbitrary and never displayed, but still necessary for [Jekyll](http://jekyllrb.com) to process the posts properly.

To add a new figure, just follow these steps:

1. Make a new post inside `_posts/` for each new figure, and copy the formatting from another figure. Include an image and video if possible.
2. Submit a pull request for the figure(s) when you're finished, and that's it! Thank you so much. :)

## Build Instructions

I've edited _config.yml for my own build purposes, but if you've got [Jekyll](http://jekyllrb.com) set up locally, the following should create the build from your friendly command line terminal:
`jekyll serve -Vw --no-watch --baseurl ""`

## Thanks

Thanks to @ephe for creating this jekill layout, I've shamelessly ripped it from their wonderful [D&D 5e Spells grimoire](https://github.com/ephe/grimoire) and re-adapted it to my needs.
