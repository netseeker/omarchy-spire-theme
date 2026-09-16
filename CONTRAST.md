# Spire contrast notes

Reference surfaces:

- Primary background: `#131110`
- Elevated background: `#221E19`

Approximate WCAG contrast ratios:

| Role | Color | vs `#131110` | vs `#221E19` |
| --- | --- | ---: | ---: |
| Foreground | `#D8C4A2` | 11.06:1 | 9.73:1 |
| Light foreground | `#E2CAA6` | 11.86:1 | 10.44:1 |
| Bright foreground | `#F0D7AF` | 13.49:1 | 11.87:1 |
| Dark foreground | `#8D8676` | 5.20:1 | 4.58:1 |
| Muted | `#887A68` | 4.51:1 | 3.97:1 |
| Accent | `#A38659` | 5.48:1 | 4.82:1 |
| Red | `#C87455` | 5.46:1 | 4.80:1 |
| Yellow | `#D5A16D` | 8.20:1 | 7.22:1 |
| Green | `#87946A` | 5.80:1 | 5.11:1 |
| Cyan | `#8EA7AB` | 7.41:1 | 6.52:1 |
| Blue | `#72899C` | 5.18:1 | 4.55:1 |
| Magenta | `#A98289` | 5.60:1 | 4.92:1 |
| Brown | `#AD7C5A` | 5.21:1 | 4.58:1 |

`muted` is intentionally the weakest text role. It clears roughly 4.5:1 on the primary background used by terminals and most shell surfaces, while remaining visibly de-emphasised. It should not be used for essential information on elevated surfaces.

`selection` (`#392E24`) is a background tint, not a foreground text color.
