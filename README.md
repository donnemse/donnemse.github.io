# donnemse.github.io

Support pages and privacy policies for my apps, served by GitHub Pages at https://donnemse.github.io/.

Each app has a folder with `index.md` (support URL `/<app>/`) and `privacy.md` (privacy policy URL `/<app>/privacy/`). Both set `app` and `app_name` in their front matter; the layout builds the navigation and the contact footer from them and from `email` in `_config.yml`.

To add an app: copy a folder, change `app`/`app_name` and the text, and add a row to `index.md`.

URLs given to App Store Connect must keep working. Don't rename a folder of a released app.
