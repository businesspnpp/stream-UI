# stream-UI

Browser viewer for the [`shareStream`](https://github.com/businesspnpp/shareStream) Windows desktop streamer.

Connects to your relay server over `wss://`, receives binary H.264-in-fMP4 chunks, and feeds them into a `<video>` element via the MediaSource Extensions API.

## Use

1. Deploy this folder to Vercel (or open `index.html` locally).
2. Paste your relay URL (e.g. `wss://my-screen-streamer.onrender.com`) into the input.
3. Click **Connect Live Feed**, then start the stream from the Windows tray app.

The last URL is cached in `localStorage` for convenience.
