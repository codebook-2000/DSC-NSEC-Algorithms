# Cousins

**Difficulty: Medium**

Turns out the crewmates involved in the Space Mission are actually a big family! CoochieMan, one of the crewmates decided to draw a family tree. The family tree depicted that each member of the family has either 0 or 1 or 2 children. They are depicted by their id numbers and you can be sure that all the ids in a particular family tree are unique. <br/>
Id no of 2 crewmates, X and Y has been given. The Space Mission General wants to know if both of them are cousins or not. <br/>
2 crewmates are cousins when they don't share the same parent and belong to the same genration(equal height from top).

## Input

- The first line of input contains a single integer n, denoting the number of nodes. n-1 lines follow
- In every line, there will be two space separated integers, u and v, denoting the parent and child node
- A single integer, denoting the root of the tree
- A single integer q, denoting the number of queries. q lines follow
- Two space separated integers, X and Y, belonging to the binary tree.

## Example Input

![btree](../../images/btree3.png)

**7<br>
15 10<br>
15 20<br>
10 5<br>
10 12<br>
20 17<br>
20 25<br>
15<br>
2<br>
10 20<br>
5 17**

## Example Output

**False** <br/>
**True**

## Explanation

In test case 1, 10 and 20 are not cousins because even though they belong to the same genration, they share the same parent. <br/>
In the test case 2, 5 and 17 are cousins because they belong to the same generation and have different parents.
