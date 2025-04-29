# cse331---project-3-red-black-trees-solved
**TO GET THIS SOLUTION VISIT:** [CSE331 – Project 3: Red Black Trees Solved](https://www.ankitcodinghub.com/product/cse331-project-3-red-black-trees-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110619&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE331 - Project 3: Red Black Trees Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
This is not a team project, do not copy someone elseâ€™s work.

Assignment Overview

Red/Black Tree

A Red Black Tree is a type of self-balancing binary search tree (BST). A BST is a binary tree with the property that given a node contained therein, its left and right children store values less and greater than it respectively. This allows for, on average, logarithmic time complexity of searches. BSTs can, as has been discussed in class, become unbalanced when subject to certain sequences of insertions or removals. A self balancing BST seeks to remedy this issue by ensuring that given a node, its left and right branches are of relatively equal size. A Red Black tree ensures this balance by assigning a color (red or black) to each node and applying rules to the ways in which these colors are distributed. These rules are as follows:

1. Each node must be either Red or Black.

2. The root of the tree must always be Black.

3. A Red node must always have a Black parent node, and a Black child node (as shown above, null nodes are assumed to be Black).

4. Every path from the root of the tree to a null pointer must pass through theÂ same number of black nodes.

Here is a visualization tool which is very useful for testing insertions and removals. We used this while developing the project.

Information on static methods in python.

Information on python generators and yield statements. (This is more than you need to use for this project.)

Here is some information on the differences between Red Black trees and AVL trees, which this project was based on in previous semesters.

Assignment Notes

IMPORTANT: Don’t create new objects without good reason. Never in the course of this project should one create a new tree, and new nodes should only be created withinÂ insert(). Doing so in other situations is very likey to violate complexity requirements, and never necessary.

Remember to write docstrings. Project 1 provides examples of how they should be written. Docstrings should include a description of the function they pertain to, its parameters, and its return type.

An RBtreeÂ is strictly typed, and will not contain mismatched types. However, the structure should be type agnostic and able to contain any standard type.

Several of the method implemented areÂ static methods – the reason for this is that while they are members of theÂ RBtreeÂ class, they act only on theÂ RBnode class, and are not called on anÂ RBtree. I.e. rather than calling on self (anÂ RBtree instance) with self.get_uncle(node), one would call the function RBtree.get_uncle(node).

The methods below are given in a suggested logical order of implementation.

IT IS HIGHLY RECOMMENDED YOU REFER TO THE SECTIONS OF ZYBOOKS RELEVANT TO THE PROJECT BEFORE AND DURING IMPLEMENTATION!

As the above note should indicate, feel free to implement helper functions as necessary- as long as they obey time and space complexity requirements.

For traversals, use of recursion is highly recommended.

Types:

T: Generic Type

RBnode: Described below

Assignment Specifications class RBnode:

This class describes the nodes contained in anÂ RBtree.

DO NOT MODIFY this class

Attributes

value: Value contained in a node. Is also used as a key insertion, removal, and other pertinent operations.

is_red: Boolean identifier for node color (if it is not red, it is black) parent: Parent of the node left: Left child of the node right: Right child of the node init(self, value, is_red=True, parent=None, left=None, right=None)

val: **TÂ **

is_red: bool parent: RBnode left: RBnode right: RBnode

Instantiates anÂ RBnode, assigning its member variables.

return: None

Time Complexity: O(1) eq(self, other)

other: RBnode

Assesses equality of data contained in a node, checking bothÂ value andÂ is_red return: bool

Time Complexity: O(1)

str(self)

Representation of val and is_red as a string return: str

Time Complexity: O(1)

repr(self)

Representation as a string utilizing str return: str

Time Complexity: O(1) subtree_size(self)

Size of a subtree rooted at self

return: int

Time Complexity: O(n) subtree_size(self)

Height of a subtree rooted at self

return: int

Time Complexity: O(n)

subtree_red_black_property(self)

Determines whether the subtree rooted atÂ self adheres to Red Black properties return: bool

Time Complexity: O(n)

class RBtree:

DO NOT MODIFY the following attributes/functions

Attributes root: root of anÂ RBtree, of typeÂ RBnode size: number of nodes contained in the tree

init(self, root=None) root: RBnode

Instantiates anÂ RBtree, creating a deepcopy of the subtree rooted at a provided node. This provided node defaults toÂ None.

Time Complexity: O(n) – whereÂ _nÂ _is the size of the rooted subtree provided

eq(self, other) other: RBtree

Determines equality betweenÂ RBtree instances.

return: bool

_Time Complexity: O(min(N, M)) –&gt; M is size of otherÂ Â _

str(self)

Represents the RBtree as a string, for use in debugging return: str

Time Complexity: O(N)

repr(self)

Represents the list as a string utilizing str return: str

Time Complexity: O(N)

IMPLEMENT the following functions

set_child(parent, child, is_left) –&gt; static method parent: RBnode child: RBnode is_left: bool

Sets theÂ childparameter ofÂ parentÂ _toÂ _child. Which child is determined by the identifierÂ _is_left.Â _The parent parameter of the new child node should be updated as required. return:Â None

Time Complexity: O(1), Space Complexity: O(1) replace_child(parent, current_child, new_child) –&gt; static method parent: RBnode current_child: RBnode new_child:Â RBnode

Replaces parent’s childÂ current_child withÂ new_child.

return:Â None

Time Complexity: O(1), Space Complexity: O(1) get_sibling(node) –&gt; static method

node:Â RBnode

Given a node, returns the other child of that node’s parent, orÂ NoneÂ should no parent exist.

Time Complexity: O(1), Space Complexity: O(1) get_uncle(node) –&gt; static method node:Â RBnode

Given a node, returns the sibling of that node’s parent, orÂ NoneÂ should no such node exist.

Time Complexity: O(1), Space Complexity: O(1) get_grandparent(node)Â –&gt; static method node:Â RBnode

Given a node, returns the parent of that node’s parent, orÂ NoneÂ should no such node exist.

Time Complexity: O(1), Space Complexity: O(1) left_rotate(self, node)

node:Â RBnode

Performs a left tree rotation on the subtree rooted atÂ node.

return:Â None

Time Complexity: O(1), Space Complexity: O(1) right_rotate(self, node)

node:Â RBnode

Performs a right tree rotation on the subtree rooted atÂ node.

return:Â None

Time Complexity: O(1), Space Complexity: O(1) insertion_repair(self, node) node: RBnode

This method is not tested explicitly, but should be called after insertion on the node which was inserted, and should rebalance the tree by ensuring adherance to Red/Black properties. It is highly recommended you utilize recursion.

return:Â None

Time Complexity: O(log(n)), Space Complexity: O(1) prepare_removal(self, node)

node: RBnode

This method is not tested explicitly, but should be called prior to removal, on a node that is to be removed. It should ensure balance is maintained after the removal.

return:Â None

Time Complexity: O(log(n)), Space Complexity: O(1) insert(self, node, val)

node: RBnode val: Type T

Inserts an RBnodeÂ object to the subtree rooted atÂ nodeÂ with value val.

Should a node with valueÂ val already exist in the tree, do nothing.

It isÂ _highly recommendedÂ _you implement this function recursively. To do so non-recursively will be significantly harder, and we won’t assist you in doing so in the helproom or on piazza. return:Â None

Time Complexity: O(log(n)), Space Complexity: O(1) search(self, node, val)

node: RBnode val: Type T

Searches the subtree rooted atÂ node for a node containing valueÂ val.Â _If such a node exists, return that node- otherwise return the node which would be parent to a node with valueÂ _val should such a node be inserted.

This is probably best to implement recursively, but not required.

Time Complexity: O(log(n)), Space Complexity: O(1) min(self, node)

node: RBnode

Returns the minimum value stored in the subtree rooted atÂ node. (None if the subtree is empty).

Time Complexity: O(log(n)), Space Complexity: O(1) max(self, node) node: RBnode

Returns the maximum value stored in a subtree rooted atÂ node. (None if the subtree is empty).

Time Complexity: O(log(n)), Space Complexity: O(1) inorder(self, node)

node: RBnode

Returns aÂ generator object describing an inorder traversal of the subtree rooted atÂ node.

Points will be deducted if the return of this function is not a generator object (hint:Â yieldÂ andÂ yieldÂ from)

Time Complexity: O(n), Space Complexity: O(n) preorder(self, node) node: RBnode

Returns a generator object describing a preorder traversal of the subtree rooted atÂ node.

Points will be deducted if the return of this function is not a generator object (hint:Â yieldÂ andÂ yieldÂ from)

Time Complexity: O(n), Space Complexity: O(n) postorder(self, node) node: RBnode

Returns aÂ generatorÂ _object describing a postorder traversal of the subtree rooted atÂ _node.

Points will be deducted if the return of this function is not a generator object (hint:Â yieldÂ andÂ yieldÂ from)

TIme Complexity: O(n), Space Complexity: O(n) bfs(self, node)

node: RBnode

Returns a generatorÂ _object describing a breadth first traversal of the subtree rooted atÂ _node.

Hint: theÂ _queueÂ _class has been imported already, feel free to use it.

Points will be deducted if the return of this function is not a generator object (hint:Â yieldÂ andÂ yieldÂ from)

Time Complexity: O(n), Space Complexity: O(n) remove(self, node, val)

node: RBnode val: Type T

Removes node with valueÂ valÂ _from the subtree rooted atÂ _node. If no such node exists, do nothing.

If the node to be removed is an internal node with two children, swap its value with that of the maximum of its left subtree, then remove the node its value was swapped to.

UsingÂ search()Â might be a good idea.

This function is complicated and hard, don’t be afraid to ask for help. We strongly recommend referring to zybooks.

Note this function uses inorder traversals for testing, so your tests will not pass if the in order traversal function is not completed.

return: None

Time Complexity: O(log(n)), Space Complexity: O(1)

Submission

Deliverables

Project3.zip

|â€” Project3/

|â€” README.md (for project feedback)

|â€” __init__.py (for proper Mimir testcase loading)

|â€” RBtree.py (contains your solution source code) |â€” RBnode.py (supports RBtree.py)

Grading

Tests: __/70

Time Complexity: __/14 set_child, replace_child, get_sibling, get_uncle, get_grandparent, min, max, search (0.5 each) inorder, preorder, postorder, bfs, left_rotate, right_rotate (1 each) insert, remove (2 each)

Space Complexity: __/14 set_child, replace_child, get_sibling, get_uncle, get_grandparent, min, max, search (0.5 each) inorder, preorder, postorder, bfs, left_rotate, right_rotate (1 each) insert, remove (2 each)

README.md is completely filled out with (1) Name, (2) Feedback, (3) Time to Completion and (4) Citations: __/2

Project designed by Andrew Haas and Ian Barber
