---
title: Privacy Policy
---

# MediPilot Lite: Privacy Policy

**Publisher:** Asklepios Consulting Oy (Business ID 3245307-1), IoT Campus, Joensuunkatu 7, FI-24100 Salo,
Finland, asklepiosconsultingoy@gmail.com, +358 44 013 0683
**Applies to:** the Chrome extension "MediPilot Lite" (Chrome Web Store; the item ID will be added here after
publication)
**Version:** 1.0, effective 23 October 2026
**Suomeksi:** [Tietosuojaseloste](tietosuojaseloste) (the Finnish text is the authoritative version)

**MediPilot Lite** is a Chrome extension published by Asklepios Consulting Oy for physicians who use the
Mehidoc patient record system at mehidoc.mehilainen.fi. It is an independent tool and not a product of
Mehiläinen Oy.

- **All processing happens locally in the user's browser.** The extension does not transmit any data to the
  publisher or to any third party. It contains no analytics, telemetry, advertising or remote code.
- **What it reads (in memory only):** the open Mehidoc page state (conversation messages, prescriptions,
  patient and practitioner identifiers, the user's own session token) to anonymise copied text, assist with
  prescription renewals and compute the user's own fee. Nothing from this is stored.
- **What it stores (on the user's device only):** billing codes of the user's own records for 120 days, the
  user's daily goal numbers for 30 days, imported shift hours for 4 months, widget settings, and an error log
  of at most 50 entries without patient data. No patient names, personal identity codes or record text are
  stored. Billing rows carry Mehidoc's internal conversation number, so they are pseudonymous health data
  and never leave the device.
- **Only network request:** when the user presses "take next", the extension sends the same request to
  Mehidoc's own API that Mehidoc's own button sends, using the user's own session token.
- **Writes:** anonymised text goes to the user's clipboard only on the user's Alt+X. The renewal assistant
  clicks Mehidoc's own buttons and fills in a record note only after the user arms it, stops at a checkpoint,
  and the user confirms and signs with their own PIN. Version 1.0.0 contains only the anonymised copy; this
  policy already covers the features of version 1.1.0.
- **Roles:** Mehiläinen Oy is the controller of the patient data in Mehidoc. The publisher receives no data
  from the extension.
- **Your choices:** removing the extension deletes all stored data. Requests concerning patient data should
  be addressed to Mehiläinen Oy.
- **Limited use:** data is used only for the extension's stated purpose. It is never sold, used for
  advertising or made readable to humans.
- **Changes:** this policy is updated before any new data flow, stored data type or browser permission is
  released. The extension's [changelog](changelog) lists every release.

Contact: Asklepios Consulting Oy, asklepiosconsultingoy@gmail.com, +358 44 013 0683
