# node-siren-import

`node-siren-import` provides a versioned HTML import of [`node-siren-parser`](https://github.com/Brightspace/node-siren-parser).

## Usage

```html
<link rel="import" href="/path/to/siren-parser-import/siren-parser.html">
```

## Updating

To update the version of `node-siren-parser` being used by the import

- Update the version of `node-siren-parser` in `package.json`
- Run `npm i`
- `git commit -a` -- make sure you include the changes to the `node_modules/siren-parser` folder

Once the change is merged, it should be released with a version number matching the version of the parser being used.