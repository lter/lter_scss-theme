# LTER SCSS Stylesheets Extension For Quarto

This extension includes custom light and dark mode SCSS stylesheets for Quarto projects. Rules are included in both for easy text styling and quality-of-life improvements.

This will be updated regularly as new types of products are produced by the LTER Network so check back periodically for updates!

## Installing

```bash
quarto add lter/lter_scss-theme
```

This will install the extension under the `_extensions` subdirectory.
If you're using version control, **you will want to check in this directory**.

## Using

Once you've installed the extension, replace your 'theme' specification in the `_quarto.yml` with `_extensions/lter/lter_scss-theme/<theme-name>.scss`.

Currently, `<theme-name>` options include:

- `theme_lter-edu-light.scss` - Light mode for educational Quarto content (e.g., workshops, courses, etc.)
- `theme_lter-edu-dark.scss` - Dark mode complement of `theme_lter-edu-light.scss`
