# ampersand-version

* Add ampersand-version to `"dependencies"` in package.json
* Add browserify transform as per below:

```json
{
    "name": "some-ampersand-module",
    "dependencies": {
        "ampersand-version": "^1.0.1"
    },
    "browserify": {
        "transform": ["ampersand-version"]
    }
}
```

* Add `/*$AMPERSAND_VERSION*/` to the top of the module's main file.

## license

MIT
