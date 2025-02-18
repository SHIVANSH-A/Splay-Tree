# Splay Tree Implementation in Java

## Overview
This project implements a **Splay Tree** in Java, a self-adjusting binary search tree that brings recently accessed nodes closer to the root using **splaying** operations. The project includes functionalities like insertion, searching, deletion, level-order traversal, and a visual representation of the tree structure.

## Features
- **Insertion**: Adds a new key and splays it to the root.
- **Search**: Finds a key and splays it to the root; if not found, brings the closest key to the root.
- **Deletion**: Removes a key if it exists and reorganizes the tree accordingly.
- **Level Order Traversal**: Prints the tree in a breadth-first manner.
- **Tree Structure Print**: Displays the tree structure visually in the console.
- **Interactive Console Application**: Allows users to interact with the tree via a menu-driven interface.

## Technologies Used
- Java
- Data Structures (Binary Trees, Queues)

## How to Run
1. Clone this repository or download the source code.
2. Open a terminal and navigate to the project directory.
3. Compile the Java files:
   ```sh
   javac SplayTree.java SplayTreeApp.java
   ```
4. Run the application:
   ```sh
   java SplayTreeApp
   ```

## Usage
Upon running the program, the tree is initialized with the elements: `10, 20, 30, 40, 50`. The user can then interact with the tree using the menu:
- **1. Insert**: Enter a key to add it to the tree.
- **2. Search**: Enter a key to search for it; the tree will splay the key or the closest key to the root.
- **3. Delete**: Enter a key to remove it from the tree.
- **4. Level Order Traversal**: Prints the tree level-wise.
- **5. Exit**: Terminates the program.

## Example Output
```
Inserting initial elements: 10, 20, 30, 40, 50
Initial Tree Structure:
        /----- 50
       |      /----- 40
 /----- 30
 |      \----- 20
 \----- 10

Menu:
1. Insert
2. Search
3. Delete
4. Level Order Traversal
5. Exit
Enter your choice: 
```

## Splay Tree Operations Explained
### Splaying
A key operation in the Splay Tree, which moves a node to the root using **rotations**:
- **Zig**: Single right rotation (left child becomes root).
- **Zag**: Single left rotation (right child becomes root).
- **Zig-Zig/Zag-Zag**: Double rotations for balancing.

## Future Enhancements
- GUI-based visualization of splay tree operations.
- Persistent storage of tree data.

## Author
Developed by SHIVANSH DUBEY,SUJAL NIMJE,TEJAS BARDE,VANSH POTPOSE.
