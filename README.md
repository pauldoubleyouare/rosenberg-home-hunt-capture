# Rosenberg Home Hunt — capture form

Public front door for the Mini-hosted listing pipeline. Paste a Zillow/Compass
URL or a plain address + the family PIN, and it POSTs to the Hermes listing
lane (`intel.bates/listing`, built in `bates-intel`/`bates-mini`) — no need to
open the full app.

Split out from the main `rosenberg-home-hunt` repo (now private) because free
GitHub plans don't support Pages on private repos. This repo holds nothing but
this one static page — no app code, no secrets.

Deploys via GitHub Actions on push to `main`, once Settings → Pages → Source
is set to "GitHub Actions" (one-time, can't be done from a workflow file).
