# avila-bus-web

Static site for the Ávila Bus Android app (`dev.davidjuanes.avilabus`; app repo: GitLab `salamanca-bus/salamanca-bus`, flavor `avila`, spec in its `docs/app-spec.md` §13). Jekyll 4, built by GitHub Actions, served by GitHub Pages at https://avilabus.davidjuanes.dev/ behind Cloudflare. It started as a copy of `salamanca-bus-web` (GitHub `DavidJuanes/salamanca-bus-web`): fixes to the shared layout, CSS or JS usually belong in both. Push straight to `main`; every push deploys.

- **i18n without plugins.** Spanish at `/`, English at `/en/`. Landing texts live in `_data/i18n/{es,en}.yml` and are rendered by `_includes/landing.html`; each page sets `lang` and a shared `ref` so the layout can find its translation (language switch, `hreflang`). Change both languages together. No automatic redirect by browser language.
- **Privacy policy** (`privacidad.md`, `en/privacy.md`) is the URL declared in Play Console. It must match the app's Data safety form (described in the app repo's `docs/play-listing.md`): when the app starts or stops collecting something, update both policies and their `updated` date.
- **`app-ads.txt`** holds the AdMob publisher line (`pub-0847996848911499`). AdMob crawls it from the developer website set in the Play listing.
- **Images** in `assets/img` come from the app repo's `avila` flavor: phone screens recorded with Roborazzi like `AvilaScreenshotTest` (Spanish and `en-rGB`; `nearby-dark-clock` with `ArrivalFormat.CLOCK`), the map from a phone screenshot, the icons and Open Graph images from its launcher icon (teal gradient). Converted to WebP (600 × 1300) with ImageMagick. The gallery shows the Play listing graphics once Ávila has them (`gallery.shots` in `_data/i18n`; empty hides it).
- **Colours** are Ávila's: the teal palette of the app's `src/avila/.../ui/theme/Color.kt` and the pastel line colours of `bus-data-avila` (`_data/lines.yml`), all with dark badge text.
- **No third parties at runtime:** fonts are self-hosted (latin subset, OFL), no analytics, no cookies. The privacy policy says so; keep it true.
- **Motion:** native CSS (scroll-driven animations) and vanilla JS in `assets/js/main.js`; everything stops under `prefers-reduced-motion`.
- The Google Play badge is Google's official image; don't edit it, and keep the trademark line in the footer.
