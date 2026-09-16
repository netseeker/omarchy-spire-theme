# Spire for Omarchy

Spire is a dark editorial-fantasy theme for Omarchy, built around warm ink-black surfaces, parchment text, restrained bronze accents, ember highlights, and smoke-blue counterpoints.

It stays deliberately close to Omarchy's native theming model: one complete semantic palette, one small lock-screen color override, and a curated wallpaper set. There are no scripts, hooks, custom shell widgets, compositor logic, terminal configs, or other executable extras.

![Spire preview](preview.png)

## Requirements

- Omarchy 4.0+ / Quattro

## Install

```bash
omarchy theme install https://github.com/netseeker/omarchy-spire-theme
```

Then select **Spire** from the Omarchy theme switcher.

For local testing:

```bash
rm -rf ~/.config/omarchy/themes/spire
mkdir -p ~/.config/omarchy/themes/spire

cp -a \
  colors.toml \
  shell.lock.toml \
  preview.png \
  backgrounds \
  ~/.config/omarchy/themes/spire/

omarchy theme set spire
```

## Included wallpapers

Spire ships with six 16:9 backgrounds:

1. `01-spire.webp` — warm hero landscape
2. `02-hall.webp` — quiet interior with generous negative space
3. `03-crossing.webp` — cooler landscape / daily-driver background
4. `04-the-watch.webp` — the compact strategist keeping watch
5. `05-the-advisor.webp` — the tall advisor overlooking the realm
6. `06-the-conspirators.webp` — both characters at the strategy table

The first four form the quieter core set. The last two are more character-focused bonus backgrounds.

## Palette

| Role | Color |
| --- | --- |
| Background | `#131110` |
| Elevated surface | `#221E19` |
| Foreground | `#D8C4A2` |
| Muted text | `#887A68` |
| Light foreground | `#E2CAA6` |
| Bright foreground | `#F0D7AF` |
| Accent | `#A38659` |
| Gold | `#D5A16D` |
| Ember | `#C87455` |
| Green | `#87946A` |
| Smoke cyan | `#8EA7AB` |
| Smoke blue | `#72899C` |

## Design intent

- Warm black instead of neutral black
- Parchment text instead of stark white
- Bronze as the everyday accent; brighter gold reserved for highlights
- Cool cyan and blue retained for editor and terminal readability
- A restrained bronze active-border gradient rather than a bright gold frame on every surface
- No full `shell.toml`; Spire inherits current Omarchy shell defaults
- Only the lock section is overridden, keeping the password field aligned with the palette
- Original Spire emblem used consistently across the wallpaper set

## Behind Spire

Spire grew out of the visual language developed for our daily editorial-fantasy satire. The recurring Advisor and Strategist in several wallpapers come from that same world.

Follow the project on X: [@EvilLOTRNews](https://x.com/EvilLOTRNews)

## Lock screen

Spire intentionally keeps Omarchy's standard blurred active-wallpaper lock screen. The theme only adjusts the password field colors via `shell.lock.toml`.

The blur is strong enough that detailed wallpaper characters are not meant to remain legible on the lock screen; the backgrounds are designed primarily as desktop wallpapers.

## Files

- `colors.toml` — complete semantic palette used by Omarchy's generated themes
- `shell.lock.toml` — lock-screen password-field color override
- `backgrounds/` — six curated wallpapers
- `preview.png` — real Omarchy desktop preview
- `CONTRAST.md` — contrast notes for the final palette
- `LICENSE` — licensing for configuration, documentation, and artwork
- `RELEASE_NOTES.md` — v1.0.2 release notes

## License

Configuration and documentation are licensed under the MIT License.

Artwork is made available under CC BY-NC 4.0 to the extent the contributors hold the relevant rights. See `LICENSE` for details.
