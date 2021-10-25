# CHANGELOG

## v3.0.0 - 2021-09-15
### Breaking changes
- `wordsCount` does not longer hold a default value of `50`. You now need to explicitely provide a number greater than `0`.

### Other changes
- Add `charactersCount` option to give the flexibility to truncate the initial text content by characters count as well.

## v2.0.0 - 2021-08-20

### Breaking changes
- Rename `numOfWords` option to `wordsCount`.
- Remove the container element of the "Read more/less" link along with `containerClass` option and place the link inline by default. You can still use a CSS class to make the link element block using the `linkClass` option.
- Do not provide a default value for `linkClass` option.
- Remove `data-readmore` and `id` attributes from the "Read more/less" link element.
- Update the way to initialise the library.  
  Prior to v2.x: `$readMoreJS.init(options);`.  
  From v2.x onwards: `$readMoreJS(options);`

## v1.2.0 - 2021-08-18
- Export library in UMD format.
- Provide a way to destroy if no longer needed.

## v1.1.1 - 2021-08-18
- Fix issue [#4](https://github.com/georapbox/ReadMore.js/issues/4)

## v1.1.0 - 2018-10-15
- Add more customisation options for the anchor element.

## v1.0.0
- Initial release
