# css-opacity

Functional CSS for opacity

## Filesize

| File | Size |
|------|------|
| `dist/opacity.css` | 1397 bytes |
| `dist/opacity.min.css` | 843 bytes (211 Gzipped) |

## Install

```sh
npm install css-opacity
```

## Usage

### Import

```css
@import "css-opacity";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-opacity/dist/opacity.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-opacity/dist/opacity.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.o-10` | `opacity: .1;` |
| `.o-20` | `opacity: .2;` |
| `.o-30` | `opacity: .3;` |
| `.o-40` | `opacity: .4;` |
| `.o-50` | `opacity: .5;` |
| `.o-60` | `opacity: .6;` |
| `.o-70` | `opacity: .7;` |
| `.o-80` | `opacity: .8;` |
| `.o-90` | `opacity: .9;` |
| `.o-full` | `opacity: 1;` |
| `.o-10-s` | `opacity: .1;` |
| `.o-20-s` | `opacity: .2;` |
| `.o-30-s` | `opacity: .3;` |
| `.o-40-s` | `opacity: .4;` |
| `.o-50-s` | `opacity: .5;` |
| `.o-60-s` | `opacity: .6;` |
| `.o-70-s` | `opacity: .7;` |
| `.o-80-s` | `opacity: .8;` |
| `.o-90-s` | `opacity: .9;` |
| `.o-full-s` | `opacity: 1;` |
| `.o-10-m` | `opacity: .1;` |
| `.o-20-m` | `opacity: .2;` |
| `.o-30-m` | `opacity: .3;` |
| `.o-40-m` | `opacity: .4;` |
| `.o-50-m` | `opacity: .5;` |
| `.o-60-m` | `opacity: .6;` |
| `.o-70-m` | `opacity: .7;` |
| `.o-80-m` | `opacity: .8;` |
| `.o-90-m` | `opacity: .9;` |
| `.o-full-m` | `opacity: 1;` |
| `.o-10-l` | `opacity: .1;` |
| `.o-20-l` | `opacity: .2;` |
| `.o-30-l` | `opacity: .3;` |
| `.o-40-l` | `opacity: .4;` |
| `.o-50-l` | `opacity: .5;` |
| `.o-60-l` | `opacity: .6;` |
| `.o-70-l` | `opacity: .7;` |
| `.o-80-l` | `opacity: .8;` |
| `.o-90-l` | `opacity: .9;` |
| `.o-full-l` | `opacity: 1;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.o-10-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/opacity.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/opacity.css` — formatted
- `dist/opacity.min.css` — minified

## License

MIT
