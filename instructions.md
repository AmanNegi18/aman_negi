# Scribble Clash Multiplayer Drawing Game

## Context

Scribble Clash is a browser-based multiplayer drawing and guessing game inspired by social party games. Players join a shared room, take turns drawing a secret word on a shared canvas, and compete to guess the correct word before the timer expires.

The objective of this project is to create a playable multiplayer web game that demonstrates the complete drawing-and-guessing gameplay loop while maintaining a responsive and functional user interface.

---

# Project Information

Project Name: Scribble Clash

Category: Web Development

Game Type: Multiplayer Drawing and Guessing Game

Target Audience: Casual gamers and online social groups

Primary Goal: Deliver a functional browser-based multiplayer game prototype.

---

# Brand Guidelines

Use the following colours throughout the interface.

| Colour Name | Hex Code |
| ----------- | -------- |
| Primary Blue | #3B82F6 |
| Secondary Purple | #8B5CF6 |
| Success Green | #22C55E |
| Warning Orange | #F97316 |
| Background Light | #F8FAFC |
| Text Dark | #1F2937 |
| Canvas Border | #CBD5E1 |

---

# Typography Requirements

Headings shall use Poppins Bold.

Body text shall use Inter Regular.

Fallback fonts may use Arial or Sans-serif.

---

# Assets Provided

Use the following project assets.

### resources/assets.pdf

Use this file for:

- Colour palette requirements
- Typography requirements
- UI component requirements
- Layout guidance
- Gameplay screen structure

### data/reference_image.png

Use this file as the visual reference for:

- Gameplay screen layout
- Component positioning
- Canvas placement
- Chat panel placement
- Scoreboard placement
- Player list placement

---

# Deliverables

Provide the following deliverables.

## 1. Playable Browser-Based Multiplayer Game

Format: Browser Application

Specifications:

- Supports 2–6 players
- Contains exactly 3 rounds
- Each round lasts exactly 60 seconds
- Uses real-time drawing synchronization
- Includes room creation and room joining
- Includes score tracking
- Includes final rankings screen
- Functions in the latest version of Google Chrome

## 2. README.md

Format: .md

Must contain:

- Installation instructions
- Dependency installation instructions
- Local execution instructions

## 3. package.json

Format: .json

Must contain all project dependencies.

## 4. Client Source Code

Formats:

- .html
- .css
- .js

## 5. Server Source Code

Format:

- .js

## 6. Assets Folder

Formats:

- .png
- .jpg
- .svg

---

# Core Gameplay Requirements

Create the following gameplay systems.

1. Room Creation
2. Room Joining
3. Shared Drawing Canvas
4. Real-Time Drawing Synchronization
5. Word Selection System
6. Guess Chat System
7. Round Timer
8. Score Tracking
9. Leaderboard
10. Game Over Screen

---

# Gameplay Screen Requirements

The gameplay screen shall display:

- Scribble Clash logo
- Room code
- Current round number
- Round timer
- Player list
- Scoreboard
- Shared drawing canvas
- Guess chat panel
- Current game status

---

# Room System Requirements

The game shall allow players to create a room.

The game shall allow players to join an existing room using a room code.

The game shall support between 2 and 6 players in a room.

Each room shall maintain an independent game state.

---

# Drawing System Requirements

The game shall contain a shared drawing canvas.

The active player shall be able to draw on the canvas.

Drawing actions shall be synchronized in real time for all connected players.

The drawing canvas shall support multiple colours.

The drawing canvas shall support an eraser tool.

The drawing canvas shall be cleared automatically at the beginning of each round.

---

# Drawing Tool Requirements

The drawing interface shall contain:

1. Small Brush
2. Medium Brush
3. Large Brush
4. Eraser Tool
5. Colour Picker

The active player shall be able to use all drawing tools.

The drawing tools shall only be available to the active drawing player.

---

# Word Selection Requirements

The active drawing player shall receive exactly three word options.

The active drawing player shall select one word before the round begins.

The selected word shall remain hidden from guessing players.

