# Cache Simulator

## Overview
* **Year:** 2019
* **Language(s):** Java
* **Discipline(s):** Computer Architecture, Computer Engineering, Computer Science
* **Keywords:** Associativity, Cache, Cache Simulator, Cache Size, FIFO, LRU, Replacement Policy, Write-Back, Write-Through

## Description
*Cache Simulator* is a Java program that simulates a simple cache system with various inputs, including cache size, replacement policy, associativity and write-back policy.

These inputs are then used to analyze a given file that contains a list of memory accesses. In the file, each line contains (a) the type of access (read or write), and (b) a memory address. The simulator then takes this information and outputs useful statistics regarding the state of the cache system, including the number of hits, misses, and their ratios.

The following are the inputs used for this program:

1. **Cache Size:** The size of the cache system (in bytes).
2. **Associativity:** The associativity of the cache system.
3. **Replacement Policy:** Uses 0 for a Least-Recently Used (LRU) Policy, and 1 for a First-In, First-Out (FIFO) Policy.
4. **Write-Back Policy:** Uses 0 for Write-Through, and 1 for Write-Back.
5. **Input File:** The given memory access list file.

Further, these are the specified output statistics for the simulator:

1. Miss Ratio for the Cache
2. Number of Writes to Memory
3. Number of Reads from Memory

The following are the memory access input files:

1. MiniFE.t
2. XSBench.t

Note: To use these files, download them and move them to the same directory as CacheSimulator.java.
