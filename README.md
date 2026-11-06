# VeniVidiCookie Consent Banner for Google Tag Manager

A Google Tag Manager Community Template (web container) for [VeniVidiCookie](https://venividicookie.com), the EU cookie-consent platform for agencies. It sets Google Consent Mode defaults to denied (basic mode), optionally re-applies a returning visitor's stored choice, and loads the site's consent banner from `cdn.venividicookie.com`.

## Setup

1. Add the template from the Community Template Gallery (Templates, Tag Templates, Search Gallery, "VeniVidiCookie").
2. Create a tag from it and set **Site key** and **Script host** from the VeniVidiCookie dashboard (Install page).
3. Fire it on **Consent Initialization - All Pages**.
4. Keep the built-in consent checks in your Google tags; use Additional consent checks or the `grf_consent_update` dataLayer event for other tags.

## Licence

The template is licensed under Apache-2.0 (see `LICENSE`). The banner script it loads is not part of this template; it is provided under the VeniVidiCookie Terms of Service (https://venividicookie.com/terms).

## Issues

Report problems with the template in this repository's issues. For the banner itself, contact your agency or VeniVidiCookie support.
