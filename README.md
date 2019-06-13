# Cooperative Agents - Search Algorithms

This project consists basically in creating 2 agents that cooperate to live as long as possible in a world where they need certain types of food to survive. These agents plan their actions and execute them by performing an A* search to their objective position. The cooperative setting is enforced through a message system between the two agents.

### To run the game you need:

* Python >= 3.5
* pygame >= 1.9.2b6

Python 3.5+ should be installed in any relatively recent Linux distribution.
To install pygame for python3 you may try using pip3:
    sudo pip3 install pygame

#### Run command examples:
```
python3 start.py                  # play the game with Agent1 on a random world.
python3 start.py -m mapa4.bmp     # use a specified world map.
python3 start.py -s StudentAgent  # This is the intelligent agent (*instead of random default one*).
python3 start.py -d 1             # show a log of information messages (and above).
python3 start.py -d 0 -v          # run fast without video, show debug log
```
