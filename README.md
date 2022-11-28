# Pushswap TESTER
## Made by: Maxime Le Besnerais - Tek 2 ED - Epitech Lyon


## User Manual

The generator can be used as a standalone program to generate random numbers, or as a library to generate random numbers in your own program.

## Tester

The tester is a program that will test your pushswap program with a given number of random numbers.

### Usage

```bash
./tester auto [number of numbers]
./tester serial [difficulty] [-u]
./tester mean [size of the array] [number of tests]
./tester [number_list.txt] [instructions.txt]
```

<details>
<summary> Usage details </summary>


#### Auto
Auto will generate a number of random numbers and test your pushswap program with it. The number of numbers is optional, if not specified, it will generate 1000 numbers.

#### Serial
Serial will generate a number of 5, 10, 25, 50 and 100 numbers and test your pushswap program with it. The difficulty is optional, if not specified, it will be set to 1. It must be between 1 and 100. It will multiply the number of numbers by the difficulty. The -u option will make the tester use the unlocked mode and allow you to go above the 100 difficulty.

#### Mean
Mean will generate a number of X numbers to test your pushswap program with it. The size of the array is optional, if not specified, it will be set to 700. The number of tests is optional, if not specified, it will be set to 10.


</details>

### Standalone Generator Usage

```bash
./Generator [number of numbers] [min] [max]
```
The generator will generate a number of random numbers between min and max. The number of numbers is optional, if not specified, it will generate 500 numbers. The min is optional, if not specified, it will be set to -100000. The max is optional, if not specified, it will be set to 100000.