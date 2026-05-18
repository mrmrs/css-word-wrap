# css-word-wrap

Functional CSS for word-wrap

## Filesize

| File | Size |
|------|------|
| `dist/word-wrap.css` | 581 bytes |
| `dist/word-wrap.min.css` | 405 bytes (146 Gzipped) |

## Install

```sh
npm install css-word-wrap
```

## Usage

### Import

```css
@import "css-word-wrap";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-word-wrap/dist/word-wrap.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-word-wrap/dist/word-wrap.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.wwn` | `word-wrap: normal;` |
| `.wwbw` | `word-wrap: break-word;` |
| `.wwi` | `word-wrap: inherit;` |
| `.wwn-s` | `word-wrap: normal;` |
| `.wwbw-s` | `word-wrap: break-word;` |
| `.wwi-s` | `word-wrap: inherit;` |
| `.wwn-m` | `word-wrap: normal;` |
| `.wwbw-m` | `word-wrap: break-word;` |
| `.wwi-m` | `word-wrap: inherit;` |
| `.wwn-l` | `word-wrap: normal;` |
| `.wwbw-l` | `word-wrap: break-word;` |
| `.wwi-l` | `word-wrap: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.wwn-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/word-wrap.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/word-wrap.css` — formatted
- `dist/word-wrap.min.css` — minified

## License

MIT
