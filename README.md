# Toxic Time

A top-down 2D shooter made for a game jam. Clear every enemy on 10 levels, and use slow motion powered by poison to survive.

My first game jam project, made with Unity for [Coco Code GameJam #1](https://itch.io/jam/coco-code-gamejam-1).

[**Play in your browser on itch.io**](https://devhex.itch.io/toxic-time)

## Gameplay

Each level is a small arena full of armed enemies. One enemy bullet kills you, so you need to aim fast and move smart.

- Pick up a weapon and shoot the enemies.
- Press **Q** to slow down time. Slow motion drains your stamina.
- Pick up **poison** and drink it to refill your stamina.
- Defeat every enemy to finish the level.

## Features

- **10 levels** built from pixel-art images. Each color in the image becomes a platform, an enemy or an item.
- **3 weapons:** Pistol, SMG and A-17, each with its own fire rate and ammo.
- **Enemy AI:** enemies spot you with raycasts and shoot back with a cooldown.
- **Slow motion:** a stamina system with post-processing effects (chromatic aberration and lens distortion).
- **Game feel:** camera shake, particle effects and sound effects.
- **Menus:** main menu, level select and a pause menu.

## Controls

| Input | Action |
|---|---|
| `W` `A` `S` `D` or arrow keys | Move |
| Mouse | Aim |
| `E` | Pick up the closest weapon or item |
| Left mouse button | Shoot, or drink poison |
| `Q` | Toggle slow motion |
| `Esc` | Pause |

## Getting Started

**Requirements**

- Unity **6000.0.25f1** (Unity 6.0)

Cinemachine, Input System, URP and the 2D feature set are installed automatically through the Package Manager.

**Run the project**

1. Clone the repository:

   ```bash
   git clone https://github.com/Yair-Bakshan/toxic-time-first-gamejam.git
   ```

2. Open the folder in Unity Hub with Unity 6000.0.25f1.
3. Open `Assets/Scenes/MainMenu.unity` and press **Play**.

All scenes are already in the Build Settings.

## Project Structure

| Folder | Contents |
|---|---|
| `Assets/Scripts` | Player, enemies, guns, level generation, camera, audio and UI |
| `Assets/Prefab` | Player, enemies, weapons, particles and UI prefabs |
| `Assets/Scenes` | Main menu, level select and Level 1 to Level 10 |
| `Assets/Sprites/Levels` | The pixel-art images that the level generator reads |

## Credits

- Font: Fredoka One by Milena Brandao
- Font: Pixel by krolesz94 (FontStruct, non-commercial license)

## Author

Yair Bakshan (DevHex)

## License

Released under the [MIT License](LICENSE).
