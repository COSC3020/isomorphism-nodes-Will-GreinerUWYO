# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

## Answer
Since we know that $G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$, we can show that $A$ and $B$ must have the same number of nodes to be isomorphic.

A bijection is defined as "a function such that each element of the second set (the codomain) is the image of exactly one element of the first set (the domain)" which means that every element in V1 must map to one and only one other element in V2. If this doesn't work, the rule for the two graphs to be isomorphic is broken because there is no way to map every element in $V_1$ to $V_2$, either there are too few or too many nodes in $V_1$ to be properly mapped.

If $V1$ and $V2$ do not have the same number of elements, there cannot be a bijection between the two, or no bijection $f: V_1 \rightarrow V_2$ can exist, meaning that the definition of isomorphisms is not fulfilled and thus, no two graphs with different number of nodes can be isomorphic.

As an example, let $V_1$ = (1,2,3) and $V_2$ = (1,2,3,4). There is no function that can map the verticies in $V_1$ to $V_2$. Therefore, there can be no isomorphic set of graphs with a different number of nodes.


## Sources and Plagarism Statement

Used this to help understand isomorphisms and connectivity [GeeksforGeeks] (https://www.geeksforgeeks.org/graph-isomorphisms-connectivity/#) Used slides from class to help with definitions.

Used this for definition of bijection [Wikipedia](https://en.wikipedia.org/wiki/Bijection#:~:text=A%20bijection%2C%20bijective%20function%2C%20or,first%20set%20(the%20domain).)

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
