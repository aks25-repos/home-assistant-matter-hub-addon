# Home Assistant Matter Hub Add-on

This is a simple wrapper that allows Home Assistant to run the Matter Hub project by [t0bst4r](https://github.com/t0bst4r/home-assistant-matter-hub) as an add-on.

It always pulls the **latest** container image from GitHub Container Registry:
`ghcr.io/t0bst4r/home-assistant-matter-hub:latest`

## Installation

1. Upload this repo to your own GitHub account.
2. In Home Assistant, go to **Settings → Add-ons → Add-on Store → ⋮ → Repositories** and add your repo link, e.g.  
   ```
   https://github.com/ajay-sharma/home-assistant-matter-hub-addon
   ```
3. The “Matter Hub” add-on will appear.
4. Install, start it, and check logs.

Ensure IPv6 and mDNS are working on your network for proper Matter discovery.
