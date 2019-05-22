# CSSS A11y Plugin

Accessibility plugin for [CSSS slide deck framework](https://github.com/LeaVerou/CSSS).

## What does it do?

- Resets focus indicator to be visible on `Tab` key press
- Removes `outline` on slide focus
- Includes CSS helper classes
- Sets `role` for each slide for semantic context
- Sets `aria-roledescription` for each slide for extra context
- Sets `aria-label` for each slide to provide an accessible name
- Outputs a link list for keyboard controls to load previous and next slides
- Shifts focus to slide content container on link click

## Usage

### CSS

Place `plugin.css` file in `css/plugins/a11y` directory and include in `head` section of Slides document.

```html
<link rel="stylesheet" href="framework/css/a11y/plugin.css">
```

### JavaScript

Place `plugin.js` file in `scripts/plugins/a11y` directory and include before closing `body` element of Slides document.

```html
<script src="framework/scripts/plugins/a11y/plugin.js"></script>
```

## Browser support

* Chrome
* Edge
* Firefox
* Internet Explorer 10+
* Safari
* Opera

## License

This project and its source code is licensed under the [MIT](LICENSE.txt) license.
