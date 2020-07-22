# sReality Listings Monitor - For Dummies

Create an input file in a subdirectory of root folder `apify_storage/key_value_stores/default/INPUT.json`:

```json
{
  "location": "Říčany u Prahy, Czechia",
  "offerType": "sale",
  "type": "apartment",
  "proxyConfiguration": {
    "useApifyProxy": false
  }
}
```

Run locally using apify with the following command:

```sh
# credit: [Apify Platform · Apify SDK](https://sdk.apify.com/docs/guides/apify-platform)
apify run -p
```