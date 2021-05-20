# Changelog

This changelog aims to document all the high-level changes added by the BBC on top of upstream [sandflow/imscJS 1.1.2](https://github.com/sandflow/imscJS) library.

For more detailed changes, please use the commit history.

## Changes

- Handle TTML1 1st Edition CR ttaf namespace declarations
- Add `options` parameter to `imscHTML.render()` to allow customisation of presentation
- Performance improvements inside `generateISD`. [#6](https://github.com/bbc/imscJS/pull/6)
- Adjacent character spans within the same line are merged together when they came from the same span in the source. [#10](https://github.com/bbc/imscJS/pull/10)
- Prune duplicate resolved font-family property values. [#7](https://github.com/bbc/imscJS/pull/7)
