This is a slightly modified version of the SimplifyModifier.js file from the three.js library.

Vertex collapse is now driven by an array that contains the required number of lowest cost vertices to be removed.

In my application this has resulted in >60% improvement in performance overall.
