+
+A collection of experiments for CSC 299.
+
+## Interactive maze
+
+Run `maze_game.py` to explore a freshly generated maze in the terminal. The
+script prompts you for the maze dimensions (defaults to 21×21) and accepts
+optional keyboard commands each turn.
+
+```bash
+python maze_game.py            # generate a new maze with random seed
+python maze_game.py 12345      # generate a reproducible maze using seed 12345
+```
+
+Once inside the maze use `W`, `A`, `S`, `D`, or the words `up`, `left`,
+`down`, `right` to move. Type `hint` for the next suggested move, `solve` to
+print the shortest path, or `quit` to exit the game.
 
