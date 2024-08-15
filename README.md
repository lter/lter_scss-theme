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

## Updating

If you're already using this extension and want to take advantage of any updates we make here, simply run the relevant Quarto command to get the new stylesheets in your project. Command is `quarto update extension lter/lter_scss-theme`.

Note that if you're using version control to deploy your Quarto project you'll need to commit the changes to the extension files for them to take effect in the "live" version of your project.

We'll continue to make extensive use of the `NEWS.md` file and GitHub's release system so documentation of version-to-version changes should be clear.
