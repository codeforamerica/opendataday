[![Build Status](http://travis-ci.org/okfn/opendataday.svg?branch=master)](http://travis-ci.org/okfn/opendataday)

National Day of Civic Hacking is a nationwide day of action for volunteers around the country to put technology to work for the benefit of our local communities.

National Day of Civic Hacking will take place on Saturday, September 23rd, 2017. We'll have a Brigade Boot Camp a few weeks before that. 

Check <http://ndoch.org/> for public website.

## Editing / contributing

This site is built with [Lektor](https://www.getlektor.com/).

It has a bunch of [dependencies](https://github.com/okfn/opendataday/blob/master/package.json), so do `npm install` and then `npm run build`.

`grunt` will watch for changes to your [SCSS files](https://github.com/okfn/opendataday/tree/master/assets/scss), and also [icons](https://github.com/okfn/opendataday/tree/master/assets/icons) (see [svgstore](https://github.com/FWeinb/grunt-svgstore)).

`lektor deploy` will deploy to the gh-pages branch, putting changes live, if you have deploy permissions.

### TODO

#### Translations

To translate the site we need to duplicate the [contents.lr](https://github.com/okfn/opendataday/blob/master/content/contents.lr) file, and save with the language code in the file name, like [contents+de.lr](https://github.com/okfn/opendataday/blob/master/content/contents%2Bde.lr).

We also need to add translations to [global-content.ini](https://github.com/okfn/opendataday/blob/master/databags/global-content.ini) and [main-nav.ini
](https://github.com/okfn/opendataday/blob/master/databags/main-nav.ini).

If we are adding new language to the site we also need to:

- Add the new language to [languages.json](https://github.com/okfn/opendataday/blob/master/databags/languages.json)
- Add the language to [project.lektorproject](https://github.com/okfn/opendataday/blob/master/project.lektorproject).

## Previous version

The previous version of the site has been moved to the [v1](https://github.com/okfn/opendataday/tree/v1) branch.

## 
This repo was forked from the Open Data Day site. 
