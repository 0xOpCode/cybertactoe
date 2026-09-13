<div align="center">

  # 🎮 CyberTacToe
  ### Neon Cyberpunk Tic Tac Toe with Unbeatable Minimax AI Engine

  [![Flutter](https://img.shields.io/badge/Flutter-v3.0+-02569B?style=flat-square&logo=flutter&logoColor=white)](https://flutter.dev)
  [![Dart](https://img.shields.io/badge/Dart-v3.0+-0175C2?style=flat-square&logo=dart&logoColor=white)](https://dart.dev)
  [![AI](https://img.shields.io/badge/AI%20Engine-Minimax%20Algorithm-00F5FF?style=flat-square)](#)
  [![Platform](https://img.shields.io/badge/Platforms-Android%20%7C%20iOS%20%7C%20Web-3DDC84?style=flat-square)](#)
  [![License](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](LICENSE)
  [![Maintained](https://img.shields.io/badge/Maintained%20by-0xOpCode-orange.svg?style=flat-square)](https://github.com/0xOpCode)

  <p align="center">
    <b>A high-polish, futuristic re-imagining of Tic Tac Toe built with Flutter. Featuring custom particle animations, tactile interactions, game telemetry, and an algorithmic Minimax adversary.</b>
  </p>

</div>

---

## ⚡ Highlights & Engineering Features

- **🧠 Algorithmic Minimax AI:** Built-in game decision tree evaluating optimal moves with zero latency — completely unbeatable on maximum difficulty.
- **🎚️ Adaptive Difficulty Engine:** Switch effortlessly between *Casual*, *Challenging*, and *Cybernetic (Unbeatable Minimax)* game modes.
- **✨ Cyberpunk Visual Experience:** High-contrast neon glows, dynamic particle confetti celebrations, and fluid tactile cell animations.
- **📊 Match Analytics & History:** In-memory session telemetry tracking win/loss ratios, streaks, and match logs.
- **📱 Responsive Architecture:** Built with clean Flutter state separation (`models/`, `screens/`, `widgets/`, `ai/`) ensuring 60fps rendering across mobile screens and tablets.

---

## 🏗️ Architecture Overview

```text
lib/
├── ai/
│   └── minimax.dart           # Recursive Minimax decision tree solver
├── models/
│   ├── ai_difficulty.dart     # Difficulty state machine
│   ├── game_record.dart       # Match history data structures
│   └── game_state.dart        # Game loop & win-check evaluators
├── screens/
│   ├── home_screen.dart       # Neon cyber menu & mode select
│   └── game_screen.dart       # Active arena viewport
└── widgets/
    ├── board_widget.dart      # Dynamic 3x3 grid
    ├── cell_widget.dart       # Neon glowing cells with touch triggers
    ├── confetti_widget.dart   # Vector particle emitter
    └── score_board.dart       # Live head-to-head telemetry
```

---

## 🚀 Quick Start

### Prerequisites
- Flutter SDK (`^3.0.0`)
- Dart SDK (`^3.0.0`)

```bash
# Clone the repository
git clone https://github.com/0xOpCode/cybertactoe.git
cd cybertactoe

# Fetch Flutter dependencies
flutter pub get

# Launch on connected emulator / device
flutter run
```

---

## 👨‍💻 Author

Engineered by **[Akash Deep (0xOpCode)](https://github.com/0xOpCode)**.
Connect on **[LinkedIn](https://in.linkedin.com/in/akashdeepv)**.
