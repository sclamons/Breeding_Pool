Breeding_Pool
=============

Genetic Simulation, originally based of XKCD's what-if dnd character model of inheritance, found in Randall Monroe's book "What If"
There are two kinds of genes - multipliers and constants.  

Punnets []|C| M|
-------------------
C| max(C, C) | M*C | 
M|M * C  | always 1 (probably a fatal mutation) |

It creates some smooth variabilty with the possibility of wild jumps as well as fatal mutations. 
It works best when there are only a few multipliers in the gene pool of the species - when they get to too high of a percent, there are too many babies with fatal mutations (1's)


Currently there is a well tested genome module, a non-graphical selective breeding simulation and a graphical sandbox which is a red-queen battle between plants and herbivores.
The graphical simulation uses tkinter, but I'll probably port to pygame for performance enhancements at some point.
