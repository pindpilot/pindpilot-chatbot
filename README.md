# PindPilot AI

Phase 1 mobile-first chat PWA. Built for GitHub Pages, with local (per-device) chat history, new/delete chat, share/copy, dark/light mode and a Gemini chat endpoint.

**Do not add API keys here or in any browser file.** The front end needs a separately hosted server-side endpoint; the proxy is configured at `https://pindpilot-chat-api.pindpilot.workers.dev/`. Its Gemini key is a Cloudflare secret, never in the browser. Never commit `.env`, secrets or tokens.

This is an early prototype, not a private authentication system. The proxy has a 3-requests-per-minute regional limiter but no per-user authentication. It is for a small pilot, not an abuse-proof public launch. Chats saved to browser storage do not sync across phones and can be removed by clearing site data. Free Gemini usage and availability depend on Google's current tier and quotas.
