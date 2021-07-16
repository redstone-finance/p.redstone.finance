# p.redstone.finance

Promotional landing pages for RedStone. Hosted on GitHub Pages.

## All pages
To see the full list of available pages open this link in browser: [p.redstone.finance/sitemap.html](https://p.redstone.finance/sitemap.html).

## Production deploy
To update the website on production simply commit and push changes to the `main` GitHub branch.
Github will automatically compile the code to pure HTML/CSS/JS and host it on its servers. The updated website will be available at https://p.redstone.finance.

## Build HTML
The following command builds the website to the `./_site` folder.
<br />
Note! There is no need to build HTML, because GitHub pages do it automatically.
```sh
jekyll build
```

## Run locally
After running the following command the website should be served at `http://localhost:4000`.
```sh
bundle exec jekyll serve --host 0.0.0.0
```
