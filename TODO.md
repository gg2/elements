DESIGN DOC
==========

Specs:
------

- board: 11×11
- 30 ea color piece (120 total)
- 2-4 players
- Player start positions
  - 2 player: across center space from ea other
  - 3-4 player: ea are 3rd spaces from corner,then 3rd space in
- No start pieces.
- Draw up to 4 pieces: 1 move + 4 pieces <---> 5 moves + 0 pieces
- Win conditions: trap player to your right (no valid moves)

TODO:
-----


- Instructions
  - \+ PDF
- Board
- Player Pieces
  - Cream
  - Green
  - Lilac
  - Brown
- Elemental Pieces
  - Earth
  - Water
  - Fire
  - Air
- Initial Setup
  - Pick number of players
  - Name entry
  - Pick player piece
  - Place players on board
- Mixing bag of all pieces
  - Varying pieces/movement
  - Pieces selection
- Move count
- Picked element pieces
- Piece pick-up/replacement (in hand/put it back)
  - Player piece
  - Element piece
- Movement Rules
  - Blocking (other players, fire/earth/water, earth mountain ranges, edge of board)
  - Air jumps
  - Forgoing remaining moves
- Element Placement Rules
- Element Interaction Rules
- Move Preview (on hover)
- Win Rules
  - Player target, if 3+ players

- Start new game (/)
- Detect number of players online
- Associate IP Address/Browser Id to players
- Save status (/Hex64EncodingOfStateObject?)
  - Replayability <- add each State encoding to State (-> history!)
- Turn switching
  - Player order
  - Current player saved in state
- Communicate status (/REST_Hex64Encoding?)
  - How to update?
