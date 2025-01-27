---
title: Sass Core Features
created: 2021-12-06
eleventyNavigation:
  key: sass
  title: Sass Core Features
  parent: home
---

## Summary

In addition to our work on CSS specifications,
we're also working on new feature proposals and specs
for the [Sass](https://sass-lang.com/) preprocessor.

The priorities right now are:

- Tools for managing new color syntax and multiple color-spaces
- Try/catch syntax, for error handling
- First-class css function calls
- Expanding internal utilities (lists & strings etc)
- URL handling & package management

From a broader perspective,
we believe that Sass can be a foundational tool
for the future of design systems tooling --
and there are many more features to consider along those lines.
For example: importing & exporting JSON data,
such as [design token files][].

[design token files]: https://github.com/design-tokens/community-group

## Our notes

{{ collections.all | eleventyNavigation('sass') | eleventyNavigationToHtml | typogr | safe }}

## Previously…

We we able to fast-track
a proposal for [HWB colors](https://github.com/sass/sass/pull/2835),
since they describe the already-supported sRGB color space.
