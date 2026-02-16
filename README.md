# css-opacity

Functional CSS for opacity

## Filesize

| File | Size |
|------|------|
| `dist/opacity.css` | 6089 bytes |
| `dist/opacity.min.css` | 3969 bytes (595 Gzipped) |

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
| `.o0` | `opacity: 0;` |
| `.o1` | `opacity: .025;` |
| `.o2` | `opacity: .05;` |
| `.o3` | `opacity: .1;` |
| `.o4` | `opacity: .2;` |
| `.o5` | `opacity: .3;` |
| `.o6` | `opacity: .4;` |
| `.o7` | `opacity: .5;` |
| `.o8` | `opacity: .6;` |
| `.o9` | `opacity: .7;` |
| `.o10` | `opacity: .8;` |
| `.o11` | `opacity: .9;` |
| `.o12` | `opacity: 1;` |
| `.o0-s` | `opacity: 0;` |
| `.o1-s` | `opacity: .025;` |
| `.o2-s` | `opacity: .05;` |
| `.o3-s` | `opacity: .1;` |
| `.o4-s` | `opacity: .2;` |
| `.o5-s` | `opacity: .3;` |
| `.o6-s` | `opacity: .4;` |
| `.o7-s` | `opacity: .5;` |
| `.o8-s` | `opacity: .6;` |
| `.o9-s` | `opacity: .7;` |
| `.o10-s` | `opacity: .8;` |
| `.o11-s` | `opacity: .9;` |
| `.o12-s` | `opacity: 1;` |
| `.o0-m` | `opacity: 0;` |
| `.o1-m` | `opacity: .025;` |
| `.o2-m` | `opacity: .05;` |
| `.o3-m` | `opacity: .1;` |
| `.o4-m` | `opacity: .2;` |
| `.o5-m` | `opacity: .3;` |
| `.o6-m` | `opacity: .4;` |
| `.o7-m` | `opacity: .5;` |
| `.o8-m` | `opacity: .6;` |
| `.o9-m` | `opacity: .7;` |
| `.o10-m` | `opacity: .8;` |
| `.o11-m` | `opacity: .9;` |
| `.o12-m` | `opacity: 1;` |
| `.o0-l` | `opacity: 0;` |
| `.o1-l` | `opacity: .025;` |
| `.o2-l` | `opacity: .05;` |
| `.o3-l` | `opacity: .1;` |
| `.o4-l` | `opacity: .2;` |
| `.o5-l` | `opacity: .3;` |
| `.o6-l` | `opacity: .4;` |
| `.o7-l` | `opacity: .5;` |
| `.o8-l` | `opacity: .6;` |
| `.o9-l` | `opacity: .7;` |
| `.o10-l` | `opacity: .8;` |
| `.o11-l` | `opacity: .9;` |
| `.o12-l` | `opacity: 1;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.o0-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/opacity.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/opacity.css` — formatted
- `dist/opacity.min.css` — minified

## License

MIT
