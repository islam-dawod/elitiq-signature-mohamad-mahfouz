# Elitiq Group — Email Signature (Mohamad Mahfouz)
Mohamad Mahfouz · UBO · MohamadMahfouz@elitiq.com · Pill-strokes variant · 600 × 200 px

## Files
```
signature.html         relative image paths (reference)
signature-ready.html   absolute GitHub Pages image URLs — paste-ready for Outlook/Gmail
images/                logo-01, chip-light (UBO), icon-01, deco-01
```

## Use in Outlook / Gmail
1. Open **signature-ready.html** in Chrome.
2. Select the signature, copy (Ctrl+C).
3. Paste into Outlook › Settings › Mail › Signatures (or Gmail › Settings › Signature).
4. Send a real test email to yourself and open it to confirm images load.

Email-safe: table layout, inline CSS only, no flex/grid/position, no JS, no base64.
All shapes (chip, decoration, icon, logo) are images — identical render in Outlook desktop.

## Notes
- Title chip is an **image** (`chip-light.png`) reading "UBO", rendered in Urbanist to match the
  brand chip (mint → white → pink gradient, soft shadow). The chip is sized to the short title (73 × 42).
- Keep total width at 600 px; don't scale images in CSS.
