# Binary-Search-Tree
## Project 3:
####: The steps for the Binary Search Tree (BST) of the array [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] are as follows:

1- Insertion:

During insertion, each element is added to the tree in the appropriate position starting from the root.
Initially, we have an empty tree. The elements we add are sequentially inserted into the tree:
Insert: 7 (root)
Insert: 5 (left of the root)
Insert: 1 (left of 5)
Insert: 8 (right of 7)
Insert: 3 (right of 1)
Insert: 6 (right of 3)
Insert: 0 (left of 1)
Insert: 9 (right of 8)
Insert: 4 (right of 3)
Insert: 2 (right of 4)

2-Search:

When an element is searched in the tree, a comparison is made starting from the root, and the search continues in the appropriate direction.
Example:

Search: 4
Start from the root, compare with 7. Since 4 is on the left of 7, go left.
Compare with 5. Since 4 is on the right of 5, go right.
Compare with 3. Since 4 is on the right of 3, go right.
Found 4.
3-Deletion:

During deletion, an appropriate element to replace the deleted one is found.
Example:

4-Delete: 5
The smallest element to replace the deleted one is found in the right subtree of 5 (6).
Replace 5 with 6. Delete 5.







