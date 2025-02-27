# Graph Representations

Implement a function that converts an adjacency matrix to an adjacency list for
a directed unweighted graph using the template in `code.js`. Test your new
function; I've provided some basic testing code that uses
[jsverify](https://jsverify.github.io/) in `code.test.js`. Now, the test code
does contain the solution, so you can have a look at it if you get stuck, but
try not to peek before attempting to solve it on your own.

I went to Ali Torabi's office hours to disuss runtime analysis and reviewed the slides for this class. 

I submitted this work Fall 2024.

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.

## Runtime Analysis

What is the runtime complexity of the conversion that you implemented? Does it
depend on the number of vertices, the number of edges, or both?

Describe your reasoning and the conclusion you've come to. Your reasoning is the
most important part. Add your answer to this markdown file.

When turning a matrix into a list, only the vertices effect the runtime complexity. Since we are turning a matrix into a list, we look at vertices
a squared amount of time since we first look at the row and then each column. The runtime complexity becuase of this is $O(v^2)$.

## Bonus

Implement a function to convert an adjacency list to an adjacency matrix and
analyze it as above.
