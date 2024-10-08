# Genetic Sequencing Using the Travelling Salesman Problem

## Aboout the Project

We present a novel approach to genome assembly and haplotype phasing using concepts from the Traveling Salesman Problem (TSP) and search
algorithms. Our method, called GenomeTSP, models the genome assembly problem as finding an optimal path through sequence reads, similar
to solving a TSP. A modified A* search algorithm is used to efficiently explore the assembly
graph and identify the optimal assembly path.

## How to install:

Clone the Repository:
```
git clone https://github.com/RufusAntonAlex/Genetic-Sequencing-Using-TSP.git
```
Navigate to the Directory:
```
cd Genetic-Sequencing-Using-TSP
```
Install Dependencies:
```
pip install -r requirements.txt
```
Run the Project:
```
python main.py
```

Output is saved to file "reordered_human_astar.txt"
