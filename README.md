# css-word-wrap

Functional CSS for word-wrap

## Filesize

| File | Size |
|------|------|
| `dist/word-wrap.css` | 593 bytes |
| `dist/word-wrap.min.css` | 417 bytes (147 Gzipped) |

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
| `.ww-n` | `word-wrap: normal;` |
| `.ww-bw` | `word-wrap: break-word;` |
| `.ww-i` | `word-wrap: inherit;` |
| `.ww-n-s` | `word-wrap: normal;` |
| `.ww-bw-s` | `word-wrap: break-word;` |
| `.ww-i-s` | `word-wrap: inherit;` |
| `.ww-n-m` | `word-wrap: normal;` |
| `.ww-bw-m` | `word-wrap: break-word;` |
| `.ww-i-m` | `word-wrap: inherit;` |
| `.ww-n-l` | `word-wrap: normal;` |
| `.ww-bw-l` | `word-wrap: break-word;` |
| `.ww-i-l` | `word-wrap: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.ww-n-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/word-wrap.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/word-wrap.css` — formatted
- `dist/word-wrap.min.css` — minified

## License

MIT
