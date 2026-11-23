<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=160&section=header&text=laircronos&fontSize=50&fontColor=fff&animation=fadeIn&fontAlignY=38&desc=LAIR%20on%20Cronos%20WebSite&descAlignY=60&descSize=14" width="100%"/>

<img src="https://skillicons.dev/icons?i=html,css,js&theme=dark" alt="Tech stack"/>

</div>

# laircronos

LAIR on Cronos WebSite

## Serving the site

The production document root is `site/`. The homepage, roadmap and tokenomics pages are hand-authored HTML with static assets. A checkout is sufficient to reproduce the distributed files. Run `sha256sum -c production.sha256` from the repository root, then `python3 -m http.server 8000 --bind 127.0.0.1 --directory site` for a local preview.

## Licensing

Licensing scope and preserved third-party permissions are documented in [LICENSING.md](LICENSING.md). The [0xfunboy Non-Commercial License](LICENSE.md) covers eligible original material only.
