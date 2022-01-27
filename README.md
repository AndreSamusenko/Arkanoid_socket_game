# Simple web game on sockets

Just small example of multiplayer game for 2 players.
Remake of old "Arkanoid".

### To run locally on one machine
1. Run server `python server/game_server.py`
2. `python scr/game/game_main.py`
3. `python scr/game/game_main.py` in another terminal

### To run in a local network
1. Run server on host-machine
2. In _scr/game/game_main.py_ change constants HOST and PORT on params of your host-machine
3. `python scr/game/game_main.py` on 1st PC
4. `python scr/game/game_main.py`on 2nd PC

