# robbonner2-cell.github.io

The GitHub Pages user site for the `robbonner2-cell` account, served at
https://robbonner2-cell.github.io/. It holds a small static legal-pages bundle for the owner's
private, single-operator automation tool — named "Hermes Fleet" on these pages — which the landing
page describes as running on the owner's own server and using Google APIs, with explicit consent, to
read and write the owner's own mail, calendar, drive files and spreadsheets. The pages state it is
not a public service, has no sign-up, and is not offered to any third party.

## How to run

There is no build step and no script: GitHub Pages serves the repository root of a
`<user>.github.io` repository as the account's user site. The files are plain HTML with inline CSS
and no scripts, so `index.html` can also be opened directly in a browser. Publishing is a push to
`main`.

## Layout

- `index.html` — landing page: what the tool is, with links to the two policies
- `privacy.html` — privacy policy: what Google data is accessed, how it is used and stored, retention
  and deletion, Limited Use
- `terms.html` — terms of service: private personal use, no warranty, revoking access
- `google8d7739365ece83dc.html` — Google Search Console site-verification file, served as-is

## Not included

- No application source code — this repository is documentation pages only.
- No OAuth client secrets, tokens or account data; the policy pages only point at Google's own
  permission-revocation page.
- No analytics, trackers or third-party scripts.
