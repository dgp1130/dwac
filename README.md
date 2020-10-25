# Devel without a Cause

[![Netlify Status](https://api.netlify.com/api/v1/badges/5e6d16da-9fcd-435b-ac5f-512e28de03ef/deploy-status)](https://app.netlify.com/sites/dwac/deploys)

This repo hosts the root https://dwac.dev/ domain. Currently this is just a
redirect to https://blog.dwac.dev/. In the future, if other subdomains are used,
this may redirect to https://www.dwac.dev/ which may provide a top-level home
page for all resources hosted on `*.dwac.dev`.

## Deployments

Run `npm run deploy-test ${someAlias}` to deploy a test instance to
`${someAlias}--dwac.netlify.app`.

Run `npm run deploy-prod` to deploy to prod.

Either may ask to login and confirm the site being deployed to. Use the site ID
from [Netlify](https://app.netlify.com/sites/dwac/overview) if necessary.
