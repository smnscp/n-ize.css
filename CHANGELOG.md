# Changes to n’ize.css

### 0.4.0 (October 1, 2022)

- No longer inherit `box-sizing`. Seems more practical to change that behavior just for one element than for a whole element tree.

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

### 0.2.1 (June 5, 2022)

- Use common block margin to help establishing a baseline grid.

### 0.2.0 (June 5, 2022)

- Add generic typography based on custom CSS properties (naming inspired by [Pollen](https://www.pollen.style/)).
- Embrace Firefox’ styling of `h1` in nested sections. (If `h1` is nested there should be a reason, anyways.)

### 0.1.1 (June 4, 2022)

- Clean-up.

### 0.1.0 (June 4, 2022)

- Init _n’ize.css_.
