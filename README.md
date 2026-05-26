# StreamFighter Game Packs

Character art packs for use with [StreamFighter](https://github.com/SetCount/StreamFighter).

## Disclaimer

All character artwork, portraits, stock icons, and related assets belong to their respective copyright holders. This repository does not claim ownership of any included assets. Assets are provided for non-commercial, fan use only.

## Structure

```
<gameId>/
  game.json
  characters/
    <charId>/
      select.png
      portrait_01.png
      stock_01.png
      portrait_02.png
      stock_02.png
      ...
```

The `gameId` directory name is what StreamFighter uses as the game identifier. Costume count is implicit — add a `portrait_NN.png` / `stock_NN.png` pair for each costume.

See the [StreamFighter docs](https://github.com/SetCount/StreamFighter) for the full `game.json` schema.

## Usage

Point StreamFighter's **Games Directory** setting at the directory containing these packs. The app will pick them up on next launch (or via **Reload Games** in Settings).
