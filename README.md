# 154AYSTuringMachine

To run tests, go to the `Input` -> `Multiple Run (Transducer)`. Or Press `CTRL+T`.

Then click `Load Inputs`, and select `tests.txt`.

Then click `Run Inputs`.

The `Transducer` Column will show the value of the `a` register afer running the string in the `Input` Column.

It should always be accepted on the `Result` Column.

If it's `Rejected`, then there's a simple bug to fix, if it's `Cancelled`, then it might have entered an infinite loop or something of the sort.

`Rejected` is like a compile time bug, and `Cancelled` is like a run time bug.

Add more tests to run by adding input strings to the end of the `tests.txt` file.