The selected word shall be displayed only to the active drawing player.

The game shall contain a minimum word bank of 50 words.

---

# Guessing System Requirements

Players shall be able to submit guesses through a chat interface.

Messages shall appear in real time for all connected players.

Correct guesses shall be detected automatically.

The active drawing player shall not be able to submit guesses.

The chat input shall support a minimum of 100 characters.

---

# Scoring Requirements

The game shall track player scores.

The game shall display a live scoreboard.

A player shall receive 10 points for a correct guess.

The active drawing player shall receive 5 points if at least one player correctly guesses the selected word during the round.

The game shall display final rankings when the game ends.

---

# Round System Requirements

The game shall use a round timer.

Each round shall last exactly 60 seconds.

The game shall contain exactly 3 rounds.

The active drawing player shall rotate after each round.

The game shall automatically proceed to the next round.

---

# Gameplay Sequence

The game flow shall follow the sequence below.

1. Create Room
2. Join Room
3. Select Word
4. Draw
5. Submit Guesses
6. Award Points
7. Start Next Round
8. Display Final Rankings

---

# User Interface Requirements

The interface shall display the room code.

The interface shall display the round number.

The interface shall display the timer.

The interface shall display the player list.

The interface shall display the scoreboard.

The interface shall display the drawing canvas.

The interface shall display the chat panel.

The interface shall use the specified colour palette.

The interface shall remain usable on desktop browsers.

---

# Technical Requirements

## Frontend

- HTML5
- CSS3
- JavaScript

## Backend

- Node.js
- Express.js

## Real-Time Communication

- Socket.IO

---

# Browser Compatibility

The game shall function in the latest version of Google Chrome.

---

# Source Code Requirements

Provide the complete source code.

Provide a README.md file.

Provide package.json.

The game shall run locally after following the README instructions.

---

# Export Requirements

Provide complete source code.

Provide package.json.

Provide README.md.

Provide all required assets.

The project shall run locally after dependency installation.

---

# File Naming Convention

Use the following naming pattern.

```text
scribble_clash_[filename]
```

Examples:

```text
scribble_clash_readme.md
scribble_clash_package.json
```

---

# Delivery Folder Structure

```text
Scribble_Clash/
│
├── README.md
├── package.json
│
├── client/
│
├── server/
│
└── assets/
```

---

# Scope Boundaries

Do not create mobile applications.

Do not create voice chat functionality.

Do not create video chat functionality.

Do not create payment systems.

Do not create user account systems.

Do not create matchmaking services.

Do not create AI-powered features.

Do not create advertisements.

Do not create social media integrations.

Do not create production-scale hosting infrastructure.

---

# Delivery Terms

This is a single-delivery prototype task.

No revision rounds are required for acceptance.

Estimated implementation effort is 8–16 hours.

---

# Acceptance Gates

- A room can be created successfully.
- A room can be joined successfully.
- The game supports 2–6 players.
- Drawing actions synchronize between connected players.
- The active player can select one word from three choices.
- The game contains a minimum word bank of 50 words.
- The selected word remains hidden from guessing players.
- Players can submit guesses.
- Correct guesses are detected automatically.
- A correct guess awards 10 points.
- The drawer receives 5 points when at least one player guesses correctly.
- The chat input supports at least 100 characters.
- Scores update correctly.
- The timer functions correctly.
- Each round lasts 60 seconds.
- The game contains exactly 3 rounds.
- Player turns rotate correctly.
- The game ends after three rounds.
- Final rankings are displayed.
- The gameplay screen contains a drawing canvas.
- The gameplay screen contains a player list.
- The gameplay screen contains a scoreboard.
- The gameplay screen contains a chat panel.
- The gameplay screen contains a room code display.
- The gameplay screen contains a round timer.
- The drawing tools include small, medium, and large brush sizes.
- The drawing tools include an eraser tool.
- The drawing tools include a colour picker.
- The project includes complete source code.
- The project includes a README.md file.
- The project includes a package.json file.
- The game runs locally using the provided instructions.