Tic Tac toe game implementation using minimax and alpha-beta pruning:
@author Arjun Dhuliya
Run the python file ttt.py using python3 ttt.py
************* Tic Tac Toe ****************************************
Human uses X marker and Computer uses O marker
User is required to read the message and enter next move
User input format:
1  | 2 | 3
-----------
4  | 5 | 6
-----------
7  | 8 | 9
For Example user wants to mark first row and second column input should be 2
For Example user wants to mark Third row and second column input should be 8
******************************************************************
User has to input the grid number he wants to drop his game marker to, for example if user want to mark
the middle grid, which is row 2 and column 2. user just inputs 5 as shown above.

Game play:
Once you run python file ttt.py
Game describes instructions, follow on screen instructions.
Human player takes the first turn
After each move is played new updated state of game board is shown.
If Game finishes appropriate message is show.
If computer wins 'COMPUTER WON'
If player wins 'PLAYER WON'
In case of a draw "DRAW" is displayed

SAMPLE GAME PLAY:
Game 1
************* Tic Tac Toe ****************************************
Human uses X marker and Computer uses O marker
User is required to read the message and enter next move
User input format:
1  | 2 | 3
-----------
4  | 5 | 6
-----------
7  | 8 | 9
For Example user wants to mark first row and second column input should be 2
For Example user wants to mark Third row and second column input should be 8
******************************************************************

  |   |
----------
  |   |
----------
  |   |

For Above board enter your move as grid# :4
  |   |
----------
X |   |
----------
  |   |

Using MiniMax:
		total states explored: 34312
		Next Move: 0
Using AlphaBeta:
		total states explored: 4581
		Next Move: 0
O |   |
----------
X |   |
----------
  |   |

For Above board enter your move as grid# :6
O |   |
----------
X |   | X
----------
  |   |

Using MiniMax:
		total states explored: 441
		Next Move: 4
Using AlphaBeta:
		total states explored: 168
		Next Move: 4
O |   |
----------
X | O | X
----------
  |   |

For Above board enter your move as grid# :3
O |   | X
----------
X | O | X
----------
  |   |

Using MiniMax:
		total states explored: 13
		Next Move: 8
Using AlphaBeta:
		total states explored: 13
		Next Move: 8
O |   | X
----------
X | O | X
----------
  |   | O

COMPUTER WON



GAME 2
************* Tic Tac Toe ****************************************
Human uses X marker and Computer uses O marker
User is required to read the message and enter next move
User input format:
1  | 2 | 3
-----------
4  | 5 | 6
-----------
7  | 8 | 9
For Example user wants to mark first row and second column input should be 2
For Example user wants to mark Third row and second column input should be 8
******************************************************************

  |   |
----------
  |   |
----------
  |   |

For Above board enter your move as grid# :8
  |   |
----------
  |   |
----------
  | X |

Using MiniMax:
		total states explored: 34312
		Next Move: 1
Using AlphaBeta:
		total states explored: 6893
		Next Move: 1
  | O |
----------
  |   |
----------
  | X |

For Above board enter your move as grid# :3
  | O | X
----------
  |   |
----------
  | X |

Using MiniMax:
		total states explored: 936
		Next Move: 6
Using AlphaBeta:
		total states explored: 520
		Next Move: 6
  | O | X
----------
  |   |
----------
O | X |

For Above board enter your move as grid# :9
  | O | X
----------
  |   |
----------
O | X | X

Using MiniMax:
		total states explored: 29
		Next Move: 5
Using AlphaBeta:
		total states explored: 25
		Next Move: 5
  | O | X
----------
  |   | O
----------
O | X | X

For Above board enter your move as grid# :1
X | O | X
----------
  |   | O
----------
O | X | X

Using MiniMax:
		total states explored: 2
		Next Move: 4
Using AlphaBeta:
		total states explored: 2
		Next Move: 4
X | O | X
----------
  | O | O
----------
O | X | X

For Above board enter your move as grid# :4
X | O | X
----------
X | O | O
----------
O | X | X

DRAW
