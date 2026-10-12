# Pixel IPTV authentication callback

Trakt registration redirect: https://karaman85.github.io/pixel-auth/callback/

Static landing page and Apple associated-domain file only. No OAuth tokens, client secret or IPTV credentials. This page does not perform token exchange. Pixel IPTV must initiate OAuth with PKCE and verify state before accepting a callback. AASA hosting and device association require validation; publication alone does not prove universal-link delivery.

Verified callback HTTPS response: HTTP 200. Root AASA is published at https://karaman85.github.io/apple-app-site-association. Apple rejected Associated Domains for the Personal Team signing account. The entitlement remains staged in PixelApple/Configuration/PixelIPTV.entitlements and is not enabled. Restored device build passed. Universal-link delivery and Trakt OAuth are not complete; Client ID is still needed. The static page is not a working login system.
