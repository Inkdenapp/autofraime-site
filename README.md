# autofraime-site

Public website for AUTOFRAIME: home page, Privacy Policy, Terms of Service and
Support. Plain HTML and CSS, no build step, designed for GitHub Pages.

- `/privacy/` and `/support/` are the URLs App Store Connect asks for.
- The app links to these through `AppConfig.websiteBase` in the app repo.
  When a custom domain is connected, change that one value and add a `CNAME`
  file here containing the domain.
- Kept separate from the app repo on purpose: the app repo must stay private,
  and GitHub Pages on a private repo needs a paid plan.

Preview locally: `python3 -m http.server 8790` then open http://localhost:8790
