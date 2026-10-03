# Maanas Retail Billing: installer and updates

This repository holds the **installer** and the **update files** for the Maanas Retail Billing desktop app.
It holds no shop data and no keys.

## Install
Download `Maanas-Retail-Billing-setup.exe` from the latest **Release** and run it. You can install it over an
older copy: your shop records are kept in a separate folder and are not touched.

## Updates
The app has a **Check for updates** button. It reads `latest.json` from the latest Release, downloads the new
version, checks its signature, and asks you to restart. An update that is not signed with the shop's key is
refused.

## For the shop owner: publishing a new version
1. Build the app (the build refreshes the `release` folder next to this file by itself).
2. On GitHub open **Releases -> Draft a new release**. Use a new tag such as `v0.2.1`.
3. Attach every file from the `release` folder and publish.
