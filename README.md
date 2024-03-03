# Event-B and ProB Project - Connect Four

## Overview
This repository contains the implementation of a Connect Four game using Event-B and ProB. The project is composed of three refined machines:

1. **Machine 1 : Turn Management:** This machine handles the turn-taking mechanism of the game.
2. **Machine 2 : Pawn Placement:** Responsible for managing the placement of pawns into each column of the game board.
3. **Machine 3 : Victory Checking:** This machine, although not yet completed, aims to check for victories in the game.

Additionally, a graphical representation of the game using ProB has been developed based on the second machine. Users will have access to the game board and can deposit a pawn into each column. After each pawn placement, automatic player change occurs.

## Features
- Implementation of Connect Four game in Event-B.
- Three refined machines to handle different aspects of the game.
- Graphical representation of the game using ProB.
- Use of Atelier B Prover to ensure correctness of the game states.

## Usage
1. Clone the repository to your local machine.
2. Ensure that Event-B and ProB are installed with Rodin, the Event-B IDE I use.
3. Run the relevant machines using Event-B.
4. Access the graphical representation using ProB and interact with the game board.

## Note
This is an academic project created to aid students from second year to university level at the University of Namur in understanding various concepts related to Event-B.

The victory checking aspect of the project is currently under development and will be completed in future iterations 🤞
