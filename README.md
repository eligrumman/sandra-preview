# Sandra Leifer — site mirror

Mirror of the artist website sandraleifer.com, for networks that block the domain. Published with GitHub Pages at https://eligrumman.github.io/sandra-preview/

The source is [eligrumman/sandra-books](https://github.com/eligrumman/sandra-books). The Pages workflow checks out its `feat/immersive-artist-portfolio` branch, where `portfolio/` links to the site in `dist/`, runs the site checks and publishes it. To refresh after the site changes: bring that branch up to date with `main`, then run Actions → Publish artist preview → Run workflow, or push to this repository's `main`.

Pages source: Settings → Pages → Source: GitHub Actions. No custom domain.

Last refreshed 2026-11-16: the home page's moving wall loads small 480px thumbnails, only for the tiles on screen, each tile shows its colour until the photo arrives, and the gallery below no longer downloads all its large images at once on the iPhone (first wall image on a slow phone network about 5 s instead of about 22 s). Branch feat/immersive-artist-portfolio ae27aea.
