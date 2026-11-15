# Helper Payslip

Monthly payslip maker for a domestic helper. Runs entirely on your phone:
payslips, history and details are stored on the device only. Nothing is sent anywhere.

Files: index.html (the app), jspdf.umd.min.js (PDF maker), sw.js (offline support),
manifest.webmanifest + icon PNGs (home-screen icon).

## Updating
After changing any file, open sw.js and bump VERSION (payslip-v1 → payslip-v2),
then upload. Phones pick up the new version the next time the app opens online.
