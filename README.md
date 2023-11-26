# admin-dashboard

## Description

This is a sig nup form project made using vanilla HTML5 & CSS. It is part of [The Odin Project](https://www.theodinproject.com/). At the time of writing, link for this particular project is [Project: Admin Dashboard](https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-admin-dashboard).

## File Structure

It consists of an index file `index.html` as starting point of project that links html & CSS files too. `styles` folder in root directory contains CSS files. One is `styles.css` for styles & other is `reset.css` serving as a css reset file for styles. There are `img`, `icons` & `fonts` directories too.
If the project is redistributed or bundled & provided to others, `OFL.txt` & `README.txt` files of font I am using(Source Sans 3 as time of writing) need to be included too(As far as I can make sense of license).

## Thoughts

This was a great project to sharpen grid concepts. Specially the cards were a great practice. Grid is like the puzzle game of joining pictures. When You have any or all the pieces & its up to you to join them in a proper manner so that a proper picture emerges afterwards. Also learned that flex is content first approach & grid is layout first. Meaning, while using flex, you have content & you have to align it. In grid, you first lay out the tracks for content to be put afterwards, thus it is layout first. I recon, as grid allows you to define track first(rows or columns) of your choice instead of aligning them afterwards & you just have to put the content on specific tracks, it makes a great use case for complex layouts. On the other hand, I found flexbox to be more useful for alignment of already placed content, more than grid. If we take joining pictures puzzle game's example, flex is like moving pieces around & grid is like putting a piece somewhere on puzzle. But you gotta know already where to put pieces. You can use grid for overall layout & or big or complex parts in layout & flexbox for aligning individual pieces. With grid, you have to know what to put where beforehand though. Quite an interesting concept grid is, I must say. Mixing it with flex here & there was quite a pleasure too. Overall it was a great tool in future arsenal for laying out projects, specially.

## Future Ideas/Issues

- Search box hover effect is not working yet for some reason.

- Setting sidebar & or header to `position: fixed`.

- Using & better rounded avatars as profile pictures for current user & trending card.
