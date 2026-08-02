# BHM Action Sports Schedule Pages

Public GitHub Pages website for BHM Action Sports Schedule.

## Publish after App Store approval

The homepage is intentionally prepared for the app's review period. After Apple approves the application:

1. In `index.html`, search for `APP_STORE_LAUNCH` and replace the status text `App Store review in progress` with `Available now.`
2. At the next `APP_STORE_LAUNCH` comment, replace the disabled `<span>` CTA with an `<a>` that uses the final App Store URL and retains the `button` styling. Do not add a URL until Apple supplies the final listing.
3. Add the final App Store QR code near the availability CTA. Store the local image in `assets/images/`, include descriptive alternative text, and set explicit `width` and `height` attributes.
4. Test the final App Store link on both mobile and desktop, including the installed App Store handoff on an iPhone.
5. Confirm the registered public URLs remain unchanged and load successfully:
   - `https://212hog.github.io/bhm-action-sports-schedule-pages/support/`
   - `https://212hog.github.io/bhm-action-sports-schedule-pages/privacy/`

Do not add a TestFlight link unless one is explicitly supplied later.
