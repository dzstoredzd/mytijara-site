# MyTijara website

Public website for MyTijara (تجارتي), served by GitHub Pages (not turned on yet).

Today it has only a "coming soon" home page in Arabic, French and English.

## Pages needed before the first Play release

- [ ] `privacy.html`: privacy policy (Play requires its URL). Must cover the account
      (email, Google sign-in), the shop data stored on MyTijara's server for Cloud Sync,
      Google Play subscriptions, analytics and crash reports.
- [ ] `terms.html`: terms of use, subscription renewal and cancellation (through Google Play).
- [ ] `delete-account.html`: how to delete the account and the shop's data. Play requires
      this URL for every app where users create an account.
- [ ] `pricing/`: subscription plans (prices come from Google Play per country).
- [ ] `windows/`: Windows download page, linking to `dzstoredzd/mytijara-releases`.

Store Soft's pages (`dzstoredzd/store-soft-site`) and Doukkany's (`dzstoredzd/doukkany-site`)
can be used as models, but their texts describe offline use and pay-once licences: rewrite,
don't copy.

## Domain

Not chosen. `mytijara.com` was not checked. Add a `CNAME` file only when the domain is set.
