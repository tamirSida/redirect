# Re-Direct

A simple redirect webapp that shows a loading spinner and immediately redirects to a configured URL.

## Features

- Clean loading screen with spinner animation
- Instant redirect to configured URL
- No delay between page load and redirect
- Easy configuration via JSON file

## Configuration

Edit `config.json` to change the redirect URL:

```json
{
  "redirectUrl": "https://www.google.com"
}
```

## Development

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to test the redirect.

## Deployment

### Netlify

1. Push this repository to GitHub
2. Connect to Netlify
3. Build command: `npm run build`
4. Publish directory: `out`
5. Deploy

The app will show a loading spinner and immediately redirect users to the URL specified in `config.json`.
