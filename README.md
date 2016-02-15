# py-vizhash

Python Visual Hash, calculate a visual random image associated with a string.

## How it works ?

It uses a maze [generation algorithm](https://en.wikipedia.org/wiki/Maze_generation_algorithm#Depth-first_search)
at each steps it changes the color of the block with a slightly random change from the previous block.

## Usage

```
usage: identicon.py [-h] [-s SEED] [-n N] [-S SIZE] [-f FILENAME]

optional arguments:
  -h, --help            show this help message and exit
  -s SEED, --seed SEED  String to use as a seed
  -n N                  Number of blocks (default : 16)
  -S SIZE, --size SIZE  Block size (default :16)
  -f FILENAME, --filename Output filename, by default will show the image
```

## Examples

![truc-13](https://cloud.githubusercontent.com/assets/876685/13054744/ad6551ac-d40b-11e5-9aaf-7c99d5a527d9.png)
![truc-34](https://cloud.githubusercontent.com/assets/876685/13054746/b00917c2-d40b-11e5-83a4-dd6b23d6631a.png)
![truc-32](https://cloud.githubusercontent.com/assets/876685/13054747/b223e0fa-d40b-11e5-8fda-4414c24bc0ea.png)
![truc-26](https://cloud.githubusercontent.com/assets/876685/13054748/b35b97f6-d40b-11e5-8ac8-492046c369eb.png)
![truc-16](https://cloud.githubusercontent.com/assets/876685/13054749/b3fa5184-d40b-11e5-81f0-adf834992bcd.png)
![truc-48](https://cloud.githubusercontent.com/assets/876685/13054762/b702a368-d40b-11e5-9865-80ba6a541ad7.png)