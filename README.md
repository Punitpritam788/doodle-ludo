# 🎲 Doodle Ludo

### Roll it. Race it. Doodle it.

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Three.js-black?style=for-the-badge&logo=threedotjs&logoColor=white" alt="Three.js">
  <img src="https://img.shields.io/badge/WebGL-990000?style=for-the-badge&logo=webgl&logoColor=white" alt="WebGL">
  <img src="https://img.shields.io/badge/Canvas-FF6F00?style=for-the-badge&logo=html5&logoColor=white" alt="Canvas">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Web%20Browser-blue?style=flat-square" alt="Platform">
  <img src="https://img.shields.io/badge/Game-3D%20Board%20Game-purple?style=flat-square" alt="Game">
  <img src="https://img.shields.io/badge/Architecture-Single%20HTML%20File-orange?style=flat-square" alt="Architecture">
  <img src="https://img.shields.io/badge/Game%20Logic-Implemented-success?style=flat-square" alt="Game Logic">
  <img src="https://img.shields.io/badge/Big%20Board-BETA-yellow?style=flat-square" alt="Big Board Beta">
  <img src="https://img.shields.io/badge/Online%20Multiplayer-Runtime%20Dependent-lightgrey?style=flat-square" alt="Online Multiplayer">
</p>

**Doodle Ludo** is a colorful, hand-drawn 3D interpretation of the classic Ludo board game, built with HTML5, CSS3, JavaScript and Three.js.

It combines traditional Ludo gameplay with a playful visual identity, interactive 3D graphics, intelligent bot opponents, cooperative team gameplay, experimental large-board matches and online multiplayer functionality.

The goal is to transform a familiar board game into an interactive browser-based experience with expressive animations, custom procedural visual effects, sound design and multiple ways to play.

Whether you're competing against AI opponents, teaming up with a partner or experimenting with a giant multiplayer board, Doodle Ludo brings a fresh perspective to a timeless game.

**Doodle Ludo - Roll it. Race it. Doodle it.**

---

## 📑 Table of Contents

