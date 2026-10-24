# CLAUDE.md — ringworld site (ring-world.github.io)

Plain Jekyll, built by GitHub Pages straight from `main` (no plugins, no Actions).
Moved here 2026-10-24 from Chris Shi's personal site (czhs/czhs.github.io, where
it lived at /ringworld/ — that path now redirects here). Design history and the
decisions not to undo are in that repo's `docs/claude/ringworld.md` and
`docs/superpowers/specs/2026-08-06-ringworld-design.md`.

- `/` — static landing (banner → blurb → About panel). Copy is verbatim from the
  Luma event; no AI-invented text anywhere on the site.
- `/timer/` — Chris's session timer: setup screen (presets + custom time) →
  fullscreen display with no visible controls (click/space pause, dbl-click/Esc
  end). State + log in localStorage. Unlisted (`noindex`).
- `_includes/ringworld_styles.liquid` is the whole stylesheet; light mode only.
- Local preview: `JEKYLL_NO_BUNDLER_REQUIRE=true jekyll serve`.
