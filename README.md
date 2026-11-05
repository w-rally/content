# W-Rally content

W-Rally's own content: stages, cars, audio and video, read by the game from its `content/` folder. This repository
is checked out there as a submodule of [w-rally](https://github.com/w-rally/w-rally).

Only content made for W-Rally (or licensed for it) belongs here. Nothing taken or converted from Richard Burns Rally
or any other game: W-Rally reads RBR's files in place from a player's own install.

## Layout

W-Rally's layer of the game's content (docs/content-layers.md in w-rally): every item in a folder of its own, per
version.

- `tracks/<id>/<version>/`, `cars/<id>/<version>/`, `cars/<id>/physics/<variant>/<version>/`,
  `physics/<base>/<version>/` - a track, a car, a car's physics, a physics base; ids are lowercase slugs, a track's
  `<country>_<stagename>`
- `rbr-tracks.json` - RBR's map numbers to track ids (from the onlineracing.cz tracks table, w-rally
  tools/rbr-tracks)
- `video/` - the main menu's video loop

## Licence

[CC BY-NC 4.0](LICENSE.txt): share and adapt with attribution, for noncommercial purposes only. Except third-party
material, under its own licence as its folder's CREDITS.md says (`video/menu.mp4`: free stock clips).
