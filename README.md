# TopologicalSort
To find "dependency"- U comes before V in the order u ---> v
Since we need dependency, this will work only on Directed, Acylic graph. DAGs
So our goal is to find which node come first and which comes next. 
We shall use DFS and store all the neighbours in the Stack, why stack ? because it has LIFO property. So just do DFS for a Node, we get all the neighbours in the stack and then lastly add the current node. This way we will get the Topological order. 
You should just understand how DFS and backtracking works using tree visualization, then moslty all problems are solved.
