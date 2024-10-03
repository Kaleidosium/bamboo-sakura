# Bamboo Sakura

A classless CSS library. Forked from [bamboo](https://github.com/rilwis/bamboo), Inspired by [sakura](https://github.com/oxalorg/sakura).

[View demo](https://kaleidosium.github.io/bamboo-sakura/demo/light)

🎋🌸

## Usage

### CDN

#### 🌙 Dark Theme

```html
<link rel="stylesheet" href="https://unpkg.com/bamboo-sakura.css/dist/dark.min.css">
```

#### ☀ Light Theme

```html
<link rel="stylesheet" href="https://unpkg.com/bamboo-sakura.css/dist/light.min.css">
```

#### 🌑 Dark-Solarized Theme

```html
<link rel="stylesheet" href="https://unpkg.com/bamboo-sakura.css/dist/dark-solarized.min.css">
```

#### 💖 Vader Theme

```html
<link rel="stylesheet" href="https://unpkg.com/bamboo-sakura.css/dist/vader.min.css">
```

#### 🌱 Earthly Theme

```html
<link rel="stylesheet" href="https://unpkg.com/bamboo-sakura.css/dist/earthly.min.css">
```

#### ✒️ Ink Theme

```html
<link rel="stylesheet" href="https://unpkg.com/bamboo-sakura.css/dist/ink.min.css">
```

#### 💗 Pink Theme

```html
<link rel="stylesheet" href="https://unpkg.com/bamboo-sakura.css/dist/pink.min.css">
```

#### 💾 Radical Theme

```html
<link rel="stylesheet" href="https://unpkg.com/bamboo-sakura.css/dist/radical.min.css">
```

### NPM

```bash
npm install --save bamboo-sakura.css
```

### Theming

Bamboo Sakura provides the following CSS variables for theming:

```css
:root {
  --b-font-main: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif;
  --b-font-heading: var(--b-font-main);
  --b-font-mono: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;

  --b-blossom: #1d7484;
  --b-fade: #982c61;

  --b-txt: #4a4a4a;
  --b-bg-1: #f9f9f9;
  --b-bg-2: #f1f1f1;
  --b-btn-bg: #4a4a4a;
  --b-btn-txt: #fff;
  --b-focus: #d8dee9;
}
```

All CSS variables are prefixed with `--b-` so it's safe to use Bamboo Sakura with your existing websites.

## Credits

- [bamboo.css](https://github.com/rilwis/bamboo)
- [modern-normalize](https://github.com/sindresorhus/modern-normalize) and [sanitize.css](https://github.com/csstools/sanitize.css)
- [sakura](https://github.com/oxalorg/sakura) for color schemes
