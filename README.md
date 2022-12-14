![](Abinde.png)
# Abinde

Abinde is a python module for pygame.

## Advantages

- Easy to use
- Lightweight

## How to use

### Shell

```sh
pip install -U Abinde
```

### Python

```python
import Abinde as ab
game = ab.Game()
player = ab.sprite.Player(ab.LoadImage("path/to/image"))
game.mainloop()
```

## Requirements

- __pygame__ for module.
- __PyOpenGL__ for better pygame.
- __threading__ for main loop.
- __python__ for running module.
- __PIL__ for image support

## Tested on

| Raspberry Pi OS | Debian Linux    | Mac          |
|-----------------|-----------------|-----------------|
| Stable (v1.3)   | Stable (v1.2)   | Unstable          |

## Please Note

To use this module, you will need at least some experience with coding python.
libc++abi.dylib: terminating with uncaught exception of type NSException