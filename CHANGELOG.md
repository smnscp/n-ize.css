# Changes to n’ize.css

## 0.6

### 0.6.1 (May 22, 2023)

- Add space to `div` following blocks.

### 0.6.0 (March 20, 2023)

- Settle on `n-ize.css` for the filename. [NPM does not include symlinks in packages.](https://github.com/npm/npm/issues/3310)

## 0.5

### 0.5.5 (March 20, 2023)

- Give up on fancy character in filename.

### 0.5.3 (October 24, 2022)

- Add `hr` margin.

### 0.5.2 (October 16, 2022)

- Add `figcaption` margin.

### 0.5.1 (October 15, 2022)

- Remove margin from collapsible nested lists.

### 0.5.0 (October 8, 2022)

- Abandon symmetric block margins in favor of [selective top margins](https://alistapart.com/article/axiomatic-css-and-lobotomized-owls/).

## 0.4

### 0.4.1 (October 7, 2022)

- Use outline to paint `hr`.
- Add color slot to `hr`.

### 0.4.0 (October 1, 2022)

- No longer inherit `box-sizing`. Seems more practical to change that behavior just for one element than for a whole element tree.

## 0.3

### 0.3.4 (August 10, 2022)

- Drop selectors for `h1` as subheading. This technique has been [removed](https://github.com/whatwg/html/pull/7829/files#diff-41cf6794ba4200b839c53531555f0f3998df4cbb01a4d5cb0b94e3ca5e23947dL16657-L16660) from [the specs](https://html.spec.whatwg.org/multipage/sections.html#headings-and-outlines).

### 0.3.3 (August 10, 2022)

- Replace `titling` with `heading` in tokens.

### 0.3.2 (July 9, 2022)

- Consolidate font size setting.
- Consolidate line height fix for inline boxes.
- Make `hr` line height neutral.
- Allow `h1` to insist to be top level.

### 0.3.1 (July 1, 2022)

- Prevent list-item markers from blowing up the list-item’s first line in Firefox.

### 0.3.0 (June 8, 2022)

- Remove rules covered by [normalize.css](https://github.com/csstools/normalize.css).

## 0.2

### 0.2.1 (June 5, 2022)

- Use common block margin to help establishing a baseline grid.

### 0.2.0 (June 5, 2022)

- Add generic typography based on custom CSS properties (naming inspired by [Pollen](https://www.pollen.style/)).
- Embrace Firefox’ styling of `h1` in nested sections. (If `h1` is nested there should be a reason, anyways.)

## 0.1

### 0.1.1 (June 4, 2022)

- Clean-up.

### 0.1.0 (June 4, 2022)

- Init _n’ize.css_.
