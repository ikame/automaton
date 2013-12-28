automaton
=========

Generator of state machines that accept the same language of a given regular expression.

## Draw the state machine associated to a regular expressions tree ##

```sh
python -m automaton "(a|b*c)" -o output.png
```

Then, `output.png` file will be:

![Screenshot](screenshot.png)

where the **accepting states are marked in blue** and the **starting node is marked with >**.
