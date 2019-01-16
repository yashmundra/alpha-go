# My implementation of AlphaGo
Implemented in tensorflow using APV-MCTS and the live play performance is around 3~4 amateur dan.


## Caveats
Not an exact replication of the deepmind paper , especially the value network. I trained the value network on publicly avaliable data in a supervised fashion without expensive self-play. 


### Requiments

Tensorflow == 1.0.0

Numpy >= 1.11.1

OpenCV (optional, visualization use only)

### Start a Game

1. Edit IP Address in play.py

2. run python play.py --is_server=1

3. run python play.py
