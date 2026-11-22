# Shadowmon Digivice

A mobile-first, installable PWA prototype for your custom Digimon, Shadowmon.

## Run it
1. Extract the ZIP.
2. Upload `index.html`, `manifest.webmanifest`, and `sw.js` to the root of a GitHub repository.
3. In GitHub, open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Open the published Pages URL in Chrome on Android. Use Chrome's menu → **Add to Home screen** / **Install app**.

## Included
- Shadowmon identity, mood, stats and personality settings
- Local chat personality engine and conversation history
- Local memory bank saved in browser storage
- Training, exploration, simulated battles and XP/levels
- Bond and trait development
- Rookie → Champion → Ultimate progression plus a dark evolution route
- Voice input (browser support required) and text-to-speech
- Export/import save file
- Offline caching after first successful load

## Important AI limitation
This build is a complete playable companion prototype, but its dialogue brain is a local rule-based engine, not a large language model. It can use saved memories and traits in its replies, but it does not independently learn language like ChatGPT. A genuinely generative AI brain requires connecting a secure backend to an AI model. **Do not put a private API key in `index.html` or any public GitHub repository.** The next engineering upgrade is a small authenticated server endpoint that keeps the key private and sends relevant memories/personality to the model.

## Data
The save is stored in this browser on this device. Export the JSON save regularly. Clearing browser site data can erase the local save.
