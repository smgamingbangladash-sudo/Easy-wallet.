# Easy Wallet Android starter

This is a starter Android project for the Easy Wallet prototype.

## Build an APK on GitHub (phone-friendly)
1. Upload the contents of this ZIP into the root of your GitHub repository (not the ZIP itself).
2. Commit the files to the `main` branch.
3. Open the repository's **Actions** tab.
4. Select **Build Easy Wallet APK** and press **Run workflow** (or wait for the push build).
5. Open the completed workflow run and download `easy-wallet-debug-apk` under Artifacts.

## Included in this starter
- Basic business-card details saved locally and shareable through Android Sharesheet.
- Document picker for PDFs and images; selected files are copied to the app's private internal storage.
- Saved Smart NFC Link field and Android share action for the saved URL.
- GitHub Actions workflow to build a debug APK.

## Important limitations
- This starter does NOT implement direct phone-to-phone NFC data transfer. Android Beam was deprecated/removed on modern Android; iPhone interoperability requires a different supported flow. The share buttons use Android's standard share sheet.
- No QR generator is included yet.
- No encrypted vault, biometric/PIN lock, cloud sync, bank payment emulation, or official government-ID/passport replacement is included.
- Do not store bank PINs, CVVs, or highly sensitive passwords in this prototype.
- The debug APK is for testing, not Play Store release.
