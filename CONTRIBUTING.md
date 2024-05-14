# Contributing to `datasalad`

## Developer cheat sheet

[Hatch](https://hatch.pypa.io) is used for packaging and development tasks.
Here are a few pointers. For full detail, see the hatch docs.

### Run the tests

```
hatch test [--cover]
```

### Check the `datasalad` version

`hatch` determines the version from the VCS tags. This can help check that
things are correct without having to build a release.

```
hatch version
```

### Build a new source package and wheel

```
hatch build
```

### Publish a new release to PyPi

```
hatch publish
```