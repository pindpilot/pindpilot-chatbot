# PindPilot AI

Phase 1 mobile-first chat PWA. Built for GitHub Pages, with local (per-device) chat history, new/delete chat, share/copy, dark/light mode and a Gemini chat endpoint.

**Do not add API keys here or in any browser file.** The front end needs a separately hosted server-side endpoint; replace `__API_ENDPOINT__` in `index.html` with its public URL only after the proxy is tested. Until then the UI intentionally blocks sending and explains that chat is not connected. Never commit `.env`, secrets or tokens.

This is an early prototype, not a private authentication system. A public proxy must have authentication or abuse controls before sharing widely. Chats saved to browser storage do not sync across phones and can be removed by clearing site data. Free Gemini usage and availability depend on Google's current tier and quotas.
