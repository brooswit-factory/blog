# Changelog

## 0.1.3

### Changed

- FACTORY-553: the "Under construction" / "Pardon our mess." area now has the same look as the factory homepage's info area: a full-width dark panel (`#16110d`) with the stone border down both edges, flush with the page edge. `assets/border.png` is the exact file from the website repo (30x1402, cropped to the art, palette PNG with full alpha, ~25 KB), tiled `repeat-y`; the left strip is used as is and the right one is mirrored (`scaleX(-1)`). Edge width `clamp(14px,3.4vw,30px)`. The banner, fonts and copy are unchanged.

## 0.1.2

### Changed

- FACTORY-542: dark-fantasy type and new copy. Headings use Cinzel Decorative 700 and body text IM Fell English 400 (SIL OFL, self-hosted latin woff2 in `fonts/` with licenses), replacing Cinzel and EB Garamond (files, `@font-face` and preloads removed). The page now reads "Under construction" (h1) with "Pardon our mess." (h2) under it, replacing "Coming soon"; meta description, `package.json` description and README updated to match.

## 0.1.1

### Changed

- FACTORY-540: the "Coming soon" page uses the new full-width blog image (1600px JPEG, 393K) in place of the factory banner, and matches the factory homepage: Cinzel and EB Garamond (SIL OFL, self-hosted in `fonts/` with licenses) on a dark palette.

## 0.1.0

### Added

- FACTORY-538: "Coming soon" placeholder page for blog.brooswit.nexus. Served by GitHub Pages from `main`; the `CNAME` file sets the custom domain.
