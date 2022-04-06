# Trees


## Definition
- A tree is a hierarchical data structure that can be used to follow data back easily through nodes and edges. 



![Tree](https://media.geeksforgeeks.org/wp-content/cdn-uploads/20201129105858/Tree-Basic-Terminology.png)

#### Node
- A node is the placeholder that stores a value.


#### Edge
- An edge is connected by two nodes.

### Root
- A root is a where the tree starts and essentially nodes are formed from it.


### Example
- For this example, we will create a binary tree. We will be using streets to get to our home. You will see the tree expand with each node that has its own properties.

`class Node:`

    `def __init__(self, key);`
    `self.right = None`
    `self.left = None`
    `self.val = key`

`root = Node(A = STC)`

`root.left = Node(B = S Center St)`

`root.right = Node(C = W Campus Rd)`

`root.left.left = Node(D = Benson)`

`root.right.right = Node(E = Rigby)`

               A
           /       \
          B          C
        /   \       /  \
        D    None  E    None
     

-If we travel down Node B, we come across the S Center St, which will lead us along the Benson. Same thing if we travel down Node C, we come along the Rigby.



### Try It Out!
- For this problem, try to find your way back to MC University Store! Use your starting point at the double doors on the Taylor side coming in on the 2nd floor!


### Solution
-[Solution](treesolution.md)