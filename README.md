## Updates guide
Change one of the files in `_data`, unless you are changing the look of the website.

Test changes with:
```
jekyll serve
```

## Visitor map

The old ClustrMaps embed has been replaced with an optional Statable map.
Create a site in Statable, copy the 10-character public hash from
`Site settings -> Widget -> Map`, and set `statable_public_hash` in
`_config.yml`. Leaving it empty hides the map without leaving a blank footer.

## External Libraries
- Framework: [Jekyll](http://jekyllrb.com/)
- CSS
  - [Skeleton](getskeleton.com)
  - Tabs: [Skeleton Tabs](https://github.com/nathancahill/skeleton-tabs)
  - Experience: [Timeline](https://codepen.io/NilsWe/pen/FemfK)
  - Icons: [Font Awesome](http://fontawesome.io/)
- JS
  - [Jquery (3.1.1)](https://jquery.com/)
