# typst-letter-bpost

Letter template respecting bpost's address position rules

## Local package installation

To use version _0.0.1_ of the package locally, either you import the package directly from your filesystem (the standard `#import`), or you need to install the package locally:

1. Execute `mkdir -p {data-dir}/typst/packages/bpostletter/0.0.1`
   - `$XDG_DATA_HOME` or `~/.local/share` on Linux
   - `~/Library/Application Support` on macOS
   - `%APPDATA%` on Windows
1. Execute `mkdir -p {data-dir}/typst/packages/bpostletter/0.0.1/src/main/typst`
1. Execute `cp src/main/typst/bpostletter.typ {data-dir}/typst/packages/bpostletter/0.0.1/src/main/typst/bpostletter.typ`
1. Execute `cp typst.toml {data-dir}/typst/packages/bpostletter/0.0.1/typst.toml`

## Template file / example document

A template is provided: `src/template/typst/main.typ`

## References

- https://www.bpost.be/sites/default/files/commercial/addressing/Documentation_Belgian_Template.pdf
- https://www.bpost.be/fr/legislation-liee-aux-adresses
- https://www.bpost.be/fr/tout-sur-les-adresses
- https://www.bpost.be/fr/adressage
- https://www.bpost.be/fr/legislation-liee-aux-adresses
