# UK mileage rates feed

Signed HMRC approved mileage allowance payment (AMAP) rates, used by the Mileage tracker app to stay
current without an app update.

- `rates.json`: rates by vehicle type and the date they apply from.
- `rates.json.sig`: an ECDSA P-256 / SHA-256 signature of `rates.json`, base64-encoded. The app refuses
  any file whose signature doesn't match the public key built into it.

Source: [GOV.UK — Travel: mileage and fuel rates and allowances](https://www.gov.uk/government/publications/rates-and-allowances-travel-mileage-and-fuel-allowances).

These figures are for convenience, not tax advice. Check GOV.UK before relying on them.
