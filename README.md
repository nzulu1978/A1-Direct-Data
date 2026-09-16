# A1 Direct Data — Version 1 (FREE)

This phone/GitHub package removes the entire payment system.

## Version 1 flow
Register → Login → Home → LiveScore / Flashscore → Fixtures & Predictions → Prediction History

## Advertising
Version 1 includes a clearly labelled advertising area. The current package uses an offline placeholder so the app still builds without adding an advertising SDK or requiring payment.

A real advertising network (for example Google AdMob) can be connected later when you are ready.

## Removed
- OTT vouchers
- 1Voucher
- Blue Voucher
- Wallet
- Deposits
- Premium subscription

## Build from Android phone using GitHub
1. Create/open your GitHub repository.
2. Upload the contents of this ZIP (not the ZIP itself).
3. Keep the `.github/workflows/build-apk.yml` file in place.
4. Open the repository → Actions.
5. Select **Build A1 Direct Data APK**.
6. Tap **Run workflow**.
7. When it finishes, open the workflow run and download the artifact named **A1-Direct-Data-V1-Free-APK**.
8. Extract the artifact and install `app-debug.apk` on your Android phone.

This is a Version 1 demo with local registration/login and demo fixtures. It does not require a payment provider or internet connection for the core flow.


## Live Scores
The Home screen includes buttons that open LiveScore and Flashscore in the phone's web browser. A1 Direct Data does not copy or scrape their live data.
