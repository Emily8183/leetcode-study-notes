**Tips:**

1. Again, for stack-related problems, I would pay extra attention to all the scenarios(conditions) described in the problem before starting to code;
2. Here's the key:
   If the current asteroid is positive, there's no need to compare it with the top of the stack.

- If the stack's top is positive, they're moving in the same direction (no collision).
- If the stack's top is negative, the top asteroid is moving LEFT, and the current asteroid is moving right, so no collision occurs.

Comparisons are only required when the current asteroid is negative.
