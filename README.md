# havensight-site

Public website for the **Havensight** Android game — a simple landing page and the
privacy policy required by Google Play and Google AdMob.

Static HTML/CSS, served via GitHub Pages.

- `index.html` — landing page
- `privacy.html` — privacy policy (the URL referenced by the Play listing and AdMob UMP)
- `style.css` — shared styling

## Live URL

Served via GitHub Pages (Deploy from branch → `main` / root), on the custom
apex domain `havensightgame.com` (Cloudflare DNS, apex CNAME-flattening, HTTPS
enforced):

- Site: https://havensightgame.com/
- Privacy: https://havensightgame.com/privacy.html

(Also reachable at https://markjhunsinger.github.io/havensight-site/, which
canonicalizes to the custom domain.)
