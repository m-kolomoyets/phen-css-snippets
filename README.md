# Phenomenon CSS Snippets
---

Here are common-use Phenomenon.Studio-style snippets to use in different projects.

> All snippets are in 2 versions:
> - Plain CSS
> - Tailwind.css

## Snippets enabled:
- Resetting default styles (and adding some custom ones)
- Focus states classes (default, within, direct focus)
- Custom scrollbar styles
- Visually hidden element styles
- Flex-wrappable content with gaps are supported where `gap` or `flx-gap` style is not supported yet (Safari 14 hello XD)[1]
- Lock document scroll

> [1] NOTE: **Flex-wrappable content with gaps** styles are actual while `Safari v14` and `Safari for iOS v14` do not support `gap` and `flx-gap` feature.  
> P.S. For further details look [here](https://caniuse.com/?search=flex-gap)

## Table of snippets

| Snippet name | Plain CSS | Tailwind CSS |
|-|-|-|
|reset.css |✅ |✅|
|focus states |✅ |✅|
|custom scrollbar |✅ |✅|
|flexbox wrap with gaps|✅ |✅|
|lock document scroll y |✅ |✅|