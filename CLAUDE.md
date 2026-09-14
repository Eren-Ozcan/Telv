# Telv

## Store / Marketing Visuals

Marketing visuals such as the store listing, feature graphic, icon and
screenshots are **never committed to this public repo**. They are saved in two
places:

1. Local, gitignored copy: `docs/store-assets-originals/`.
2. Private backup repo: `C:\Projects\pictures\Telv\` (local clone of the private
   `Eren-Ozcan/pictures` repo) — copy them there and commit+push in that repo.

## Licensing

This repo is proprietary: the root `LICENSE` is an all-rights-reserved notice
(copyright Yilk Games), and GitHub therefore reports no open-source license.
Never replace it with MIT or any other permissive licence, and never leave a
scaffold's own LICENSE file (Expo's, Unity's, a starter template's) in the repo
root — that would publish this project under someone else's terms.

Third-party components are recorded in `THIRD-PARTY-NOTICES.md` — the Apache-2.0
Mobile Dependency Resolver and the LevelPlay/ironSource SDK among them. When
adding a font, SDK or asset pack: keep its licence text next to it, add a row to
the notices file, and remember that SIL OFL fonts need their text inside the
shipped build, not only in the repo.

## Studio-wide information

For studio-wide questions that are not specific to this game — Google account,
Play Console developer account, the status of yilkgames.com/yilkgames_web —
`C:\Projects\pictures\STUDIO.md` is the single source of truth; it is not
repeated here.
