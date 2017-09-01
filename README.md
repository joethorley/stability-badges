# stability-badges

SVG stability badges for R packages.

## Badges

### Experimental
![stability-experimental](https://img.shields.io/badge/stability-experimental-orange.svg)

Any changes may be [backward incompatible](http://r-pkgs.had.co.nz/release.html#compatibility). 

```markdown
[![stability-experimental](https://img.shields.io/badge/stability-experimental-orange.svg)](https://github.com/joethorley/stability-badges#experimental)
```

### Unstable
![stability-unstable](https://img.shields.io/badge/stability-unstable-yellow.svg)

Backward compatibility will be maintained if possible.

```markdown
[![stability-unstable](https://img.shields.io/badge/stability-unstable-yellow.svg)](https://github.com/joethorley/stability-badges#unstable)
```

### Stable
![stability-stable](https://img.shields.io/badge/stability-stable-green.svg)

Backward incompatible changes will be restricted to [major releases](http://r-pkgs.had.co.nz/release.html#release-version) (if possible!) and functions and arguments will be gradually deprecated with informative warning messages.

```markdown
[![stability-stable](https://img.shields.io/badge/stability-stable-green.svg)](https://github.com/joethorley/stability-badges#stable)
```

### Locked
![stability-locked](https://img.shields.io/badge/stability-locked-blue.svg)

Changes will be restricted to [patches](http://r-pkgs.had.co.nz/release.html#release-version).

```markdown
[![stability-locked](https://img.shields.io/badge/stability-locked-blue.svg)](https://github.com/joethorley/stability-badges#locked)
```

### Deprecated
![stability-deprecated](https://img.shields.io/badge/stability-deprecated-red.svg)

This package is not maintained and should not be used anymore.

```markdown
[![stability-deprecated](https://img.shields.io/badge/stability-deprecated-red.svg)](https://github.com/joethorley/stability-badges#deprecated)
```

## Credits

Basically from https://github.com/orangemug/stability-badges and then forked from https://github.com/emersion/stability-badges.

## Information

For more information see [Releasing a package](http://r-pkgs.had.co.nz/release.html) in R Packages by Hadley Wickham.
