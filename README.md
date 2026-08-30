# Mavic Drop

[![CI](https://github.com/Sam-DarkBall-Mods/Mavic-Drop/actions/workflows/ci.yml/badge.svg)](https://github.com/Sam-DarkBall-Mods/Mavic-Drop/actions/workflows/ci.yml)

Mavic Drop adds detachable grenade payloads for compatible drones. The mod
contains the payload models, an attachment action, a selector interface and the
drop script. A released grenade starts with the drone's current velocity and is
also affected by wind.

## Requirements

- Arma 3 2.22 or newer

## Building

```bash
python3 -B -m unittest discover -s tests -p "test_*.py" -v
hemtt check
hemtt build --no-bin
```

The release keeps the old `mavic_drop.pbo` name and `mavic_drop` prefix.

## License

Code and configs use GPL-2.0-or-later. Original payload models, textures and
audio use APL-SA. See [LICENSES.md](LICENSES.md).
