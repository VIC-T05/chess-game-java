Chess Game in Java
This is a simple chess game implemented in Java. It allows two players to play chess on a console-based interface.
The game includes core chess mechanics, such as movement of pieces, check, checkmate, castling, pawn promotion, and en passant.

Features
Chessboard Representation: The game uses a matrix to represent the chessboard and pieces.
Piece Movements: Each piece follows the rules of movement according to chess regulations.
Check and Checkmate Detection: The game can detect check and checkmate situations.
Undo Move: The game allows undoing a move if it leads to an illegal situation or check for the player.
Valid Moves: The game can simulate and validate all possible moves for a piece, ensuring that moves are legal.

Prerequisites
Java 8 or higher
IDE such as IntelliJ IDEA, Eclipse, or you can use the command line

Game Flow
The game starts by displaying the chessboard on the console.
Players alternate turns, moving their pieces according to the rules of chess.
The game checks for check or checkmate conditions after every move.
The game ends when one player wins, or the game reaches a draw (stalemate, insufficient material, etc.).

Code Structure
ChessPiece Class: Contains all the pieces' properties and movement logic.
ChessMatch Class: Handles the game logic, including move validation, check, and checkmate detection.
Main Class: Starts the game and manages user input.

Contributing
If you'd like to contribute to this project, feel free to fork the repository, make changes, and submit a pull request. Contributions are always welcome!

License
This project is licensed under the MIT License - see the LICENSE file for details.
