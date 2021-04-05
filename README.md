# Universal-Chessboard
A JavaFX 8 Application that allows you to play chess variants and create your own chess variants using text files. It has been designed to support as many chess variants as possible. If it can be thought up, the Universal Chessboard can support it...within limits of course.

Version: Alpha 0.0

This application is still very much a work in progress, but it already has the following basic features implemented:
1. Moving pieces on the board with the mouse
2. Navigating through a game, undoing moves, and starting a new game
3. Loading games presets from files, with examples (loading text files with file chooser to be completed)
4. Getting the FEN Code of a position and loading board positions from FEN Code
5. Getting the current game's move sequence and appending to it using a special universalized notation (SAN is too vague)
6. The ability to flip the board perspective, flipping pieces images on the board and in the holdings when needed
7. Automatic size control for the window to prevent it from straying off the viewing screen if the board gets too big
8. The ability to reset the window's size and position
9. A specialized holdings dialog which gives a complete piece overview and can be used to drop pieces back onto the board (when drops are enabled)
10. The ability to change the colors of the board and the board highlights
11. Support for various promotion modes (Chess-like, Shogi-style, promotion by capture, and Microshogi-style)
12. Fully implemented promotion dialogs which appear automatically when a piece is eligible for promotion
13. Automatically carries out promotions that are forced without displaying dialogs
14. Help dialogs (Key Bindings and FEN Code Help Dialog completed, all others are TBC)
15. Multi-moves, which can be executed with the mouse by Ctrl-clicking intermediate squares in order and clicking the destination square normally
16. Keyboard shortcuts for many of the menu items, as well as for navigating through the game and undoing moves
17. About and License buttons in the Help menu show About and lLicense text, respectively
18. modifications.txt file provided in the documentation folder, and a corresponding Modifications tab in the Help menu which is shown automatically if modifications.txt is not empty

The project is currently being stored as an Eclipse IDE Project, which can be experimented with and run through Eclipse IDE for Java.
You will need Java 8 and EFXclipse installed in order to run it.
