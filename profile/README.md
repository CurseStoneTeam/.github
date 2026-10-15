<div align="center">

# CurseStoneTeam

**We build Minecraft: Pocket Edition server software from the ground up, in C and C++.**

[Server](https://github.com/CurseStoneTeam/CurseStone) · [Plugin docs](https://CurseStoneTeam.github.io) · [Contribute](https://github.com/CurseStoneTeam/CurseStone/blob/stable/CONTRIBUTING.md)

</div>

<div align="center">

[Oficial Website](https://cursestone.pages.dev/)

</div>

---

## About us

CurseStoneTeam is a small open source team making **CurseStone**, a server for Minecraft: Pocket Edition 0.15.x (protocol 84). We care about code you can read end to end, builds that work on every platform, and tools that help you find out why a server is slow.

## How CurseStone is built

```
  Lua 5.4 plugins        your code, loaded at runtime
  ─────────────────
  C++20 game layer       players, world, blocks, items, commands
  ─────────────────
  C core                 RakNet, NBT, binary I/O, math, chunk data
```

The C core stays plain C, and the game logic lives in C++. That boundary is enforced by our [contributing rules](https://github.com/CurseStoneTeam/CurseStone/blob/stable/CONTRIBUTING.md).

## The team

| | Role |
|---|---|
| **Dr1xyDev** | Founder & Developer |
| **pkz.byt** | Co-founder & Developer |
| **mateocollar** | Developer |

## Repositories

| Repository | What you'll find |
|---|---|
| [**CurseStone**](https://github.com/CurseStoneTeam/CurseStone) | The server: Linux, macOS, Windows and Android (Termux) |
| [**cursestone-docs**](https://github.com/CurseStoneTeam/cursestone-docs) | Lua plugin guide, API reference and an example plugin |

## Join in

- 🛠️ **Build it:** the [building guide](https://github.com/CurseStoneTeam/CurseStone/blob/stable/BUILDING.md) gets you from clone to running server.
- 🐛 **Break it:** found a bug? Open an [issue](https://github.com/CurseStoneTeam/CurseStone/issues) with steps to reproduce.
- 🔌 **Extend it:** write a Lua plugin using the [plugin docs](https://github.com/CurseStoneTeam/cursestone-docs).
- 💡 **Improve it:** for anything bigger than a small fix, open an issue first so we can agree on the approach.

<sub>Licensed under [LGPL-3.0-or-later](https://www.gnu.org/licenses/lgpl-3.0.html). CurseStoneTeam is not affiliated with Mojang; all brands and trademarks belong to their respective owners.</sub>
