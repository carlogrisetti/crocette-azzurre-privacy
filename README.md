# Crocette Azzurre — Privacy policy

Public source of the Privacy policy page for **Crocette Azzurre**, the Android
app that simulates the Lombardy certification exam for sanitary emergency
(118) volunteers. This repository exists only to publish the page through
GitHub Pages; the application itself lives in a private repository.

Published at: <https://carlogrisetti.github.io/crocette-azzurre-privacy/>

That URL is the one linked from the app's About screen and entered in the
Play Console.

- `index.html` — the page itself (Italian, self-contained: no scripts, no
  external assets, no analytics).

To change the policy: edit `index.html` and push — GitHub Pages redeploys
within about a minute. If the URL itself ever changes, update the app's
`privacyPolicyUrl` constant in `lib/src/backend/models.dart` as well.
