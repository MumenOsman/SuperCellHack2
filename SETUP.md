# Setup & Build Instructions

## Quick Start - Play in Browser

The easiest way to play:
1. Open `web-build/V0.0.2/index.html` in your web browser
2. Allow the page to load (may take a few seconds)
3. Click "Play" and enjoy!

No installation or downloads needed.

## Prerequisites (For Development)

## Gameplay Basics

### Objective
- Explore the giant kitchen as a rabbit
- Collect carrots scattered throughout the level
- Reach different areas and discover multiple paths
- No fail states - relax and enjoy the experience!

### How to Play
1. Use controls to move and jump around the kitchen
2. Find and collect carrots by running into them
3. Explore all areas - there are multiple routes
4. Take your time and enjoy the cozy atmosphere

### Tips
- Not all carrots are easy to reach - try different routes
- Use the walls and platforms to navigate
- There's no time limit, so explore at your own pace
- Short falls won't hurt you - this is a cozy, relaxing game

### From Source
1. Clone the repository:
   ```bash
   git clone [YOUR_REPO_URL]
   cd SuperCellHack2
   ```

2. Open the project in Unity 6.2:
   - Launch Unity Hub
   - Click "Open Project"
   - Select the `SuperCellHack2` folder
   - Wait for Unity to import assets (this may take 1-2 minutes)

3. Run the game:
   - Open the main scene from `Assets/Scenes/Main.unity`
   - Press **Play** in the Unity Editor

### Building an Executable

#### Windows (.exe)
1. Go to **File > Build Settings**
2. Select **PC, Mac & Linux Standalone**
3. Set Target Platform to **Windows**
4. Click **Build**
5. Choose output folder (e.g., `Builds/Windows`)
6. Run `SuperCellHack2.exe` to play

#### macOS (.app)
1. Go to **File > Build Settings**
2. Select **PC, Mac & Linux Standalone**
3. Set Target Platform to **Mac**
4. Click **Build**
5. Choose output folder
6. Run the generated `.app` file

## Game Controls
- W, A, S, D - Move forward, left, backward, right
- Arrow Keys - Alternative movement controls
- Space - Jump (tap to jump higher)
- Shift - Dash/Sprint (for quick bursts of speed)
- Mouse - Look around (first-person view)
- ESC - Pause menu / Settings

### Camera
- Mouse movement controls camera view
- Scroll wheel - Adjust field of view (optional)

## Troubleshooting

**Unity won't load the project?**
- Make sure you're using Unity 6.2+
- Delete the `Library` folder and reopen the project

**Graphics issues?**
- Check your GPU drivers are up to date
- Reduce quality settings in game options
- Make sure your browser has hardware acceleration enabled (for WebGL)

**Game runs slowly?**
- Lower the graphics quality settings
- Close other browser tabs
- Make sure no other apps are using GPU

## Performance
- Recommended: GPU with 2GB+ VRAM, 4GB+ RAM
- Minimum: Integrated GPU, 4GB RAM
- Typical FPS: 60+ on modern hardware

## No External Dependencies
This project requires no API keys or internet for base gameplay.
The game runs completely locally (offline-friendly).
