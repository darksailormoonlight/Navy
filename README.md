# Navy

## Table of content
* [Introduction](https://www.github.com/NaadiQmmr/Navy#Introduction)
* [Features](https://www.github.com/NaadiQmmr/Navy#Features)
* [How to run it](https://www.github.com/NaadiQmmr/Navy#How%20to%20run%20it)
* [Going further](https://www.github.com/NaadiQmmr/Navy#Going%20further)
* [Contributors](https://www.github.com/NaadiQmmr/Navy#Contributors)

## Introduction

The Navy project aims to learn us how to use the kill function, and therefore send some signals to comunicate between processes.
You have to provide a map, which is a file containing your boats dispositions. The map needs to be configured like :

```
2:B1:B2
3:C1:E1
4:H1:H5
```

Obviously, the boats must not overlap.
The first number corresponds to the length's boat. The first coordinates corresponds to where the boat begins at, and the seconds is to notify its end : it is useful 
for the direction (either horizontal or vertical) of the boat.

## Features
This project aimed at make us learn the signal between process, therefore we are using `sigaction` wrapper.

## How to run it

To start : open two tabs, for the first one run ./navy map ;
you pid will appear, and for the second one just run : ./navy map pid_player1.

Then, enter some coordinates in order to sink your opponent !

## Going further
Maybe an ncurses application !

## Contributors
* [Adina C.](https://www.github.com/NaadiQmmr)
* [Bogdan G.](https://www.github.com/bogdzn)


Enjoy!
