# 154AYSTuringMachine

## Project Description

Everything comes together into the `main.jff` file. Run that for project level testing, look at the **testing** section below for more details.

The tape is initialized using `setup.jff`, where the registers are initialized.

---

All the files relating to the sub-categories `Arithmetics`, `Controls`, and `Loads` can be found in their respective folders.

Each of the top level commands, such as `INC`, `DEC`, `LD`, `JMP`, and so on are in the first level in the folders.

Each of their functionalities are broken up more into smaller file chunks in each sub-folder in the main three folders.

---

In terms of OOP, think of these smaller files as functions and each command is a class that uses these functions, and the main is the runner class that calls each of the classes to run the commands.

## Testing

Everything should be boiled down to the `main.jff` - all project level testing should happen in that file.

To run tests, go to the `Input` -> `Multiple Run (Transducer)`. Or Press `CTRL+T`.

Then click `Load Inputs`, and select `tests.txt`.

Then click `Run Inputs`.

The `Transducer` Column will show the value of the `a` register afer running the string in the `Input` Column.

It should always be accepted on the `Result` Column.

---

If it's `Rejected`, then there's a simple bug to fix, if it's `Cancelled`, then it might have entered an infinite loop or something of the sort.

`Rejected` is like a compile time bug, and `Cancelled` is like a run time bug.

---

Add more tests to run by adding input strings to the end of the `tests.txt` file.
