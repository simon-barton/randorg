# randorg

Command line tool to generate 'true' random integers and strings via [RANDOM.ORG](https://www.random.org/)

## Installation

This tool is written in bash. Other dependencies are cURL.

## Basic usage

```bash
$: ./randorg string --num 5 --len 10 --upper --digits
7LS4SFFUDL
OMV5V2R7K6
8G3VAIJ55M
5MLYZRIR3U
6LSPCPB78L
$:
```

If used in conjunction with an automated task please refer to the RANDOM.ORG's API [usage guidelines](https://www.random.org/clients).

## Coming soon

- Built in functions like coin flipping and dice rolling
- Picking from a hat / lottery (from file..)