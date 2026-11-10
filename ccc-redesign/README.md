# CCC Homepage Redesign

An unofficial redesign concept of the [Clearwater Central Catholic High School](https://www.ccchs.org/) homepage: a simpler layout in the school's red, gold and white, with the same pages, events, news and links as the official site.

This is a student design project and is not affiliated with or endorsed by CCCHS. Photos, logos and written content belong to Clearwater Central Catholic High School.

## Files
- `index.html` – the whole page (HTML, CSS and a little JavaScript, no build step)
- `img/` – compressed copies of the photos and logos from ccchs.org

## Deploying to Cloudflare Pages
1. Push this folder to a GitHub repository.
2. In Cloudflare, go to **Workers & Pages → Create → Pages → Connect to Git** and pick the repository.
3. Leave the framework preset as **None**, the build command empty, and the output directory as `/`.
4. Deploy. Every push to `main` will redeploy the site.
