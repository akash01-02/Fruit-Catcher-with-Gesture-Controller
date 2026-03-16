# Fruit-Catcher-with-Gesture-Controller
Developed a real-time gesture-controlled desktop game using webcam-based hand tracking. Integrated MediaPipe hand landmark detection with OpenCV for gesture recognition and mapped movements to Pygame-based game controls, enabling interactive, hands-free gameplay.
# Fruit Catcher Game
 
A fun and interactive fruit-catching game with gesture control support.
 
## Features
 
- **Gesture Control**: Use hand gestures to control the basket using your webcam
- **Keyboard/Mouse Control**: Traditional keyboard and mouse controls
- **Particle Effects**: Visual effects for enhanced gameplay
- **Sound Effects**: Audio feedback for actions
- **Multiple Game Modes**: Full version and minimal demo version
 
## Requirements
 
- Python 3.8+
- Pygame
- OpenCV
- NumPy
- MediaPipe (for gesture control)
 
## Installation
 
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd fruit-catcher
Create a virtual environment:
bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:
bash
pip install -r requirements.txt
Usage
Run the Full Game
bash
python main.py
Run Minimal Demo (No Dependencies)
bash
python minimal_demo.py
Quick Start Menu
bash
python quick_start.py
Controls
Keyboard
Arrow Keys / A, D: Move basket
Space: Start/Pause game
ESC: Quit game
Gesture Control
Enable camera: Press 'C'
Toggle debug overlay: Press 'F1'
Open hand: Move basket horizontally
Fist: Catch fruits
Pinch: Special action
Project Structure
fruit-catcher/
├── main.py              # Main game entry point
├── minimal_demo.py      # Minimal version without dependencies
├── quick_start.py       # Quick start menu
├── gestures.py          # Gesture detection logic
├── game/                # Game modules
│   ├── __init__.py
│   ├── basket.py        # Basket logic
│   ├── fruit.py         # Fruit objects
│   └── ...
├── assets/              # Game assets (images, sounds)
├── tests/               # Test files
├── requirements.txt     # Production dependencies
├── requirements-dev.txt # Development dependencies
└── README.md           # This file
Development
Running Tests
bash
pytest tests/
Code Formatting
bash
black .
Linting
bash
flake8 .
