# A1 Direct Data — Version 1

Android starter app implementing:
- Registration / login (local demo)
- Wallet balance
- OTT Voucher, 1Voucher and Blu Voucher deposit screens
- Fixture list with deterministic demo predictions
- Prediction history stored locally
- GitHub Actions APK build

## Demo voucher
Use `TEST100` in any voucher deposit screen to simulate a R100 deposit.

## Production payment integration
The app intentionally does NOT process real voucher PINs. Real OTT/1Voucher/Blu Voucher redemption must be performed by an authorised payment provider/backend. Keep provider API keys and merchant credentials on the server, never inside the APK.

1Voucher states that businesses integrate through its APIs and business account. OTT provides merchant/payment integration options. Blu Voucher is available through payment integrations such as BR-DGE. Verify commercial terms, KYC/AML, gambling licensing requirements (if applicable), and settlement arrangements before enabling real-money deposits.
