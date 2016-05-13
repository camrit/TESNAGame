# TESNAGame

Is a serious game written in JavaFX. It simulates situations when people development software and determines how they would resolve dependencies based on Conway's Law and code ownership patterns. These situations can be found by using the TESNA tool in a real life environment: https://github.com/camrit/TESNA.git

See: http://referaat.cs.utwente.nl/conference/11/paper/6963/developing-a-serious-game-to-aid-managers-in-solving-coordination-problems-in-software-development.pdf
citation: van Veen GF. Developing a serious game to aid managers in solving coordination-problems in software development.

The game contains persons and software modules.
 Persons can be connected to each other, meaning they can communicate with each other. This connection is called a communication line.
 Software modules can be connected to each other, meaning they are dependent upon each other. This connection is referred to as a dependency.
 Persons can be connected with software modules, meaning they are working on the corresponding module. This connection is called a task connection.
