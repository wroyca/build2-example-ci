# fang - An executable

The `fang` executable is a <SUMMARY-OF-FUNCTIONALITY>.

Note that the `fang` executable in this package provides `build2` metadata.


## Usage

To start using `fang` in your project, add the following build-time
`depends` value to your `manifest`, adjusting the version constraint as
appropriate:

```
depends: * fang ^<VERSION>
```

Then import the executable in your `buildfile`:

```
import! [metadata] <TARGET> = fang%exe{<TARGET>}
```


## Importable targets

This package provides the following importable targets:

```
exe{<TARGET>}
```

<DESCRIPTION-OF-IMPORTABLE-TARGETS>


## Configuration variables

This package provides the following configuration variables:

```
[bool] config.fang.<VARIABLE> ?= false
```

<DESCRIPTION-OF-CONFIG-VARIABLES>
