# W-Rally content

W-Rally's own content: stages, cars, audio and video, read by the game from its `content/` folder. This repository
is checked out there as a submodule of [w-rally](https://github.com/w-rally/w-rally).

Only content made for W-Rally (or licensed for it) belongs here. Nothing taken or converted from Richard Burns Rally
or any other game: W-Rally reads RBR's files in place from a player's own install.

## Layout

- `cars/<id>.ini` - W-Rally's values on top of a car's physics data
- `stages/`, `cars/<id>/`, `audio/`, `video/` - as the game's design describes them (docs/design.md 6.1 in w-rally)

## Licence

[CC BY-NC 4.0](LICENSE.txt): share and adapt with attribution, for noncommercial purposes only.
