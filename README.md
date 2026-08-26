# MTC NP2900W â€” Firmware Releases

Official firmware release channel for the **MTC NP2900W** mono laser printer
(the **WiFi** model). Releases here are **not** for the MTC NP2900 (USB-only) printer,
which has its own channel; a printer rejects an image built for the other model.

## How to update

Use the **MTC NP2900 Update** Windows application: it detects the printer model, downloads
the matching release from this channel and guides you through the update. Manual route:
hold the PAPER key while powering the printer on, copy `np2900w_update_<version>_ENCRYPTED.bin`
onto the `NP2900W-FW` drive that appears, and wait for the printer to restart.

The `manifest.json` / `manifest.json.sig` files in each release are used by the
application itself (signed version and integrity data); users do not need them.

---
Â© MTC. For warranty inquiries, please contact the place of purchase.