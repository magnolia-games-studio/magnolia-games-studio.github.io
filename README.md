# Magnolia Games Studio — static files

GitHub Pages publishes `main` from `/`. No dependencies or build step.

- Developer website: https://magnolia-games-studio.github.io/
- AdMob authorization: https://magnolia-games-studio.github.io/app-ads.txt
- Privacy notice: https://magnoliablocks.com/privacy

Custom domain: `magnoliablocks.com`. Short links `/country`, `/troll` and
`/mine` lead to the corresponding Google Play listings. GitHub Pages first
normalizes a directory URL to its trailing-slash form; each page then replaces
the browser location, with an immediate meta-refresh and clickable fallback.
No tracking scripts, user input or query parameters are forwarded.
The privacy notice is served at `/privacy`; `/privacy.html` forwards there for
existing app versions. `app-ads.txt` remains at its original path. GitHub Pages
also forwards the original github.io domain to this custom domain.

Porkbun's apex ALIAS must point to `magnolia-games-studio.github.io`.
Do not alter MX, SPF, DKIM, Zoho/Google verification, certificate TXT records,
email bounce records, or nameservers when changing web hosting.

The app-ads.txt entry is the exact publisher line supplied by the owner.
No credential belongs in this repository.

Before submitting the Android release, add the approved private support/privacy
email, confirm the audience and advertising-consent configuration, and review
the notice against each app and its Play Data safety form. This generic notice
is not a claim of release compliance.
