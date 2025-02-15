# Quantum Chess Engine API
This document defines a c-style API for interacting with the Quantum Chess Engine.

# Structures
* [GameData](./api/GameData.md) : Information about the current state of a game.
* [Move](./api/Move.md) : Data used to completely describe a move.

# Functions
* [qchess_new_game](./api/qchess_new_game.md) : Create a new game.
* [qchess_delete_game](./api/qchess_delete_game.md) : Deallocate game memory.
* [qchess_do_move](./api/qchess_do_move.md) : Apply a move procedure to a game.
* [qchess_undo_move](./api/qchess_undo_move.md) : Undo the last move in a game.
* [qchess_get_game_data](./api/qchess_get_game_data.md) : Get [GameData](./api/GameData.md) for the current state of a game.
* [qchess_get_history](./api/qchess_get_history.md) : Get the move history for a game.
* [qchess_get_legal_moves](./api/qchess_get_legal_moves.md) : Get the legal moves for the current state of a game.
* [qchess_get_pairwise_bell_measures](./api/qchess_get_pairwise_bell_measures.md) : Get the [Bell correlation values](./math.md#bell-correlations) between two squares for the current state of a game.
* [qchess_get_simulator_state_size](./api/qchess_get_simulator_state_size.md) : Get simulated number of states in the game's superposition.
* [qchess_get_simulator_board_probabilities](./api/qchess_get_simulator_board_probabilities.md) : (Simulator only) Get the exact probability of each bitboard.
