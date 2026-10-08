# BlvdChrg-email-assets

Public images for BlvdChrg email signatures (GitHub Pages).

## Official signature logo (use this one)

https://winsightcounsel.github.io/BlvdChrg-email-assets/blvdchrg-logo-official.png

- BLVDCHRG wordmark, B-bolt mark, tagline "Ultrafast Charging, Drive-Thru Service".
- 360x156 PNG. Show it at width 180px, height auto.
- Approved by Kasra on Oct 7, 2026.

## Retired (do not use in new mail)

- `IMG_2376.jpeg` ("Luxury, Repowered" tagline). Kept only so older sent mail still shows its logo.
- Any "You've Arrived" tagline logo.

## Upload helper

The MCP file tools write text only. To add an image, commit `<name>.b64` (base64 text) to `main`.
The workflow `.github/workflows/decode-b64-assets.yml` decodes it to `<name>` and removes the `.b64` file.
