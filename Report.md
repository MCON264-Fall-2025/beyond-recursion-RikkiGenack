Fibonacci (recursive): work doubles at each step → O(2ⁿ); time skyrockets.

Fibonacci (iterative): single pass → O(n); time scales linearly and stays tiny.

Linked list (recursive insert): one call per node → O(n) stack and call overhead.

Linked list (iterative insert): one frame → O(1) stack, typically faster

Both recursive solutions were less efficient, as the time increased exponentially.
Additionally, RecursiveInsertLAst even threw a StackOverflow Exception, which is avoided in an iterative approach.
The iterative solutions worked faster and more efficiently. 
The reason why recursive takes so long is because it keeps calculating the same values over and over again.