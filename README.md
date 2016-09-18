# Welcome to BONE
BONE is a tool to compute backbone of satisfiable propositional formula.
In Satisfiability problem, literals that always have the assignment of TRUE in every solution of the given formula are called backbone literals. 
BONE is able to compute every backbone literal of a given formula.
## Benchmark
The random-benchmark.tar.gz contains all random benchmark used in our paper.
The industrial-benchmark1.tar.gz from industrial-benchmark26.tar.gz contains all industrial benchmark used in our paper.
## Usage
To use BONE, please download the executable file bone and execute it on a linux operating system, with the following commands:
    `chmod +x bone`
   `./bone CNFfile.cnf`
for example, if there is a cnf file named test.cnf, BONE can be executed  by :
    `./bone test.cnf`
