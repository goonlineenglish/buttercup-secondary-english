# Buttercup - LuvKids Landing Page

Cloudflare Pages source for `https://buttercup.edu.vn/luvkids/`.

The registration form posts to `/api/register` and appends submissions to Google Sheet `1x1we6Kdpq1NNbQS1Z2Qpn56dMeVlLSRggqCb78uuMeA`.

Required Cloudflare Pages environment variables:

- `GOOGLE_SERVICE_ACCOUNT_EMAIL`
- `GOOGLE_PRIVATE_KEY`

Share the Google Sheet with the service account email as Editor.
