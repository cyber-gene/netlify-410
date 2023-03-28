# netlify-410

English / [日本語](README_ja.md)

Use Netlify to return HTTP status code 410 for all accesses.

## NOTICE
Responses to requests other than GET methods will be 404 instead of 410.

If you want to return a response code of 410 strictly for all requests, please consider other methods.

## How to use

### Deploy to Netilfy

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/cyber-gene/netlify-410)

Or manually create a site on Netlify.

1. Fork this repository.
1. Create new site in Netlify.
1. Setting and deploy site. Basic build settings do not need to be set.

### Custom domain setting

1. Custom domain settings in Netlify. And add a record to the DNS server you are using.
1. After adding a record to your DNS, a TLS certificate will be automatically issued and you will be able to communicate over HTTPS.

## Sample site

[![Netlify Status](https://api.netlify.com/api/v1/badges/e5b953ea-0d12-4ec9-8720-6d98dd2153d1/deploy-status)](https://app.netlify.com/sites/sharp-einstein-854dcc/deploys)

Sample site is [here](https://sharp-einstein-854dcc.netlify.app/).

This site will automatically publish main branch.

## Lisence
[MIT License](https://github.com/cyber-gene/netlify-410/blob/main/LICENSE)

## Author
[cybergene](https://github.com/cyber-gene)
