# Windows

This is a WIP layout based on Colemak DHm for using on macOS (with **en-US International** layout on host) that includes Spanish accents, and complemented with easy access to development symbols and JS/TS shortcuts.

![US International](/.github/images/layout/US-International.png)

---

## Menu

- [Conventions](#conventions)
- [Layers](#layers)
  - [BAS](bas)
  - [DEV](dev)
  - [AXN](axn)
  - [STG](stg)

---

## Conventions

### Icons

Icons used to describe some modifiers and actions

| Label        | Description |
| :-----------: | ----------- |
| <kbd>❖</kbd> | Win |
| <kbd>⌃</kbd> | Control |
| <kbd>⌥</kbd> | Alt |
| <kbd>⇧</kbd> | Shift |
| <kbd>🄰</kbd> | Caps Lock|
| <kbd>⎋</kbd> | Esc |
| <kbd>↹</kbd> | Tab |
| <kbd>⏎</kbd> | Return |
| <kbd>␣</kbd> | Space |
| <kbd>⇪</kbd> | [Hold Tap](https://zmk.dev/docs/behaviors/hold-tap#hold-tap) |
| <kbd>🔁</kbd> | [Key Repeat](https://zmk.dev/docs/behaviors/key-repeat) |

### Shared Modifiers

| Label           | Shortcut                                | Actions                                               |
| --------------: | --------------------------------------: | ----------------------------------------------------- |
| <kbd>⌫</kbd>   |                                         | Backspace                                             |
| <kbd>\|⌫</kbd> | <kbd>⇪⌫</kbd>                          | Delete word backward                                  |
| <kbd>⌦</kbd>   | <kbd>⇧</kbd>+<kbd>⌫</kbd>              | Delete                                                |
| <kbd>⌦\|</kbd> | <kbd>⇧</kbd>+<kbd>⇪⌫</kbd>             | Delete word forward                                   |
| <kbd>F2</kbd>   | <kbd>⇪⏎</kbd>                           | Rename (like macOS)                                   |
| <kbd>▷</kbd>   | <kbd>⇪↹</kbd>                            | left (terminal autocompletion)                        |
| <kbd>🄰</kbd>   | <kbd>⇧</kbd>+<kbd>⌫</kbd>               | Caps lock                                             |
| <kbd>⇧⇧</kbd>  | <kbd>L⇧</kbd>+<kbd>R⇧</kbd>              | [Caps word](https://zmk.dev/docs/behaviors/caps-word) |
| <kbd>^^</kbd>  | <kbd>L^</kbd>+<kbd>R^</kbd>              | Cancel caps                                           |
| <kbd>❖❖</kbd>  | <kbd>L❖</kbd>+<kbd>R❖</kbd>            | Show current layout on screen                         |

⇧ [Back to menu](#menu)

---

## Layers

### BAS

Letters, accents for Spanish language and quick shortcuts for most used symbols to "avoid" changing layers.

![BAS Layer](/.github/images/layers/macos/BAS.png)

#### Spanish

| Label        | Shortcut                                 |
| :----------: | ---------------------------------------: |
| <kbd>á</kbd> | <kbd>⌥</kbd>+<kbd>a</kbd>               |
| <kbd>Á</kbd> | <kbd>⇧</kbd>+<kbd>⌥</kbd>+<kbd>a</kbd>  |
| <kbd>é</kbd> | <kbd>⌥</kbd>+<kbd>e</kbd>               |
| <kbd>É</kbd> | <kbd>⇧</kbd>+<kbd>⌥</kbd>+<kbd>e</kbd>  |
| <kbd>í</kbd> | <kbd>⌥</kbd>+<kbd>i</kbd>               |
| <kbd>Í</kbd> | <kbd>⇧</kbd>+<kbd>⌥</kbd>+<kbd>i</kbd>  |
| <kbd>ó</kbd> | <kbd>⌥</kbd>+<kbd>o</kbd>               |
| <kbd>Ó</kbd> | <kbd>⇧</kbd>+<kbd>⌥</kbd>+<kbd>o</kbd>  |
| <kbd>ú</kbd> | <kbd>⌥</kbd>+<kbd>u</kbd>               |
| <kbd>Ú</kbd> | <kbd>⇧</kbd>+<kbd>⌥</kbd>+<kbd>u</kbd>  |
| <kbd>ü</kbd> | <kbd>^</kbd>+<kbd>u</kbd>                |
| <kbd>Ü</kbd> | <kbd>⇧</kbd>+<kbd>^</kbd>+<kbd>u</kbd>   |
| <kbd>ñ</kbd> | <kbd>⌥</kbd>+<kbd>n</kbd>               |
| <kbd>Ñ</kbd> | <kbd>⇧</kbd>+<kbd>⌥</kbd>+<kbd>n</kbd>  |

⇧ [Back to menu](#menu)

### DEV

Symbols and dev shortcuts for JS/TS.

![DEV Layer](/.github/images/layers/macos/DEV.png)

#### Symbols

| Label           | Shortcut                                  |
| :-------------: | -------------------------------------- -: |
| <kbd>°</kbd>    | <kbd>⌥</kbd>+<kbd>#</kbd>                |
| <kbd>€</kbd>    | <kbd>⌥</kbd>+<kbd>$</kbd>                |
| <kbd>«</kbd>    | <kbd>⌥</kbd>+<kbd>[</kbd>                |
| <kbd>»</kbd>    | <kbd>⌥</kbd>+<kbd>]</kbd>                |
| <kbd>¡</kbd>    | <kbd>⌥</kbd>+<kbd>!</kbd>                |
| <kbd>¿</kbd>    | <kbd>⌥</kbd>+<kbd>?</kbd>                |

#### Browser DevTools

| Label        | Shortcut                     | Action                      |
| -----------: | ---------------------------: | --------------------------- |
| <kbd>↻</kbd> | <kbd>↻</kbd>                 | Refresh                     |
| <kbd>⟳</kbd> | <kbd>⇧</kbd>+<kbd>↻</kbd>   | Hard refresh (clean cache) |
| <kbd>⩸</kbd> |                              | Open DevTools              |

#### VS Code

| Label               | Shortcut                                | Action                      |
| ------------------: | --------------------------------------: | --------------------------- |
| <kbd>//</kbd>       | <kbd>⌃</kbd>+<kbd>/</kbd>               | Toggle line comment         |
| <kbd>/\* \*/</kbd>  | <kbd>⇧</kbd>+<kbd>/</kbd>               | Toggle block comment        |

⇧ [Back to menu](#menu)

### AXN

Quick navigation actions and numbers. Function keys works independently as a sub-layer to avoid shortcuts collisions.

![AXN Layer](/.github/images/layers/macos/AXN.png)

#### Navigation

| Label          | Shortcut                               | Action               |
| ------------: | --------------------------------------- | -------------------- |
| <kbd>△</kbd>  |                                        | Up                    |
| <kbd>▽</kbd>  |                                        | Down                  |
| <kbd>◁</kbd>  |                                        | Left                  |
| <kbd>▷</kbd>  |                                        | Right                 |
| <kbd>⇤</kbd>  |                                         | Home                  |
| <kbd>⇥</kbd>  |                                         | End                   |
| <kbd>⤒</kbd>  | <kbd>^</kbd>+<kbd>⇤</kbd>               | Beginning of document |
| <kbd>⤓</kbd>  | <kbd>^</kbd>+<kbd>⇥</kbd>               | End of document       |
| <kbd>⇞</kbd>  |                                         | Page up               |
| <kbd>⇟</kbd>  |                                         | Page down             |
| <kbd>⇺</kbd>  |                                         | Prev Tab              |
| <kbd>⇻</kbd>  |                                         | Next Tab              |
| <kbd>▦</kbd>  |                                        | New virtual desktop   |
| <kbd>▩</kbd>  |                                        | Close virtual desktop |
| <kbd>⎗</kbd>  | <kbd>⇧</kbd>+<kbd>⇺</kbd>              | Prev desktop          |
| <kbd>⎘</kbd>  | <kbd>⇧</kbd>+<kbd>⇻</kbd>              | Next desktop          |

#### Actions

| Label          | Shortcut                   | Action               |
| -------------: | -------------------------- | -------------------- |
| <kbd><\|</kbd> |                            | Expand selection     |
| <kbd>\|></kbd> |                            | Shrink selection     |
| <kbd>↶</kbd>  |                             | Undo                 |
| <kbd>↷</kbd>  |                             | Redo                 |
| <kbd>⬚</kbd>  |                             | Cut                  |
| <kbd>⿻</kbd>  |                             | Copy                 |
| <kbd>⏍</kbd>  |                             | Paste                |
| <kbd>⛶</kbd>  | <kbd>⇧</kbd>+<kbd>⏍</kbd>   | Paste without format |
| <kbd>☉</kbd>  |                             | Find                 |
| <kbd>☊</kbd>  |                             | Replace              |

⇧ [Back to menu](#menu)

### STG

Dedicated to Bluetooth and media controls.

![STG Layer](/.github/images/layers/macos/STG.png)

#### Actions

| Label                     | Action                        |
| ------------------------: |  ---------------------------- |
| <kbd>B#️⃣</kbd>            | Jump to #️⃣ device             |
| <kbd>⎉</kbd>              | Connect Quick Action          |
| <kbd>B❌</kbd>            | Clear current device          |
| <kbd>▣</kbd>              | Capture portion of the screen |
| <kbd>▣</kbd>+<kbd>␣</kbd> | capture a window or menu      |
| <kbd>□</kbd>              | capture screen shoot          |
| <kbd>⛢</kbd>              | Color Picker                 |
| <kbd>🖿</kbd>              | Finder (File Explorer)       |
| <kbd>Z+</kbd>              | Zoom in                      |
| <kbd>ZR</kbd>              | Zoom reset                   |
| <kbd>Z-</kbd>              | Zoom out                     |
| <kbd>M+</kbd>              | Magnifier in                 |
| <kbd>MR</kbd>              | Magnifier reset              |
| <kbd>M-</kbd>              | Magnifier out                |
| <kbd>🔅</kbd>              | Bright down                  |
| <kbd>🔆</kbd>              | Bright up                    |
| <kbd>⎚</kbd>               | Fancy Zones                  |
| <kbd>▤</kbd>               | Task Manager                 |
| <kbd>ⓘ</kbd>              | System Info                   |
| <kbd>⛨</kbd>              | Security                      |
| <kbd>⎈</kbd>               | Settings                     |

#### Media

| Label         | Action       |
| ------------: |  ----------- |
| <kbd>🔊</kbd> | Volume up    |
| <kbd>🔇</kbd> | Mute         |
| <kbd>🔉</kbd>  | Volume down  |
| <kbd>⏹️</kbd> | Stop         |
| <kbd>⏪</kbd> | Fast reverse |
| <kbd>⏮️</kbd> | Prev         |
| <kbd>⏯️</kbd> | Play/Pause   |
| <kbd>⏭️</kbd> | Next         |
| <kbd>⏩</kbd> | Fast Forward |
| <kbd>🔀</kbd> | Shuffle      |

⇧ [Back to menu](#menu)
