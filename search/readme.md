# Search

## Search problems

- initial state
- actions
- transition model
- goal test
- path cost function

### Approach

- Start with a frontier that contains the initial state.
- Repeat:
  - If the frontier is empty, yhen no solution.
  - Remove node from the frontier.
  - If node contains goal state, return the solution.
  - Expand the node, add resulting nodes to the frontier.

### Revised Approach

- Start with a frontier that contains the initial state.
- Start with an empty explored set.
- Repeat:
  - If the frontier is empty, yhen no solution.
  - Remove node from the frontier.
  - If node contains goal state, return the solution.
  - Add the node to the explored set.
  - Expand the node, add resulting nodes to the frontier if they aren't already in the frontier or the explored set.
