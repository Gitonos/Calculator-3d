# 3D Chess Game

A fully-featured chess game built with vanilla JavaScript and modern web technologies. This project transforms the original calculator application into an interactive chess gaming experience.

## Features

### ✅ Core Chess Functionality
- **Complete Chess Rules**: All standard chess pieces with proper movement validation
- **Turn-Based Gameplay**: Alternating white and black player turns
- **Visual Feedback**: Selected pieces and valid moves are highlighted
- **Pawn Promotion**: Automatic promotion to queen when pawns reach the end
- **Move History**: Complete game history with algebraic notation

### ✅ User Interface
- **Responsive Design**: Works on desktop and mobile devices
- **Intuitive Controls**: Click to select pieces and make moves
- **Real-Time Status**: Current player display and game state
- **Clean UI**: Modern dark theme with professional styling

### ✅ AI Opponent
- **Basic AI**: Toggle-able computer opponent for single-player games
- **Random Strategy**: AI makes random valid moves (can be enhanced)
- **Automatic Play**: AI moves after a 1-second delay for better UX

### ✅ Game Management
- **Save/Load**: Persist games to local storage
- **New Game**: Reset to initial board state
- **Move Validation**: Prevents illegal moves
- **Game State**: Track current player, selections, and history

### ✅ Audio Feedback
- **Move Sounds**: Audio feedback when pieces are moved
- **Web Audio API**: Procedural sound generation (no external files)

## How to Play

1. **Start a Game**: The game begins with white to move
2. **Select a Piece**: Click on any of your pieces to select it
3. **Make a Move**: Click on a highlighted square to move the selected piece
4. **AI Mode**: Toggle the AI button to play against the computer
5. **Save Progress**: Use Save/Load buttons to preserve your game

### Controls
- **Click**: Select pieces and make moves
- **New Game**: Reset the board to starting position
- **AI Toggle**: Switch between human vs human and human vs AI
- **Save**: Store current game state in browser storage
- **Load**: Restore previously saved game

## Technical Implementation

### Architecture
- **Modular Design**: Separated game logic from UI rendering
- **Chess Logic Module**: Handles move validation and game rules
- **Game State Management**: Centralized state with functional updates
- **Event-Driven**: Click handlers for user interaction

### Technologies Used
- **Vanilla JavaScript**: No external framework dependencies
- **HTML5**: Semantic markup and modern web standards
- **CSS3**: Advanced styling with gradients and animations
- **Web Audio API**: Procedural sound generation
- **Local Storage**: Game persistence

### Chess Rules Implemented
- ✅ **Pawn**: Forward movement, diagonal capture, double-move from start
- ✅ **Rook**: Horizontal and vertical movement
- ✅ **Knight**: L-shaped movement pattern
- ✅ **Bishop**: Diagonal movement
- ✅ **Queen**: Combined rook and bishop movement
- ✅ **King**: One square in any direction
- ✅ **Path Blocking**: Pieces cannot jump over others (except knight)
- ✅ **Capture Rules**: Cannot capture own pieces
- ✅ **Pawn Promotion**: Automatic queen promotion

## Getting Started

### Running the Game
1. Open `index.html` in any modern web browser
2. No installation or build process required
3. Game runs entirely in the browser

### Browser Compatibility
- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## Future Enhancements

### Planned Features
- **Advanced AI**: Implement minimax algorithm with position evaluation
- **3D Visualization**: Add Three.js 3D board rendering
- **Special Moves**: Castling, en passant capture
- **Check Detection**: Highlight when kings are in check
- **Checkmate Logic**: Automatic game end detection
- **Online Multiplayer**: WebSocket-based remote play
- **Game Analysis**: Move suggestion and position evaluation
- **Chess Puzzles**: Built-in tactical training
- **Theme Customization**: Multiple board and piece themes

### Code Structure
```
index.html
├── Chess Logic Module (game rules and validation)
├── Game State Management (centralized state)
├── UI Rendering (board display and updates)
├── Event Handling (user interactions)
├── AI Implementation (computer opponent)
└── Audio System (move sounds)
```

## Development

### Key Functions
- `ChessLogic.createInitialBoard()`: Sets up starting position
- `ChessLogic.isValidMove()`: Validates move legality
- `ChessLogic.makeMove()`: Executes moves and updates board
- `handleSquareClick()`: Processes user clicks
- `makeAIMove()`: Computer move generation
- `renderBoard()`: Updates visual display

### Contributing
1. Fork the repository
2. Make your changes
3. Test thoroughly
4. Submit a pull request

## License

This project is open source and available under the MIT License.

---

**Live Demo**: [https://gitonos.github.io/Calculator-3d/](https://gitonos.github.io/Calculator-3d/)

Transform your web browser into a chess battleground! 🏰♟️👑
