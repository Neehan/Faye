Faye
======
Faye is a program to perform swift graph querying in large biologocal network databases. This project is under development. Currently you can find:

##In `data`:
- The list of unique graphs under automorphism (called *canonical graphettes*) up to 8 nodes.
- The permutaion map of each graph to its *canonical graphette* up to 8 nodes.
- The *automorphism orbits* for each *canonical graphette* up to 8 nodes.
- The *distance* matrix among the *canonical graphettes* up to 7 nodes

##In `src`
- A Database program that samples graphettes (small graphs upto 8 nodes) and lists the orbits of each nodes in `test`.
- The code to generate automorphism orbits for a given graph


Build instructions
-------------------
Just run the `Makefile`.

License
--------
You can use, modify and distribute the source code under the terms of GPL version 3. (or any later version in your opinion) See the `LICENSE` for details.
