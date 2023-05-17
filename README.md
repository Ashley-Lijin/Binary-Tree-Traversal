<h2 align='center'>Tree Traversals (Inorder, Preorder and Postorder)</h2>

<p align="center"> <img src="https://media.geeksforgeeks.org/wp-content/cdn-uploads/Preorder-from-Inorder-and-Postorder-traversals.jpg" /> </p>

## Introduction
- Linear data structures like arrays, linked lists, queues, and stacks have a linear organization where each element is connected to its previous and next element. As a result, there is only one logical way to traverse them - from the beginning to the end or vice versa.
- Linear data structures like arrays, linked lists, queues, and stacks have a linear organization where each element is connected to its previous and next element. As a result, there is only one logical way to traverse them - from the beginning to the end or vice versa.

### The most commonly used methods for traversing trees are:

- **Preorder Traversal** : In this traversal method, we visit the root node first, then recursively traverse the left subtree, and then the right subtree. The traversal order is: root node, left subtree, right subtree.

- **Inorder Traversal** : In this traversal method, we recursively traverse the left subtree, then visit the root node, and then recursively traverse the right subtree. The traversal order is: left subtree, root node, right subtree.

- **Postorder Traversal** : In this traversal method, we recursively traverse the left subtree, then the right subtree, and finally visit the root node. The traversal order is: left subtree, right subtree, root node.

## Objective
- the objectives of tree traversals include searching, printing, performing operations, and evaluating or constructing expressions. The specific objectives may vary depending on the type of tree traversal and the specific application.

## Reason for Traversals
- **Data Retrieval** : Traversing a tree is often necessary to retrieve data from it. For example, in a binary search tree, we might need to traverse the tree in order to locate a specific node or find the maximum or minimum value.

- **Data Modification** : Traversing a tree is also necessary when modifying its data. For example, if we want to delete a node from a binary search tree, we need to traverse the tree to locate the node to be deleted and then reorganize the tree accordingly.

- **Data Display** : We may need to traverse a tree to display its data in a specific order. For example, in an Inorder Traversal of a binary search tree, we visit the nodes in ascending order, which can be useful for displaying the data in a sorted manner.

- **Data Manipulation** : Traversing a tree is often necessary when manipulating its data. For example, in a binary expression tree, we may need to traverse the tree in order to evaluate an expression or convert it to a different representation.

- **Algorithm Design** : Tree traversals are also essential for designing algorithms that involve trees. For example, many graph algorithms use tree traversals as a subroutine to traverse the graph.
