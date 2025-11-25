# Link's Arrow Quest

Dive into 'Link's Arrow Quest' – a thrilling Pygame crossover where Zelda's legendary hero Link wields his bow against Undertale's eerie landscapes! Can you rack up the ultimate high score by sniping arrows with precision? This fan-inspired mashup turns pixelated peril into addictive arrow-hunting fun.

## 🎮 Game Overview

Step into Undertale's twisted underground as Link, dodging pitfalls and gravity's pull while hunting glowing arrows to refill your quiver. Shoot your bow with mouse precision to propel forward, collecting targets for points and arrows – but one wrong leap sends you tumbling to game over! Vibes hit hard with looping tracks: chill MenuMusic.ogg for the start screen, pulse-pounding MainMusic.mp3 during action, and somber GameOverMusic.mp3 when the fall comes. It's quick sessions of Hyrule-meets-Underground chaos, perfect for high-score chasers.

## 🚀 Quick Start

No elf ears required – jump in fast!

### Python Setup (Dev Mode)
1. Clone the repo: `git clone https://github.com/Astatide1337/Pygame.git`
2. Install deps: `pip install -r requirements.txt` (Pygame 2.3.0 powers the magic)
3. Run: `python Main.py`

Assets live in `Public/` – audio, fonts, images all self-contained. High scores save to `Public/highscore.json` for persistence across runs.

### EXE Play (Windows Only – Plug & Play)
- Grab `Main.exe` from the `Exe/` folder (includes all assets in `Exe/Public/`).
- Double-click to launch – no Python needed!
- High scores stick via the bundled `highscore.json`. Share with friends for score battles!

Pro tip: If scores reset oddly, check file permissions in the EXE's Public folder.

## 🎯 Controls & Tips

Master the bow in seconds – it's all about that Hylian aim!

- **Movement**: Gravity pulls you down; shoot (Spacebar) to launch toward your mouse cursor for jumps and glides.
- **Aiming**: Mouse points the bow – drag to fine-tune direction.
- **Shoot**: Spacebar fires an arrow (costs 1 from your quiver; collect to refill).
- **Quit/Restart**: Menu buttons or close the window.

**Tips to Dominate**:
- Time shots to arc over obstacles on the Undertale map – momentum is your friend!
- Hunt collectibles early; each arrow snag boosts score + quiver (start with 5).
- Pro move: Hover mouse low for longer glides, but watch the edges – one slip, and it's game over. Precision sniping = high-score glory!

## 📸 Gameplay Peek

Peek at the pixelated action without firing up the game:

![Menu Screen](Public/images/Menu.jpg)  
*Eerie menu vibes, ready to play – high score taunting you already?*

![In-Game Action](Public/images/UndertaleMap.jpg)  
*Link mid-leap on Undertale's haunting map, bow drawn on a target!*

![Game Over](Public/images/GameOver.png)  
*Score reveal – did you beat the high score, hero?*

(Imagine a GIF here of Link shooting an arrow – smooth Pygame physics in motion. Assets like Link.png and arrow.png bring the crossover charm.)

## 🏆 High Scores & Features

Chase glory with persistent high scores saved in `highscore.json` – beats stick between sessions, so grind for that personal best! Displayed boldly in Montserrat-ExtraBold font on menus and game over.

**Standout Features**:
- **Arrow Physics**: Pygame's Vector2 magic for realistic shots and gravity tugs – no floaty jumps here.
- **Dynamic Audio**: Seamless mixer transitions – collect sounds (Arrowcollect.mp3) pop on pickups, music loops keep the tension high.
- **Crossover Polish**: Link's sprite scaled crisp (50x60), bow rotations for immersive aiming, UndertaleMap.jpg as the eerie backdrop.
- **Quick Loops**: 60 FPS cap for buttery play; auto-restart after 5s on death.

Tease: More maps (Waterfall? Hotland?) and power-ups incoming – fork and suggest via issues!

## ❤️ Credits & Shoutouts

Huge nods to Nintendo for Zelda's timeless Link and bow mastery, and Toby Fox for Undertale's unforgettable world that inspired this mashup. Assets blend custom pixels (Link.png, Bow.png) with public nods – all fair-use fan fun, no IP drama.

Built solo with Pygame love. Got feedback, score boasts, or mod ideas? Hit up issues – let's make this quest legendary! 🚀