- [✨ Features](#-features)
- [🎮 Game Modes](#-game-modes)
- [🎲 Classic Ludo Gameplay](#-classic-ludo-gameplay)
- [🧠 AI Bot Intelligence](#-ai-bot-intelligence)
- [🎨 Visual Experience](#-visual-experience)
- [💥 Animation and Battle Effects](#-animation-and-battle-effects)
- [🔊 Audio System](#-audio-system)
- [📊 Statistics and Save System](#-statistics-and-save-system)
- [⚙️ Settings and Accessibility](#️-settings-and-accessibility)
- [🕹️ Controls](#️-controls)
- [🛠️ Technology Stack](#️-technology-stack)
- [🏗️ Project Architecture](#️-project-architecture)
- [🚀 Getting Started](#-getting-started)
- [🌐 Online Multiplayer](#-online-multiplayer)
- [📱 Responsive Design](#-responsive-design)
- [📂 Project Structure](#-project-structure)
- [🗺️ Project Status](#️-project-status)
- [🔮 Future Improvements](#-future-improvements)
- [🤝 Contributing](#-contributing)
- [🐛 Bug Reports](#-bug-reports)
- [📜 License](#-license)
- [❤️ Acknowledgements](#️-acknowledgements)

---

## ✨ Features

Doodle Ludo combines classic board-game mechanics with modern browser-based game development.

### 🎨 1. Hand-Drawn 3D Visual Experience

A playful visual style inspired by doodles, sketchbooks and colorful illustrations.

Features include:

- Interactive 3D Ludo board.
- Stylized toon-inspired materials.
- Custom outlines and visual details.
- Colorful player tokens.
- Animated dice.
- Hand-drawn interface elements.
- Animated menus and buttons.
- Responsive HUD and player indicators.
- Camera transitions and board rotation.
- Custom visual effects and particles.

### 🧠 2. Intelligent AI Opponents

Challenge computer-controlled opponents with different levels of decision-making.

Three difficulty levels are available:

| Difficulty | Behavior |
|---|---|
| Easy | More random decisions with occasional strategic moves. |
| Normal | Evaluates captures, safe squares and token progression. |
| Hard | Considers opponent threats, defensive positioning and tactical opportunities. |

The bot system evaluates available legal moves and uses different selection strategies according to the chosen difficulty.

### 🎮 3. Multiple Game Modes

Experience Ludo in different ways.

- Classic Mode
- Co-op Team Mode
- Big Board Mode (Beta)
- Online Multiplayer

### 💥 4. Custom Procedural Effects

Doodle Ludo includes a custom procedural animation and visual-effects system.

- Dice animations.
- Token movement effects.
- Capture effects.
- Finishing animations.
- Particle-based effects.
- Victory celebrations.
- Custom battle-effect presets.

### 🔊 5. Procedural Audio

The browser-based audio system includes:

- Dice sounds.
- Token movement sounds.
- Capture sounds.
- Finishing sounds.
- Interface interaction sounds.
- Procedurally generated background music.
- Independent sound and music controls.

### 📊 6. Statistics and Progress

Keep track of your gameplay with built-in statistics.

- Total games played.
- Total captures.
- Sixes rolled.
- Best game by turn count.
- Current winning streak.
- Best winning streak.
- Wins by player color.

### 💾 7. Local Save System

Continue unfinished games without starting over.

- Save the current game state.
- Restore unfinished matches.
- Remember player names.
- Store settings and preferences.
- Preserve statistics.
- Reset saved information through the settings menu.

---

## 🎮 Game Modes

### 1. Classic Mode

<kbd>2–4 Players</kbd>

Play the traditional Ludo experience with a combination of human players and AI opponents.

**Features:**

- Supports 2–4 players.
- Four tokens per player.
- Custom player names.
- Human and bot player selection.
- Enable or disable individual seats.
- Three bot difficulty levels.
- Automatic turn management.
- Traditional Ludo rules.

Players can configure their seats before starting a match.

### 2. Co-op Team Mode

<kbd>2 Teams · 4 Players</kbd>

Why compete against everyone when you can work together?

Co-op mode introduces cooperative gameplay.

**Team configuration:**

| Team | Players |
|---|---|
| Team 1 | 🔴 Red + 🟡 Yellow |
| Team 2 | 🟢 Green + 🔵 Blue |

**Features:**

- Two teams compete against each other.
- Teammates can move each other's tokens.
- Teammates cannot capture each other.
- Shared team strategy.
- Eight tokens per team.
- First team to bring all eight tokens home wins.

Co-op mode can be played locally by sharing the same device or through the supported online multiplayer functionality.

### 3. Big Board Mode - BETA

<kbd>2–16 Players</kbd> <kbd>Experimental</kbd>

Take the traditional Ludo experience and expand it into a giant circular board.

Big Board is an experimental mode designed to support more players than the standard four-player board.

**Features:**

- Supports 2–16 players.
- Extended circular game track.
- Configurable human player count.
- Remaining seats controlled by bots.
- Customizable player names.
- Expanded token and player management.
- Shared game mechanics with the standard Ludo experience.

**Experimental limitations:**

- Big Board is currently marked as Beta.
- Co-op mode is unavailable while Big Board is enabled.
- Some gameplay behavior and extended-board interactions may need additional refinement.

### 4. Online Multiplayer

<kbd>Online Co-op</kbd> <kbd>Private Rooms</kbd>

Play cooperative online matches with other players through supported multiplayer services.

**Features:**

- Quick match.
- Private room creation.
- Five-character room codes.
- Join existing rooms.
- Live player lobby.
- Real-time game-state synchronization.
- Bot-controlled empty seats.
- Online leaderboard.
- Automatic bot takeover for inactive players.

Online matches use the cooperative Red + Yellow versus Green + Blue team format.

**Important:** Online multiplayer currently depends on the compatible Claude.ai runtime, including its `window.claude` database and user services. It requires an authenticated session and suitable Contributor permissions. The feature is not independently deployable through ordinary GitHub Pages hosting without a compatible backend implementation.

---

## 🎲 Classic Ludo Gameplay

Doodle Ludo implements the familiar rules of traditional Ludo.

### Game Objective

Move all four of your tokens around the board and bring them safely into the center.

The first player to finish all four tokens wins the game.

### Game Rules

| Rule | Description |
|---|---|
| Leaving the yard | Roll a 6 to bring a token onto its starting square. |
| Movement | Tokens move according to the dice result. |
| Safe squares | Start squares and star squares protect tokens. |
| Capture | Land on a single unprotected opponent token to send it back to its yard. |
| Token walls | Two tokens stacked together form a wall. |
| Extra turn | Rolling a 6 grants another turn. |
| Capture bonus | Capturing an opponent grants another turn. |
| Finishing bonus | Bringing a token home grants another turn. |
| Three consecutive sixes | The turn is forfeited. |
| Exact finish | An exact dice roll is required to reach the center. |

### Winning Conditions

**Classic Mode:** A player must bring all four tokens home.

**Co-op Mode:** A team must bring all eight combined tokens home.

**Big Board:** The game follows the extended-board finish-order logic.

---

## 🧠 AI Bot Intelligence

The AI system is built around evaluating available legal moves and selecting a move based on the configured difficulty.

### Easy AI

A less predictable opponent.

- Introduces more random decisions.
- Occasionally prioritizes finishing tokens.
- Occasionally selects capture opportunities.
- Provides a more relaxed challenge.

### Normal AI

A more tactical opponent.

- Prioritizes finishing moves.
- Evaluates capture opportunities.
- Considers safe landing positions.
- Rewards token progression.
- Applies basic threat awareness.

### Hard AI

A more defensive and strategic opponent.

- Evaluates possible opponent captures.
- Considers token vulnerability.
- Rewards safer movement.
- Looks for opportunities to threaten opponents.
- Uses additional tactical scoring.

### AI Move Evaluation

The bot considers several factors:

| Evaluation Factor | Purpose |
|---|---|
| Finishing | Prioritize completing a token. |
| Captures | Reward capturing opponents. |
| Entering the board | Encourage bringing tokens out of the yard. |
| Safe landing | Reward protected positions. |
| Progression | Encourage advancing tokens. |
| Threat awareness | Reduce exposure to opponent captures. |

The AI is rule-based rather than powered by a machine-learning model.

---

## 🎨 Visual Experience

Doodle Ludo uses Three.js to create an interactive 3D environment.

### Rendering Features

- Three-dimensional board geometry.
- Perspective camera.
- Animated dice.
- 3D token models.
- Custom materials.
- Stylized lighting.
- Outlines and toon-inspired shading.
- Dynamic board positioning.
- Automatic resizing.
- Interactive camera controls.

### Visual Style

The visual identity combines:

- Sketchbook-inspired styling.
- Warm paper-like backgrounds.
- Playful typography.
- Colorful game pieces.
- Hand-drawn interface elements.
- Animated visual feedback.

The intention is to preserve the casual feeling of a traditional board game while making the presentation feel modern and interactive.

---

## 💥 Animation and Battle Effects

The project includes a custom procedural effects library named **PixelFX**.

It provides reusable animation and particle-effect utilities.

### Animation Categories

- Token movement.
- Dice rolling.
- Token capture.
- Token finishing.
- Victory celebration.
- Interface transitions.
- Board interaction feedback.

### PixelFX Effects

The embedded PixelFX system includes utilities for effects such as:

- Firework bursts.
- Hit sparks.
- Explosions.
- Particle bursts.
- Magic circles.
- Lightning.
- Star effects.
- Fire rings.
- Heavy impacts.
- Confetti.
- Portal effects.
- Shield effects.
- Ground and dirt explosions.

The system supports procedural rendering and reusable effect configurations.

### Battle Effect Presets

| Setting | Description |
|---|---|
| Off | Disables additional battle effects. |
| Normal | Enables regular visual effects. |
| Epic | Enables stronger visual effects. |

Battle effects can also be changed while playing.

---

## 🔊 Audio System

The game includes a procedural browser-based audio system using the Web Audio API.

### Sound Effects

- Button clicks.
- Dice shaking.
- Dice landing.
- Moving tokens.
- Entering the board.
- Capturing tokens.
- Finishing tokens.
- Safe landing.
- Gameplay feedback.

### Background Music

The audio system includes procedurally generated music.

### Audio Controls

- Enable or disable sound effects.
- Enable or disable background music.
- Adjust audio behavior through the audio subsystem.
- Save audio preferences locally.

Audio initialization follows browser interaction and autoplay requirements.

---

## 📊 Statistics and Save System

Doodle Ludo provides local gameplay statistics and save functionality.

### Available Statistics

| Statistic | Description |
|---|---|
| Games | Total games played. |
| Captures | Total opponent tokens captured. |
| Sixes | Total sixes rolled. |
| Best Game | Best game measured by turn count. |
| Win Streak | Current consecutive winning streak. |
| Best Streak | Highest recorded winning streak. |
| Wins by Color | Individual wins for each color. |

### Local Save System

The game uses browser `localStorage` to store:

- Unfinished game state.
- Player settings.
- Player names.
- Gameplay statistics.
- Audio preferences.

The Continue option becomes available when an unfinished local game is saved.

The reset option allows users to clear stored game data, settings and statistics.

---

## ⚙️ Settings and Accessibility

Doodle Ludo includes customizable gameplay and accessibility options.

| Setting | Available Options |
|---|---|
| Sound Effects | On / Off |
| Music | On / Off |
| Bot Difficulty | Easy / Normal / Hard |
| Bot Speed | Slow / Normal / Fast |
| Rotate Board | Auto / Each Turn / Off |
| Battle Effects | Off / Normal / Epic |
| Colorblind Symbols | On / Off |
| Reduced Motion | On / Off |

### Accessibility Features

- Colorblind symbols alongside player colors.
- Reduced-motion setting.
- Keyboard dice interaction.
- Accessible labels for interactive controls.
- Responsive menus and controls.
- Keyboard focus indicators.

The application also respects the operating system's reduced-motion preference.

---

## 🕹️ Controls

### Mouse and Touch

| Action | Control |
|---|---|
| Roll Dice | Tap or click anywhere on the board |
| Move Token | Tap or click a highlighted token |
| Pan Board | Drag |
| Zoom In / Out | Mouse wheel or pinch gesture |
| Pause Game | Pause button |

### Keyboard

| Key | Action |
|---|---|
| Space | Roll the dice |

### Gameplay Tips

- Look for highlighted tokens after rolling.
- Use safe squares to protect your pieces.
- Watch for opponents approaching your tokens.
- Use extra turns strategically.
- Coordinate with your teammate in Co-op mode.

---

## 🛠️ Technology Stack

Doodle Ludo is built using browser-native technologies and the Three.js ecosystem.

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | Responsive interface and styling |
| JavaScript | Gameplay logic and interactions |
| Three.js | 3D scene rendering |
| WebGL | Hardware-accelerated rendering |
| Canvas | Custom drawing, textures and effects |
| Web Audio API | Procedural sound and music |
| Local Storage | Local save and settings persistence |
| Pointer Events | Mouse and touchscreen input |
| Google Fonts | Handwritten typography |

### External Dependencies

The supplied HTML currently loads:

**Three.js r128**

`https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js`

**Google Fonts**

- Gochi Hand
- Patrick Hand

The game also includes its procedural PixelFX implementation directly in the HTML file.

---

## 🏗️ Project Architecture

Although distributed as a single HTML file, Doodle Ludo is organized into logical JavaScript subsystems.

### 1. LudoGame.Logic

Responsible for the core gameplay system.

- Initialize game states.
- Manage players and tokens.
- Generate dice results.
- Calculate legal moves.
- Handle token movement.
- Handle captures.
- Check winning conditions.
- Manage turn progression.
- Calculate AI bot decisions.
- Generate extended-board layouts.

### 2. LudoGame.Scene

Responsible for the 3D experience.

- Three.js scene initialization.
- Camera management.
- Board construction.
- Token rendering.
- Dice rendering.
- Input handling.
- Token movement animations.
- Board interaction.
- Resize handling.
- Rendering lifecycle.

### 3. LudoGame.UI

Responsible for the user interface.

- Main menu.
- Game setup.
- Player management.
- Game HUD.
- Pause menu.
- Settings.
- Game rules.
- Statistics.
- Game-over screen.
- Notifications and interaction feedback.

### 4. LudoGame.Storage

Responsible for local persistence.

- Save unfinished games.
- Restore previous games.
- Store settings.
- Store statistics.
- Manage player names.
- Reset saved data.

### 5. LudoGame.Audio

Responsible for browser audio.

- Procedural sound effects.
- Background music.
- Audio initialization.
- Sound controls.
- Music controls.
- Audio preference persistence.

### 6. LudoGame.Net

Responsible for online multiplayer functionality.

- User and database service integration.
- Quick matchmaking.
- Private room creation.
- Room-code joining.
- Player seat management.
- Live game-state synchronization.
- Online leaderboard.
- Inactive-player bot takeover.

### 7. LudoGame.Style

Responsible for visual styling enhancements.

- Shader uniforms.
- Rendering parameters.
- Pixel-ratio management.
- Lighting configuration.
- Stylized rendering.

### 8. PixelFX

Responsible for procedural visual effects.

- Particle systems.
- Animation utilities.
- Visual effect generators.
- Explosions and impacts.
- Fireworks and celebrations.
- Reusable effect configurations.

---

## 🚀 Getting Started

Getting started is straightforward because the current game is distributed as a single HTML file.

### Prerequisites

- Modern web browser.
- JavaScript enabled.
- WebGL-compatible graphics support.
- Internet connection for the external Three.js library and Google Fonts.

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/doodle-ludo.git
```

### 2. Navigate to the Project

```bash
cd doodle-ludo
```

### 3. Prepare the HTML File

Rename the supplied game file to:

```text
index.html
```

### 4. Run the Game

Open `index.html` in your browser.

For local static hosting, you can also use Python:

```bash
python -m http.server 8000
```

Open:

```text
http://localhost:8000
```

### 5. Start Playing

- Select Play.
- Configure your players.
- Select a game mode.
- Choose bot difficulty.
- Start your match.

No separate frontend build process or npm installation is needed for the current standalone local gameplay.

---

## 🌐 Online Multiplayer

The online subsystem currently provides cooperative online gameplay.

### Available Functionality

- Quick match.
- Private rooms.
- Five-character room codes.
- Player lobby.
- Online game-state synchronization.
- Bot-filled empty seats.
- Online leaderboard.

### Online Requirements

Online gameplay uses the host environment's services through:

```javascript
window.claude.use('db')
window.claude.use('user')
```

It requires:

- A compatible runtime.
- A signed-in user.
- Database access.
- Appropriate Contributor permissions for players.

### GitHub Pages Compatibility

The standalone local game can be hosted on GitHub Pages.

However, the existing online multiplayer system is not a self-contained backend and does not automatically work on GitHub Pages.

An independent backend and appropriate real-time synchronization service would be required to make online multiplayer portable to standard hosting environments.

---

## 📱 Responsive Design

Doodle Ludo includes responsive UI and canvas rendering behavior.

### Responsive Features

- Flexible menu layouts.
- Viewport-aware game interface.
- Touch-friendly controls.
- Mobile-oriented safe-area handling.
- Mouse and touch interaction.
- Responsive canvas resizing.
- Camera adjustment based on screen dimensions.
- Device-pixel-ratio management.

### Rendering Considerations

The Three.js renderer uses:

- Antialiasing.
- High-performance power preference.
- A capped device pixel ratio.
- Resize and orientation listeners.
- ResizeObserver support where available.

Actual rendering performance depends on the user's browser, device, GPU and display resolution.

---

## 📂 Project Structure

The current implementation is packaged as a single HTML application.

```text
doodle-ludo/
│
├── index.html
│
└── README.md
```

The HTML file contains the application markup, styles and JavaScript systems.

Internally, the JavaScript is organized into logical components:

```text
Doodle Ludo
│
├── Application
│
├── LudoGame
│   │
│   ├── Logic
│   │   ├── Game State
│   │   ├── Dice System
│   │   ├── Legal Moves
│   │   ├── Token Movement
│   │   ├── Captures
│   │   └── AI Bot Decisions
│   │
│   ├── Scene
│   │   ├── Three.js Renderer
│   │   ├── Board
│   │   ├── Tokens
│   │   ├── Dice
│   │   ├── Camera
│   │   └── Animations
│   │
│   ├── UI
│   │   ├── Main Menu
│   │   ├── Game Setup
│   │   ├── HUD
│   │   ├── Settings
│   │   ├── Statistics
│   │   └── Game Over
│   │
│   ├── Storage
│   │
│   ├── Audio
│   │
│   ├── Net
│   │
│   └── Style
│
└── PixelFX
    ├── Particle Systems
    ├── Animation Utilities
    └── Visual Effects
```

This diagram represents the logical architecture, not separate files.

---

## 🗺️ Project Status

| Feature | Status |
|---|---|
| Classic Ludo Gameplay | ✅ Implemented |
| 2–4 Player Setup | ✅ Implemented |
| Human and Bot Players | ✅ Implemented |
| Easy AI | ✅ Implemented |
| Normal AI | ✅ Implemented |
| Hard AI | ✅ Implemented |
| Co-op Team Mode | ✅ Implemented |
| Big Board Mode | 🟡 Beta |
| 2–16 Player Big Board | 🟡 Experimental |
| 3D Board Rendering | ✅ Implemented |
| Animated Dice | ✅ Implemented |
| Token Animations | ✅ Implemented |
| PixelFX System | ✅ Implemented |
| Procedural Audio | ✅ Implemented |
| Background Music | ✅ Implemented |
| Local Save System | ✅ Implemented |
| Statistics | ✅ Implemented |
| Accessibility Options | ✅ Implemented |
| Online Multiplayer | ⚙️ Runtime-dependent |
| Private Online Rooms | ⚙️ Runtime-dependent |
| Online Leaderboard | ⚙️ Runtime-dependent |
| Independent Multiplayer Hosting | 🔮 Future Improvement |

**Legend**

- ✅ Implemented in the supplied source.
- 🟡 Beta or experimental.
- ⚙️ Requires a compatible runtime or service.
- 🔮 Potential future improvement.

---

## 🔮 Future Improvements

Doodle Ludo is an evolving browser-game project.

Potential areas of development include:

### Gameplay

- Further refine Big Board gameplay.
- Introduce additional board variations.
- Add new gameplay challenges.
- Improve multiplayer room management.
- Expand player customization.

### AI

- Improve bot decision-making.
- Introduce more advanced tactical evaluation.
- Improve strategic cooperation between team bots.
- Add additional AI difficulty profiles.

### Visuals

- Additional board themes.
- Custom token skins.
- More animation variations.
- Additional particle effects.
- Improved victory celebrations.
- Expanded visual customization.

### Performance

- Optimize rendering on lower-end hardware.
- Improve mobile GPU performance.
- Reduce unnecessary rendering work.
- Improve memory management.
- Optimize visual-effect workloads.

### Multiplayer

- Develop an independent multiplayer backend.
- Improve room lifecycle management.
- Expand matchmaking.
- Improve connection recovery.
- Add more multiplayer options.

### Testing and Reliability

- Add automated game-logic tests.
- Expand edge-case testing.
- Validate extended-board interactions.
- Improve accessibility testing.
- Test across browsers and devices.

---

## 🤝 Contributing

Contributions and suggestions are welcome!

Doodle Ludo is a project where game development, interactive design, 3D rendering and JavaScript come together.

You can contribute through:

- Improving gameplay mechanics.
- Improving bot intelligence.
- Optimizing Three.js rendering.
- Improving mobile performance.
- Enhancing accessibility.
- Creating additional visual effects.
- Improving the UI and UX.
- Fixing bugs.
- Suggesting new game modes.

### Contribution Workflow

1. Fork the repository.
2. Create a feature branch.
3. Make your changes.
4. Test your implementation.
5. Commit your changes.
6. Open a pull request.

Example:

```bash
git checkout -b feature/new-game-mode
```

Commit your changes:

```bash
git add .
git commit -m "Add new game mode"
git push origin feature/new-game-mode
```

Then create a pull request with a description of your changes.

---

## 🐛 Bug Reports

Found an issue?

Please create a GitHub Issue with:

- A clear description of the problem.
- Steps to reproduce it.
- Expected behavior.
- Actual behavior.
- Browser and device details.
- Screenshots or screen recordings, when available.

For performance problems, include hardware and browser information where possible.

---

## 📜 License

No license has been specified in the supplied project source.

A license should be added to the repository before granting permissions for public reuse, modification or redistribution.

---

## ❤️ Acknowledgements

Doodle Ludo is built using browser-based technologies and the open-source development ecosystem.

Special appreciation to:

- [Three.js](https://threejs.org/) - 3D graphics library.
- [MDN Web Docs](https://developer.mozilla.org/) - Web development documentation.
- [WebGL](https://www.khronos.org/webgl/) - Browser graphics technology.
- [Google Fonts](https://fonts.google.com/) - Typography resources.

---

## 🎲 Final Words

A familiar board game. A different visual experience. Countless dice rolls.

Doodle Ludo brings together traditional gameplay, AI opponents, cooperative strategy, procedural animations and interactive 3D graphics in a browser-based project.

Built with creativity, experimentation and a passion for game development.

**Roll it. Race it. Doodle it.**

⭐ If you enjoy the project, consider giving the repository a star and sharing your feedback!

---

<p align="center">
  <strong>🎲 DOODLE LUDO</strong>
  <br>
  <em>Roll it. Race it. Doodle it.</em>
</p>
