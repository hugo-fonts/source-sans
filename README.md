# Source Sans font for Hugo

This module provides CSS and web fonts for [Source Sans 3](https://github.com/adobe-fonts/source-sans).

By default, only Latin and Latin Extended character sets are included.
Optionally, Cyrillic, Greek and Vietnamese are available in addition to Latin.

To use, import this module from your `config.toml`.

## Latin only

```toml
[module]
[[module.imports]]
path = "github.com/hugo-fonts/source-sans"
```

To enable the font in a template, use `/css/source-sans-latin.css`.

## Cyrillic
```toml
[module]
[[module.imports]]
path = "github.com/hugo-fonts/source-sans/cyrillic"
```

To enable the font in a template, use `/css/source-sans-cyrillic.css`.

## Greek
```toml
[module]
[[module.imports]]
path = "github.com/hugo-fonts/source-sans/greek"
```

To enable the font in a template, use `/css/source-sans-greek.css`.

## Vietnamese
```toml
[module]
[[module.imports]]
path = "github.com/hugo-fonts/source-sans/vietnamese"
```

To enable the font in a template, use `/css/source-sans-vietnamese.css`.
