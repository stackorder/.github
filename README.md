# stackorder/.github

This repository holds the public profile of the [Stackorder](https://stackorder.io) organisation on GitHub. GitHub shows `profile/README.md` on the organisation page at [github.com/stackorder](https://github.com/stackorder), above the pinned repositories.

For the project itself, start with [`stackorder/stackorder`](https://github.com/stackorder/stackorder) and the documentation at [docs.stackorder.io](https://docs.stackorder.io).

## Contents

| Path | What it is |
| --- | --- |
| `profile/README.md` | The organisation profile: banner, pitch, how it works, repositories, documentation links, status and licence |
| `profile/assets/banner-light.svg` | Banner for GitHub's light theme: the colour lockup and tagline on Sand |
| `profile/assets/banner-dark.svg` | Banner for GitHub's dark theme: the dark lockup and tagline on Slate |
| `profile/assets/avatar.png` | The organisation avatar, 1024 by 1024, opaque and safe under a circle crop |

## Organisation avatar

GitHub does not read the avatar from this repository. An organisation owner uploads `profile/assets/avatar.png` by hand in the `stackorder` organisation's **Settings > General > Profile picture** (`https://github.com/organizations/stackorder/settings/profile`). The copy here keeps the file next to the profile it belongs to.

## Brand assets

Every image here comes from the Stackorder brand kit, described in the [brand guide](https://stackorder.io/brand). None of it is redrawn:

- `avatar.png` is the kit's `dist/github-avatar.png`, unchanged.
- The banners combine the kit's `svg/lockup-light.svg` or `svg/lockup-dark.svg`, at scale 6, with the outlined tagline from `svg/social-preview.svg`. It is the social preview's composition on a shorter, rounded card.

The wordmark and the tagline are outlines, so the banners look the same everywhere: an SVG shown through `<img>` cannot load web fonts, and system fonts differ from reader to reader. When the kit changes, copy the new paths into the banners rather than editing them here, and keep each lockup on its own background: the light lockup on Sand, the dark lockup on Slate.
