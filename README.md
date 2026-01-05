# Approximate Nearest Neighbor (ANN) Search – C++

A C++ implementation of an Approximate Nearest Neighbor (ANN) search system using
tree-based indexing for efficient similarity search on high-dimensional vectors.

---

##  Overview

This project focuses on improving nearest neighbor search performance by using
approximation techniques instead of exact brute-force comparison.  
It is suitable for large vector datasets where exact search becomes computationally expensive.

---

##  Features

- Tree-based indexing for fast ANN queries
- Modular C++ design using header and source files
- Efficient vector representation and distance computation
- Extensible architecture for experimenting with indexing strategies

---

##  Technologies Used

- C++
- STL (Standard Template Library)
- Object-Oriented Programming

---

##  Project Structure

```
ANN-Project/
├── DataVector.h
├── DataVector.cpp
├── VectorDataSet.h
├── TreeIndex.h
├── TreeIndex.cpp
├── README.md
```

---

##  Build & Run

### Compile
```bash
g++ -std=c++17 *.cpp -o ann
```

### Run
```bash
./ann
```

---

##  Use Cases

- Similarity search in vector databases
- Recommendation systems
- Information retrieval
- Machine learning preprocessing

---

##  Future Improvements

- Add support for multiple distance metrics
- Benchmark against brute-force search
- Parallelize search for large datasets
- Add unit tests

---

##  Author

**Pawan Yadav**  
Final-year undergraduate | Aspiring Software Engineer

