# randorg

![I'm So Random](https://imgs.xkcd.com/comics/im_so_random.png "I'm So Random")

Command line tool to generate '[true](https://www.random.org/randomness/)' random integers and strings via [RANDOM.ORG](https://www.random.org/)

## Installation

This tool is written in bash. Other dependencies are cURL.

Optionally copy `randorg` to `/usr/local/bin` for use anywhere.

## Basic usage

Generate random strings:
```
$ ./randorg string --num 5 --len 10 --upper --digits
7LS4SFFUDL
OMV5V2R7K6
8G3VAIJ55M
5MLYZRIR3U
6LSPCPB78L
```

Roll a dice with `n` sides:
```
$ ./randorg roll 6
4
```

Flip a coin:
```
$ ./randorg flip
Heads!
```

If used in conjunction with an automated task please refer to the RANDOM.ORG's API [usage guidelines](https://www.random.org/clients).

## Coming soon

- Picking from a hat / lottery (from file..)