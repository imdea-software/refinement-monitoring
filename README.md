The Story
=========

1. Concurrent objects are really important

2. Concurrent objects are hard to implement

3. Verification is really hard

What are the obstacles?
----------------------------

1. Enumerating linearizations

2. Complexity exponential in number of operations

What is our solution?
--------------------------

1. Avoid enumeration by symbolic reasoning

2. Remove operations to avoid exponential explosion

3. Only saturate / avoid guessing to avoid exponential also

What do we demonstrate?
----------------------------

1. Our tricks are sound

2. Our tricks are empirically complete, or close

3. Our approach is extremely scalable

What is the outline of our approach?
-----------------------------------------

1. Axiomatization of objects (sequential executions)
   reduces to logical/symbolic reasoning w/ enumeration

2. Reduction to propositional reasoning for logical/symbolic
   reasoning w/o enumeration

3. Sound theory for removing "obsolete" operations

4. Empirical evaluation shows completeness & scalability
