#Qwirk (Go variant)

The goal of Qwirk is to be similar in gameplay to RoboRally, a Wizards of the Coast game I played when I was a kid. The basic idea is that you and a few other "robots" are in a factory trying to reach several objectives. Unlike other games, you must define your actions in small sets before they can be carried out (like programming). Unexpected changes in the board or other character's actions may interfere with your own causing trouble during the execution of your program. Fun times.

Currently there isn't much to run. Eventually there will be three primary components: a game engine, a route engine, and a game client.

## Game Engine

The game engine should manage an instance of the game for a group of players. It manages the game resources (cards, board actions, player status, and so on) and enforces the rules.

## Route Engine

The route engine just manages websockets and connects them to game engine processes.

## Game Client

This is the front end piece that will be used by players to actually interact with the game.