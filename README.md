# Crocette Azzurre — Privacy policy

Public source of the Privacy policy page for **Crocette Azzurre**, the Android
app that simulates the Lombardy certification exam for sanitary emergency
(118) volunteers. This repository exists only to publish the page through
GitHub Pages; the application itself lives in a private repository.

Published at: <https://carlogrisetti.github.io/crocette-azzurre-privacy/>

That URL is the one linked from the app's About screen and entered in the
Play Console.

- `index.html` — the privacy policy itself (Italian, self-contained: no
  scripts, no external assets, no analytics).
- `cancella-account/index.html` — the Play-required account-deletion page
  (Italian + short English section), published at
  `<https://carlogrisetti.github.io/crocette-azzurre-privacy/cancella-account>`.
  This URL is entered in the Play Console Data safety form and linked from
  policy §10 — keep it stable forever.

To change a page: edit the HTML and push — GitHub Pages redeploys within
about a minute. If the policy URL itself ever changes, update the app's
`privacyPolicyUrl` constant in `lib/src/backend/models.dart` as well.
