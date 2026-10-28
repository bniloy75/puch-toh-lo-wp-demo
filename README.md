# Puch Toh Lo — WordPress demo

A client-review WordPress theme for Puch Toh Lo (formerly The Healing Room).

- **Live demo:** open the WordPress Playground link shared with the client. WordPress runs entirely in the browser; nothing is hosted and nothing is saved to a server.
- **What is editable:** Experts, Circles & events, and Conversations are WordPress content types with normal admin screens, featured images and custom fields.
- **What is not built yet:** the support / community / practitioner forms and RSVP are presentation-only in this demo. They validate and show a confirmation, but do not send anything.

## Files

- `blueprint.json` — WordPress Playground setup: installs and activates the theme, which seeds the sample content on activation.
- `puch-toh-lo.zip` — the theme itself (classic PHP theme, PHP 7.4+).

## Run it yourself

Paste this into a browser:

```
https://playground.wordpress.net/?blueprint-url=https://raw.githubusercontent.com/bniloy75/puch-toh-lo-wp-demo/main/blueprint.json
```

Or upload `puch-toh-lo.zip` to any WordPress site under **Appearance → Themes → Add New → Upload Theme**, then activate it. Activation seeds the sample experts, circles, conversations and the Ask / About pages.

## Notes

All names, credentials, fees, dates and capacities are sample content for design review. They are not real practitioner listings. The theme stores no personal data.
