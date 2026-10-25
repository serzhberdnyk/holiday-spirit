# Holiday Spirit

Static RU/EN website for villa management, renovation and long-term rental enquiries in Phuket.

This source snapshot matches the HTML published as Holiday Spirit version 4. All HTML, CSS, JavaScript and visual assets are contained in `index.html`; no dependency installation or build step is required.

## Run locally

Open `index.html` in a browser, or serve this directory:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Then open `http://127.0.0.1:8000`.

## Behaviour

- RU/EN language switching; the language preference is stored only in the browser.
- Eight property-style selection guides, not verified property listings. No live prices or availability are asserted.
- Public WhatsApp links prepare a generic enquiry; visitors decide whether to send it.
- No backend, booking, payment, analytics or automatic message sending.
- The existing `noindex, nofollow` directive is preserved.

For generic static hosting, serve `index.html` directly. Provider-specific deployment metadata is intentionally omitted.

## Visual assets

The photographs and brand artwork are embedded in the existing website source. Their presence here does not grant a separate licence to reuse them.
