# Feature Roadmap

This project is evolving into a polished, arcade-style game experience. The current milestone is tuning settings, which will make the gameplay feel better balanced before adding more layers.

## Priority Features

### 1. Nice graphics
- Improve the visual style with richer colors, stronger contrast, and cleaner motion.
- Add animated background layers, subtle particle effects, and a more expressive robot sprite.
- Polish the HUD with clearer score feedback and a more premium game frame.

### 2. Sounds
- Add audio for jump, crash, start, and score progression.
- Keep sounds short and responsive so they reinforce actions without becoming distracting.
- Make sound volume configurable in the settings panel.

### 3. Difficulty ramp
- Gradually increase obstacle speed and spawn frequency as the player scores.
- Introduce a smooth progression curve instead of a sudden jump in challenge.
- Let the game feel fair at first and more exciting as the player improves.

### 4. Tuning settings (current task)
- Expose the core game values so they can be adjusted without editing code.
- Create a simple settings panel with sliders or toggles for:
  - jump height
  - gravity
  - obstacle speed
  - obstacle spawn rate
  - score scaling
- Add presets such as Easy, Balanced, and Hard.
- Save the selected settings locally so they persist between sessions.

## Proposed Settings Structure

### Player feel
- Jump force
- Gravity strength
- Ground height / landing feel

### Obstacle flow
- Spawn interval
- Speed curve
- Obstacle size range

### Reward pacing
- Score gain speed
- Difficulty increase rate
- Optional combo or streak bonuses

## Implementation Notes
- Keep the tuning system simple and readable.
- Use a single configuration object so the game logic stays easy to maintain.
- Make sure tuning changes immediately affect the current run for fast iteration.

## Definition of Done
- A settings panel is visible and usable.
- The game responds immediately to tuning changes.
- Default values are clearly defined.
- The player can reset to defaults.
- The experience feels more fun and more customizable than the initial prototype.
