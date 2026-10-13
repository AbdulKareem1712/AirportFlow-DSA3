# ✈️ AirportFlow-DSA3

### Airport Operations & Resource Management — DSA Review-1 Prototype

**AirportFlow** is a Java-based prototype that demonstrates how Data Structures and Algorithms can be applied to airport operations and resource management. The project combines string matching, suffix structures, and advanced dynamic programming through an interactive console-based application.

Developed as part of my **2nd Year, 1st Semester** coursework.

---

## 🎯 Project Objectives

- Implement advanced string-matching algorithms for flight information and alert detection.
- Explore suffix-based data structures for searching airport-related documents.
- Apply dynamic programming to name correction and resource assignment problems.
- Demonstrate multiple algorithms through a single interactive Java application.

## 🛠️ Technologies Used

- **Programming Language:** Java
- **JDK:** Java 21
- **IDE:** Eclipse
- **Version Control:** Git and GitHub

## 📚 Project Modules

### Module 1: String Algorithms

**File:** `M1_StringAlgorithms.java`

Implements string-matching algorithms to locate flight identifiers, search text, and detect airport-related alerts.

| Algorithm | Purpose |
|---|---|
| Naive String Matching | Searches for a pattern by checking possible positions |
| Knuth-Morris-Pratt (KMP) | Uses an LPS array to avoid unnecessary comparisons |
| Z-Function | Uses Z-values to identify pattern occurrences |
| Rabin-Karp | Uses rolling hashes to find candidate matches |
| Aho-Corasick | Detects multiple keywords using a trie and failure links |

**AirportFlow application:** Searches for flight identifiers such as `AI202` and detects alerts such as `delayed`, `cancelled`, `boarding`, and `diverted`.

### Module 2: Suffix Structures

**File:** `M2_SuffixStructures.java`

Implements suffix-based structures for organizing and searching airport-related text.

| Structure | Purpose |
|---|---|
| Suffix Array | Stores suffix starting positions in lexicographical order |
| LCP Array | Stores the longest common prefix lengths of adjacent suffixes |
| Suffix Automaton | Supports substring-existence queries |

**AirportFlow application:** Processes sample airport documents containing words such as `airport`, `gate`, `runway`, `passenger`, and `baggage`.

Example queries include `gate`, `runway`, and user-entered keywords.

### Module 3: Advanced Dynamic Programming

**File:** `M3_DynamicProgramming.java`

Applies dynamic programming techniques to string correction and optimization problems.

| Algorithm | Purpose |
|---|---|
| Levenshtein Distance | Measures the minimum insertions, deletions, and substitutions needed to transform one string into another |
| Damerau-Levenshtein Distance | Also accounts for adjacent character transpositions |
| Bitmask Dynamic Programming | Finds a minimum-cost assignment of flights to gates |
| Matrix Chain Multiplication | Computes the minimum scalar multiplication cost for a matrix chain |
| Optimal Binary Search Tree | Computes the minimum search cost using key frequencies |

**AirportFlow application:** Demonstrates airport-name correction, flight-to-gate assignment, matrix-chain optimization, and optimal search-tree construction.

## 🖥️ Main Application

**File:** `AirportFlow.java`

The main application provides an interactive console menu with the following options:

1. **M1 — String Algorithms:** Run string matching and alert detection demonstrations.
2. **M2 — Suffix Structures:** Explore suffix arrays, LCP arrays, and substring queries.
3. **M3 — Advanced Dynamic Programming:** Run string correction and optimization demonstrations.
4. **Complete Review-1 Demo:** Execute predefined examples from all three modules.
5. **Exit:** Close the application.

## 📂 Project Structure

```text
AirportFlow-DSA3/
├── src/
│   └── airportFlow/
│       ├── AirportFlow.java
│       ├── M1_StringAlgorithms.java
│       ├── M2_SuffixStructures.java
│       └── M3_DynamicProgramming.java
├── .gitignore
├── .classpath
└── .project
```

## ▶️ How to Run

### Prerequisites

- Java Development Kit (JDK) 21
- Eclipse IDE or another Java-compatible IDE
- Git (optional, for cloning the repository)

### Run using Eclipse

1. Clone or download this repository.
2. Import the project into Eclipse as an existing Java project.
3. Configure JDK 21 in the project build path.
4. Open `src/airportFlow/AirportFlow.java`.
5. Run the class as a Java application.
6. Enter a menu choice in the console and follow the prompts.

### Clone using Git

```bash
git clone https://github.com/AbdulKareem1712/AirportFlow-DSA3.git
```

## 🧪 Sample Scenarios

- Search for flight identifier `AI202` in a sample flight-information string.
- Detect delay and boarding alerts in text.
- Search for `gate` or `runway` in an airport document.
- Calculate the edit distance between `Hyderbad` and `Hyderabad`.
- Find a minimum-cost assignment between three flights and three gates.
- Calculate matrix-chain multiplication and optimal BST costs.

*The project uses predefined sample data and console-based demonstrations; it is an educational prototype, not a live airport management system.*

## 🚀 Learning Outcomes

- Understanding and implementing advanced string algorithms.
- Working with suffix arrays, LCP arrays, tries, and suffix automata.
- Applying dynamic programming to optimization problems.
- Organizing Java code into reusable classes and modules.
- Using Git and GitHub for source-code management and project documentation.

## 👨‍💻 Author

**Abdul Kareem**

B.Tech — Computer Science and Engineering  
2nd Year, 1st Semester

---

*Learning Data Structures and Algorithms through practical problem-solving.*
