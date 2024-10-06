#GENETIC SEQUENCING USING THE TRAVELLING SALESMAN PROBLEM

##Aboout the Project

We present a novel approach to genome assembly and haplotype phasing using concepts from the Traveling Salesman Problem (TSP) and search
algorithms. Our method, called GenomeTSP, models the genome assembly problem as finding an optimal path through sequence reads, similar
to solving a TSP. A modified A* search algorithm is used to efficiently explore the assembly
graph and identify the optimal assembly path.

##How to install:
```
git clone https://github.com/RufusAntonAlex/Genetic-Sequencing-Using-TSP.git

cd Genetic-Sequencing-Using-TSP

pip install -r requirements.txt

python main.py
```

Output is saved to file "reordered_human_astar.txt"
