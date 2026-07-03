# intarweb Home Assistant Add-ons

Manifests for intarweb's prebuilt-image HA add-ons. Add this repo's URL in HA →
Settings → Add-ons → Add-on Store → ⋮ → Repositories.

Each add-on here is `image:`-based — HA **pulls** the prebuilt image from `ghcr.io/intarweb/*`
(built in CI from the source fork's `main` + our open upstream PRs, ephemerally). The source
forks (e.g. `intarweb/filament-manager`) stay pure upstream mirrors; branding + version live
here, never on the fork's main. `auto_update: false` — upstream folds are deliberate.
