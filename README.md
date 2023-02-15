# HP-12c programming

HP-12c Calculators offer a fun way to run some interesting algorithms.

## Fibonacci Sequence

- 1, 2, 3, 5, 8, 13, 21, 34, 55 ...

This code runs the Fibonacci Sequence with the least amount of commands (most optimized algorithm) and with no pre-loaded data.

We add solely to the algorithm, we do not need to initialize anything else.

If you find any opportunity for improvement, please let us know!

### To run the program

- Press `R/S`

### Code

| # | Command    |
|---|------------|
| 1  | 1         |
| 2  | g PSE     |
| 3  | STO 0     |
| 4  | STO 1     |
| 5  | RCL 0     |
| 6  | RCL 1     |
| 7  | +         |
| 8  | g PSE     |
| 9  | RCL 0     |
| 10 | STO 1     |
| 11 | R ⬇️       |
| 12 | STO 0     |
| 13 | g GTO 005 |

### To input the code

- Press `f P/R` to enter programming mode
- Press `f PRGRM` to clear the *programming memory* (this will delete any previous info added to the *programming memory*)
- Type all the commands [above](README.md#code)
- Press `f P/R` to exit programming mode

### Fun fact

If you stop (by pressing any key), let's say in `55`. Pressing `R/S` will run from that point on to `89...`
