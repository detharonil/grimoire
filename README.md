# Grimoire

Grimoire is a mobile-friendly 5e spellbook that organizes spell lists by class and level.

See the latest compiled build [here](http://detharonil.github.io/grimoire/).

## To Do
* Create another layout for the spell level tag pages. Also figure out what to do with those pages; they're just taking up space for now.
* Find a real home for specializations (e.g. cleric's domains, spell schools)

## Structure
Spells can be found inside the `_posts/` directory. Each spell gets its own post, written and stored as a [kramdown](http://kramdown.gettalong.org/) file. The date is arbitrary and never displayed, but still necessary for [Jekyll](http://jekyllrb.com) to process the posts properly.

If you'd like to help fill out the rest of the spells from the PHB, EEPC, or SCAG, for each new spell you:

1. Make a new post inside `_posts/` for each new spell, and copy the formatting from the spell.template file
2. Submit a pull request for the spell(s) when you're finished

## Build Instructions
`bundle exec jekyll build`

## Thanks

Thanks to Saph for doing nearly all of the work.  I just got impatient.

Cleric and wizard spells from the Starter Kit were seeded from [this Reddit post](http://www.reddit.com/r/DnD/comments/2a7wau/5e_cleric_and_wizard_spells_sorted_by_level/).

Thanks to @sethxd for suggesting [Jets.js](http://nexts.github.io/Jets.js/), a CSS search engine that plays nicely with Jekyll.
