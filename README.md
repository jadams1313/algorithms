# Algorithms Repository

A comprehensive collection of fundamental algorithms with C++ implementations, based on:
- **Algorithms** by Dasgupta, Papadimitriou, and Vazirani
- **Artificial Intelligence: A Modern Approach** by Russell and Norvig (Search Algorithms)

## 🎯 Purpose

This repository provides battle-tested algorithm implementations with:
- Clean, readable C++ code
- Detailed modification guides for interview problems
- Real-world examples and use cases
- Time/space complexity analysis

## 📚 Repository Structure

Each algorithm includes:
- `algorithm_name.cpp` - Base implementation
- `README.md` - Theory, modifications, and problem-solving patterns
- `examples/` - Practical applications and variations

```
algorithms-repo/
├── divide-and-conquer/
│   ├── merge-sort/
│   ├── quick-sort/
│   ├── binary-search/
│   ├── master-theorem/
│   └── fast-fourier-transform/
├── greedy/
│   ├── huffman-coding/
│   ├── minimum-spanning-tree/
│   ├── dijkstra/
│   └── interval-scheduling/
├── dynamic-programming/
│   ├── longest-common-subsequence/
│   ├── knapsack/
│   ├── edit-distance/
│   ├── shortest-paths/
│   └── matrix-chain-multiplication/
├── graph-algorithms/
│   ├── dfs/
│   ├── bfs/
│   ├── topological-sort/
│   ├── strongly-connected-components/
│   └── max-flow/
├── search-algorithms/
│   ├── uninformed/
│   │   ├── depth-first-search/
│   │   ├── breadth-first-search/
│   │   ├── uniform-cost-search/
│   │   └── iterative-deepening/
│   └── informed/
│       ├── a-star/
│       ├── greedy-best-first/
│       └── bidirectional-search/
├── number-theory/
│   ├── gcd-euclidean/
│   ├── modular-arithmetic/
│   └── primality-testing/
└── data-structures/
    ├── heap/
    ├── union-find/
    └── segment-tree/
```

## 🚀 Quick Start

### Compilation
```bash
g++ -std=c++17 -O2 -Wall algorithm_name.cpp -o algorithm_name
./algorithm_name
```

### Testing
Each algorithm includes test cases:
```bash
cd algorithm-name/
make test
```

## 📖 How to Use This Repository

### For Learning
1. Start with the algorithm's README to understand the theory
2. Study the base implementation
3. Review the modification patterns
4. Attempt the example problems

### For Interview Prep
1. Focus on the "Common Modifications" section in each README
2. Practice the example problems
3. Time yourself implementing variations
4. Review complexity analysis

### For Reference
- Use the search function to find specific algorithms
- Check modification patterns for similar problems
- Reference the complexity analysis tables

## 🔑 Key Algorithms by Category

### Divide and Conquer
- **Merge Sort**: O(n log n) sorting, useful for counting inversions
- **Quick Sort**: In-place sorting with average O(n log n)
- **Binary Search**: O(log n) searching in sorted arrays
- **FFT**: O(n log n) polynomial multiplication

### Greedy Algorithms
- **Dijkstra's Algorithm**: Single-source shortest paths
- **Prim's/Kruskal's**: Minimum spanning trees
- **Huffman Coding**: Optimal prefix codes
- **Interval Scheduling**: Activity selection

### Dynamic Programming
- **LCS**: Longest common subsequence - O(mn)
- **Knapsack**: 0/1 and unbounded variants
- **Edit Distance**: String similarity and transformations
- **Bellman-Ford**: Shortest paths with negative edges

### Graph Algorithms
- **DFS/BFS**: Graph traversal fundamentals
- **Topological Sort**: Ordering with dependencies
- **SCC**: Strongly connected components (Kosaraju's)
- **Max Flow**: Ford-Fulkerson, Edmonds-Karp

### Search Algorithms (AI)
- **A\***: Optimal pathfinding with heuristics
- **Uniform Cost Search**: Dijkstra variant for AI
- **Iterative Deepening**: Memory-efficient search
- **Bidirectional Search**: Meet-in-the-middle approach


## 📊 Complexity Quick Reference



## 🛠️ Building and Running

### Prerequisites
- C++17 compatible compiler (g++ 7.0+, clang++ 5.0+)
- Make (optional, for build automation)

### Individual Algorithm
```bash
cd algorithm-name/
g++ -std=c++17 -O2 -Wall algorithm_name.cpp -o algorithm_name
./algorithm_name
```

### With Examples
```bash
cd algorithm-name/examples/
g++ -std=c++17 -O2 -Wall example1.cpp -o example1
./example1
```

## 📝 Contributing Guidelines

Each algorithm should include:
1. Clean, commented C++ implementation
2. Comprehensive README with:
   - Algorithm explanation
   - Time/space complexity
   - Common modifications
   - Example problems with solutions
3. Test cases covering edge cases

## 📚 Additional Resources

- [Dasgupta et al. - Algorithms](http://algorithmics.lsi.upc.edu/docs/Dasgupta-Papadimitriou-Vazirani.pdf)
- [AIMA - Artificial Intelligence: A Modern Approach](http://aima.cs.berkeley.edu/)
- [CP-Algorithms](https://cp-algorithms.com/)
- [LeetCode](https://leetcode.com/) - Practice problems
- [Codeforces](https://codeforces.com/) - Competitive programming

## 🎯 Interview Patterns by Company

### FAANG Focus Areas
- **Google**: Graph algorithms, DP, system design with algorithms
- **Meta**: DFS/BFS variations, tree algorithms, optimization
- **Amazon**: Array/string manipulation, graph traversal, greedy
- **Apple**: Data structures, search algorithms, optimization
- **Microsoft**: DP, graph algorithms, tree problems

### Trading Firms (Jane Street, Citadel, etc.)
- Optimization algorithms
- Search algorithms with constraints
- Advanced DP
- Computational complexity analysis

## ⚡ Performance Tips
  coming soon

## 📄 License

This repository is for educational purposes. Algorithm implementations are based on published works in the public domain.

## 🤝 Acknowledgments

- Sanjoy Dasgupta, Christos Papadimitriou, Umesh Vazirani - *Algorithms*
- Stuart Russell, Peter Norvig - *Artificial Intelligence: A Modern Approach*


---

**Last Updated**: December 2025  
**Maintained by**: me! 

