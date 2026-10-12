# Pixel IPTV authentication callback

Trakt registration redirect: https://karaman85.github.io/pixel-auth/callback/

Static landing page and Apple associated-domain file only. No OAuth tokens, client secret or IPTV credentials. This page does not perform token exchange. Pixel IPTV must initiate OAuth with PKCE and verify state before accepting a callback. AASA hosting and device association require validation; publication alone does not prove universal-link delivery.
