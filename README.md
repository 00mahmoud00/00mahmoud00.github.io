# 00mahmoud00.github.io

## Enable HTTPS for `mahmoudsharabati.me`

This repository already has a `CNAME` file, which is required for a custom domain on GitHub Pages.

To enable HTTPS:

1. In GitHub, open this repository and go to **Settings → Pages**.
2. Ensure the custom domain is set to `mahmoudsharabati.me`.
3. Wait for GitHub Pages to provision the TLS certificate (can take a few minutes up to 24 hours).
4. Enable **Enforce HTTPS** in the Pages settings.

If **Enforce HTTPS** is disabled/grayed out, verify DNS first:

- For apex domain (`mahmoudsharabati.me`), point DNS to GitHub Pages IPs:
  - `185.199.108.153`
  - `185.199.109.153`
  - `185.199.110.153`
  - `185.199.111.153`
- Keep the `CNAME` file in this repository with `mahmoudsharabati.me`.
