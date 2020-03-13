**Problem:** 

Import and analyze an internal email communication network between employees of a mid-sized manufacturing company. After analyzing the network, solve the following problems:
  1. Load up the directed multigraph.
  2. How many employees and emails are represented in the graph?
  3.
    a. When an employee sends an email to another employee, a communication channel has been created, allowing the sender to provide information to the receiver, but not vice versa. Based on the emails sent in the data, is it possible for information to go from every employee to every other employee?
    b. Now assume that a communication channel established by an email allows information to be exchanged both ways. Based on the emails sent in the data, is it possible for information to go from every employee to every other employee?
  4. How many nodes are in the largest (in terms of nodes) weakly connected component?
  5. How many nodes are in the largest (in terms of nodes) strongly connected component?
  6. Find the subgraph (call this G_sc) of nodes in a largest strongly connected component.
  7. What is the average distance between nodes in G_sc?
  8. What is the largest possible distance between two employees in G_sc?
  9. What is the set of nodes in G_sc with eccentricity equal to the diameter?
  10. What is the set of node(s) in G_sc with eccentricity equal to the radius?
  11. Which node in G_sc is connected to the most other nodes by a shortest path of length equal to the diameter of G_sc? How many nodes are connected to this node?
  12. Suppose you want to prevent communication from flowing to the node that you found in the previous question from any node in the center of G_sc, what is the smallest number of nodes you would need to remove from the graph (you're not allowed to remove the node from the previous question or the center nodes)?
  13. Construct an undirected graph G_un using G_sc (you can ignore the attributes).
  14. What is the transitivity and average clustering coefficient of graph G_un?


**Packages:**
  * NetworkX
  * collections
    * Counter

