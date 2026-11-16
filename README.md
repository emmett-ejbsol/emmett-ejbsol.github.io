# EJB Solutions website

A responsive, static starter site for a data science consulting business. It is built with plain HTML and CSS and can be hosted free with GitHub Pages.

## Preview locally

Open `index.html` in a browser, or start a local server from this directory:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Publish with GitHub Pages

This repository is named `emmett-ejbsol.github.io`, so it can be published as a user site. In the repository's **Settings → Pages**, choose the `main` branch and the root (`/`) folder as the publishing source. The root `CNAME` file is set to `ejb.solutions`.

For the custom domain to resolve, configure DNS with your domain provider. For an apex domain, GitHub Pages documents the required A/AAAA records; for a `www` subdomain, use a CNAME pointing to `emmett-ejbsol.github.io`. See GitHub's current [custom domain documentation](https://docs.github.com/pages/configuring-a-custom-domain-for-your-github-pages-site) for exact records and setup details. DNS propagation and HTTPS provisioning can take some time. Once the domain is verified and serving, enable **Enforce HTTPS** in Pages settings.

## Before launch

- Replace `hello@ejb.solutions` in `index.html` if you want to use another contact address.
- Review the service descriptions and About text to ensure they accurately represent your business.
- Add your own real client examples or testimonials only when you have permission to publish them.

## Files

- `index.html` — page content and metadata
- `styles.css` — responsive visual design
- `CNAME` — GitHub Pages custom domain