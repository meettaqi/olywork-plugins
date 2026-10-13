# Public vendor listings

Vendor listings describe publicly available integrations. They are discovery metadata, not a
promise that Olywork has a commercial relationship with the vendor or that every endpoint is
available to every team.

## What belongs here

- Vendor name, official HTTPS homepage, and official documentation URL.
- A category such as `search`, `email`, `analytics`, or `storage`.
- The public integration kind and a path to a public manifest or skill.
- Attribution and logo licensing information.

## What must stay out

- API keys, OAuth secrets, access tokens, private endpoints, or customer data.
- Provider contract terms, negotiated rates, internal reliability data, or private catalogs.
- Claims about endpoint counts, pricing, uptime, or authorization unless they are sourced and dated.
- Vendor logos copied without permission or without following the vendor's brand policy.

Each listing must validate against [`schema.json`](./schema.json) and should be reviewed by a
maintainer before release.
