# BOT Microsite (Knowledge 26)

This microsite is delivered as a single-file build:
- `index.html`

## What’s Included
- Final approved microsite UI/content.
- Working HubSpot embedded form integration.
- Influ2 tracker script integration.

## Integrations

### HubSpot Form
The page includes HubSpot embed script and form container in `index.html`.

### Influ2 Tracker
The following script is already added in `index.html`:

```html
<script async src="https://www.influ2.com/tracker?clid=f9a44c38-1cef-45ba-88eb-e702ea04d6c4"></script>
```

## Deployment
1. Upload `index.html` and the full `images/` folder together.
2. Keep folder paths unchanged (`./images/...`) so assets load correctly.
3. Publish on your hosting environment.

## Local Preview
Open from a local server (recommended), for example:

```powershell
cd "f:\Work\BOT Consulting\BOT Projects\BOT Microsite"
python -m http.server 8000
```

Then open:
- `http://localhost:8000/index.html`

## Notes
- This project is intentionally single-file for easy handoff.
- If any content updates are required, edit `index.html` directly.
