# ChessEngine
Python 3 UCI chess engine, initially created by [Alain Lou](https://github.com/alainlou/).

## Introduction
There are three main subtasks in this repository:
1. Board evaluation
2. Move generation using search algorithms (pruning and other heuristic analysis)
3. Opening database

This is a Universal Chess Interface engine and uses the [lichess-bot bridge](https://github.com/careless25/lichess-bot) to play on lichess.org.

## Requirements:
1. [python-chess](https://github.com/niklasf/python-chess) for board representation
2. [lichess-bot](https://github.com/careless25/lichess-bot) if you want it to play as a bot on lichess

## My own extensions
There is my plan
1. Evaluate this Engine through a Lichess Bot
2. Evaluate the value added by my own big Opening Library (and reevaluate it if needed)
3. Extends the evaluation function
4. Go to Monte-Carlo to enjoy life, and moreover fine-tune evaluation parameters (old and new)
5. If successful (and drunk !), port it to C++
