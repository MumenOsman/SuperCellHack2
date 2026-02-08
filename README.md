#  Almost There

Hop into a cozy 3D parkour adventure! Play as a curious rabbit exploring a familiar, oversized world. Leap across platforms, discover hidden paths, and collect carrots at your own pace. This is a fully playable parkour experience with hand-crafted level design.

## Gameplay
- Parkour-based movement (jump, dash, bounce)
- Collect carrots to progress through cozy micro-missions
- Hand-crafted level design with multiple routes to explore
- No fail states, designed for flow and relaxation

## AI Design (Planned)
AI is designed to optimize level design in real-time—this is a **planned system** being developed:
- Would learn skill through movement and completion patterns
- Would adjust carrot placement and route difficulty dynamically
- **Current Build:** Core gameplay is fully playable without AI; AI system in development

See [AI_DESIGN.md](Docs/AI_DESIGN.md) for details on planned features.

## Art Direction
- Soft, toy-like proportions
- Pastel colors and warm lighting

![DALL·E 2026-02-08 14 14 00 - A cozy 3D game scene rendered in warm, soft lighting with the same pastel, clean color style as before  In the center, a curious, fluffy brown cartoon](https://github.com/user-attachments/assets/2af62f76-e5e8-4131-999d-49b2e64ccaa8)

  

AI-generated art was used for **concept and reference only**.

## Tech Stack
- Unity (3D)
- AI: Gemini, Claude and DALL·E for game art
- Tools: Google Antigravity
- Target: Hackathon prototype

## Play Now
Play "Almost There" directly on itch.io:

https://mumenosman.itch.io/almost-there

No installation needed - plays in your browser!

## Submission Documents
For detailed information, see:
- **[SETUP.md](SETUP.md)** — Game controls and setup instructions
- **[IMPLEMENTATION.md](IMPLEMENTATION.md)** — AI technical architecture & design
- **[DOCS/](Docs/)** — Game design, AI design, art sources, story

**Play the Game:** https://mumenosman.itch.io/almost-there

## Technical Details

### Unity Version
- **Unity 6.2** (or later)
- Built as Windows executable (.exe)
- No external API keys required for base gameplay

### Current Build Status
- Gameplay: Fully playable parkour mechanics
- Level Design: Hand-crafted cozy kitchen environment
- Carrot Collection: Complete core gameplay loop
- AI System: Planned but not yet implemented

See [AI_DESIGN.md](Docs/AI_DESIGN.md) for details on planned adaptive difficulty system.

### Performance
- Runs smoothly on modern hardware (60+ FPS)
- Minimal memory overhead (<50MB)
- Async AI response handling (no gameplay blocking)


## Team & Credits
- **Development:** Mumen, Maab
- **Art & Design:** Mumen, Maab
- **Tools Used:**
  - Unity 6.2 (game engine)
  - Claude (level design optimization & concept development)
  - DALL-E (concept art & environmental inspiration)


## How to Get Started

**Best Option: Play on itch.io**
1. Visit: https://mumenosman.itch.io/almost-there
2. Click "Run game" in your browser
3. Enjoy playing!

**Option 2: Play from Source (Requires Unity 6.2)**
1. Clone this repository
2. Open in Unity 6.2
3. Load the main scene
4. Press Play

For detailed setup, including controls and gameplay tips, see [SETUP.md](SETUP.md).

## Project Structure
```
Almost-There/
├── Assets/
│   ├── Scenes/        # Game scenes
│   ├── Scripts/       # C# gameplay logic
│   ├── Models/        # 3D models (rabbit, kitchen, carrots)
│   ├── Animations/    # Character and UI animations
│   ├── UI/            # UI prefabs (HUD, menus)
│   └── Prompts/       # AI system design documents
├── web-build/
│   └── V0.0.2/        # WebGL playable build (play in browser!)
├── Docs/              # Design documentation
│   ├── AI_DESIGN.md   # Planned AI system
│   ├── GAME_DESIGN.md # Core gameplay design
│   ├── Story.md       # Game narrative
│   └── ART_SOURCES.md # Art references
├── SETUP.md           # Dev setup guide
├── IMPLEMENTATION.md  # AI architecture (planned)
└── README.md          # This file
```

## Contact & Feedback
We'd love to hear your thoughts! Feedback on the AI's tone, gameplay flow, or cozy aesthetics is welcome.
contact at: https://www.linkedin.com/in/mumenosman/

---

**Made with care for SuperCell AI Hackathon — 2026**

