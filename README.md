# TowerDefense (7-21st March)

<img src="https://i.postimg.cc/v8PYKhVG/defender-howtoplay.png" alt="alt text">

<img src="https://i.postimg.cc/nrwnQVJX/defender-gameplay.png" alt="alt text">

This project is a Tower Defense game, following specific rules:

• The player is a builder who must defend his castle,

• Enemy waves will regularly appear from one side of the playground,

• The player must buy and place buildings to block/kill enemies,

• Buildings can be offensive or defensive,

• When the castle is reached by an enemy, it takes damages,

• If the castle reaches 0 hit points, the player loses.

### Linux Installer

Clone the repository:

    git clone https://github.com/MayaHill/TowerDefense-7-21-March.git

Install CSFML

    sudo apt-get install libcsfml-dev libcsfml-doc

To compile:

    make

Update:

    git pull && make re

## How to play

    ./my_defender -h

## Launch the game

    ./my_defender [map]
    
    (Example: "./my_defender maps/map1.txt")
