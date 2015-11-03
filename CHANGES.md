# Changes

## Breaking Changes

Value component -> MultiValue

Major API changes to SingleValue and MultiValue

Options & Value components get their label as their Children

new `simpleValue` prop for when you want to deal with values as strings or numbers (legacy behaviour, defaults to false). onChange no longer receives an array of expanded values as the second argument.

## New Select.Async Component

`loadingPlaceholder` prop
`autoload` changed to `minimumInput` and now controls the minimum input to load options
`cacheAsyncResults` -> `cache` (new external cache support) - defaults to true

## Fixes & Other Changes

new `ignoreAccents` prop (on by default), thanks [Guilherme Guerchmann](https://github.com/Agamennon)
new `escapeClearsValue` prop (on by default)

## Notes

`undefined` default props are no longer declared