# LTER SCSS Stylesheets Extension For Quarto

This extension includes light and dark mode SCSS stylesheets consistent with LTER Network colors for Quarto projects. Rules are included in all SCSS files for easy text styling and quality-of-life improvements.

## Installing

```bash
quarto add lter/lter_scss-theme
```

This will install the extension under the `_extensions` subdirectory. If you're using version control, **you will want to check in this directory**.

## Using

Once you've installed the extension, replace your 'theme' specification in the `_quarto.yml` with `_extensions/lter/lter_scss-theme/<theme-name>.scss`. Currently, `<theme-name>` options include:

- `theme_lter-edu-light.scss` - Light mode for educational Quarto content (e.g., workshops, courses, etc.)
- `theme_lter-edu-dark.scss` - Dark mode complement of `theme_lter-edu-light.scss`

## Updating

```bash
quarto update extension lter/lter_scss-theme
```

This will replace the contents of the `lter/lter_scss-theme` subfolder of the `_extensions` folder with whatever is in this repository. Note that if you're using GitHub to deploy your Quarto project, you'll need to commit the changes to the extension files for them to take effect.
