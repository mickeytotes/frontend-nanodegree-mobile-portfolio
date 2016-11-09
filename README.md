# Website Performance Optimization portfolio project

For the most part, I was able to keep my cool while struggling through this project. I'd say that alone is a win in my progess in the FEND program. Below you can read how to access a live version of this project, as well as a breakdown of the performance optimizations I made.

## gh-pages

A live version of the mobile portfolio/pizzaria page is hosted on _github pages_. You can view it **[here](https://mickeytotes.github.io/frontend-nanodegree-mobile-portfolio/)**.

## Optimizations
I've split my breakdown of optimizations into two parts:
  - _Part 1: Optimize PageSpeed Insights score for `index.html`_
  - _Part 2: Optimize Frames per Second in `pizza.html`_

#### Part 1: Optimize PageSpeed Insights score for `index.html`
  - inline css
  - used a query to make `print.css` non-render blocking
  - made sure `perfmatters.js` and `analytics.js` were both `async`
  - optimized images

_These changes achieved a pagespeed of `94` on desktop and `95` on mobile!_

#### Part 2: Optimize Frames per Second in `pizza.html`

  - minified css and js
  - took/created variables outside the for-loop in `changePizzaSizes()`
  - decreased the amount of items to append on `ln: 532`

## License
Code released under the [MIT License](/LICENSE.txt)