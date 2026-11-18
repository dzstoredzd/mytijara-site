# MyTijara website

Public website for MyTijara (تجارتي), served by GitHub Pages at
`https://yousoft.site/mytijara-site/`.

Pages in Arabic, French and English. No trackers, no external fonts.

## Pages needed before the first Play release

- [x] `privacy.html`: privacy policy (Play requires its URL). Must cover the account
      (email, Google sign-in), the shop data stored on MyTijara's server for Cloud Sync,
      Google Play subscriptions, analytics and crash reports.
- [x] `terms.html`: terms of use, subscription renewal and cancellation (through Google Play).
- [x] `delete-account.html`: how to delete the account and the shop's data. Play requires
      this URL for every app where users create an account. The app opens `#request`.
- [x] `pricing/`: free plan and subscription plans (prices come from Google Play per
      country, no prices printed). The app opens it as `pricing/?lang=ar|fr|en`.
- [x] `windows/`: Windows page. Download says "coming soon" and links the releases page of
      `dzstoredzd/mytijara-releases`; add the real installer link when it exists.

Store Soft's pages (`dzstoredzd/store-soft-site`) and Doukkany's (`dzstoredzd/doukkany-site`)
can be used as models, but their texts describe offline use and pay-once licences: rewrite,
don't copy.

## Domain

Not chosen. `mytijara.com` was not checked. Add a `CNAME` file only when the domain is set.
