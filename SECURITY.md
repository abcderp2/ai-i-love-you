# Security and privacy

AI I Love You is a static GitHub Pages site designed to minimize attack surface and data collection.

## Security design

- No JavaScript or executable client-side application code
- No forms, authentication, accounts, database, API, or server-side processing
- No third-party assets, embeds, frames, analytics, advertisements, or external fonts
- A restrictive Content Security Policy is declared in the HTML
- No repository secrets or runtime credentials are required
- Dependencies and package managers are intentionally absent

## Privacy design

The site does not intentionally collect, store, profile, or transmit visitor information. It contains no cookies, tracking pixels, fingerprinting code, or analytics scripts.

GitHub Pages is the hosting provider. Network and operational information may be processed by GitHub independently of this site's source code and under GitHub's own policies. For that reason, this project describes its own design as data-minimizing rather than making an absolute claim about the entire hosting infrastructure.

## Reporting a problem

Please open a GitHub issue in this repository without including private, personal, credential, or exploit-sensitive information. For sensitive reports, use a private GitHub security advisory if that feature is enabled for the repository.

## Maintenance guidance

Keep the site static. Avoid adding scripts, forms, external resources, trackers, secrets, generated dependencies, or user-submitted content unless their security and privacy effects have been reviewed first.
