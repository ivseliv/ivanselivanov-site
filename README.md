# Ivan Selivanov · academic website

Personal academic homepage in English and Russian.

- English: `public/index.html`
- Russian: `public/ru/index.html`
- Academic CV: `public/assets/ivan-selivanov-academic-cv-2026.pdf`
- Separate reading journal: https://blog.ivanselivanov.org/

## Cloudflare Pages deployment

Connect repository `ivseliv/ivanselivanov-site` through Pages Git integration.
Choose **None** for Framework preset, production branch `main`, build command `exit 0`, and build output directory `public`. Do not choose Hugo: these files are already static HTML.

First verify the temporary `*.pages.dev` URL. Then use **Custom domains → Set up a domain** to attach `ivanselivanov.org` from the same Cloudflare account that holds the domain and blog subdomain.

Changes to `public/` pushed to the main branch will trigger automatic deployment.

## Boundaries

Do not copy, overwrite, or modify `ivseliv/plusquamperfect` or `blog.ivanselivanov.org`. This is a separate personal site.
