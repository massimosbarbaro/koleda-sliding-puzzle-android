# Puzzle Koleda: sliding-tile puzzle game on a winter folk tradition

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23205264.svg)](https://doi.org/10.5281/zenodo.23205264)

*Gioco del quindici (puzzle a tessere) su una tradizione popolare invernale*

**Android** · 2021 · version 1.0  
Author: **Massimo Sbarbaro** ([ORCID 0009-0006-8965-9013](https://orcid.org/0009-0006-8965-9013))

## Overview

A 3×3 sliding-tile puzzle on the theme of the *koleda*, the carol singing that marks the New Year in Slovene folk tradition. The picture is cut into nine tiles that the player slides on a canvas until the image is recomposed; on success the app plays applause and the traditional song and offers a link to a page about the custom. Slovene interface.

I designed and programmed this application in 2021. It is published here in 2026 as part of the documented record of my software work, with a permanent DOI on Zenodo.

## Main functions

- Start screen with the game and web-page buttons (`Screen1`).
- Game screen with nine image sprites on a canvas, shuffling, tile moves and win detection (`scrFacil`).
- Sound feedback, vibration and link to an information page.

## Data

No data: the nine picture tiles and the sounds were packaged with the app (removed from this publication).

## Technology

MIT App Inventor 2: Canvas, ImageSprite, Sound, Player, ActivityStarter.

## Repository contents

| Path | Content |
|---|---|
| `project/*.aia` | The App Inventor project, ready to be imported (*Projects → Import project (.aia)* at ai2.appinventor.mit.edu). |
| `source/src/` | Screen designs (`.scm`, JSON) and block programs (`.bky`, Blockly XML), one pair per screen. |
| `source/assets/` | Button icons and App Inventor extensions used by the project. |
| `source/youngandroidproject/` | Project properties (package, version, theme). |

## What is not included

Photographs, illustrations, logos, sound recordings and stock images are **not** included: most of them belong to third parties (photographers, illustrators, performers, the commissioning organisation). The project still opens in App Inventor; the components that showed those media are simply empty. The name of the commissioning organisation and the funding statement have been removed, together with addresses, telephone numbers, e-mail addresses and websites of third parties; web addresses used by the app have been replaced with `example.org`. The compiled APK and its signing key are not published.

## How to cite

Use the citation metadata in [`CITATION.cff`](CITATION.cff) (GitHub: *Cite this repository*). The release is archived on Zenodo with the DOI [10.5281/zenodo.23205264](https://doi.org/10.5281/zenodo.23205264).

> Sbarbaro, Massimo. 2021. *Puzzle Koleda: sliding-tile puzzle game on a winter folk tradition*. Software (Android, 2021), version 1.0. Zenodo. https://doi.org/10.5281/zenodo.23205264.

## License

Released under the [MIT License](LICENSE). © 2021 Massimo Sbarbaro.
