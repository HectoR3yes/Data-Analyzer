A CLI program that:
- Reads CSV file with a single column of integers (one value per line)
- Calculates:
    - mean
    - median
    - mode
    - standard deviation
- Prints the result to the terminal
- Write a summary report to a file

# Usage
```shell
./data_analyzer input.csv output.txt
```
- Reads `input.csv`, which contains one integer per line, eg:
```shell
23
45
23
67
78
...
```

- Prints summary to terminal:
```shell
Mean: x
Median: x
Mode: x
Standard Deviation: x
```
>[!note]
>Writes the same sumary to `output.txt`
