# Unlimited dicimal of PI using python

### Computing Pi to 'n' Decimal Places

This Python script calculates the value of pi to 'n' number of decimal places using the Bailey–Borwein–Plouffe (BBP) formula. It prompts the user to input the desired number of decimal places and then computes the value of pi accordingly.

## Usage

1. Run the Python script `compute_pi.py`.
2. Input the number of decimal places 'n' when prompted.
3. The script will output the value of pi to 'n' decimal places and save the result in a text file named `pi_digits.txt`.
4. Check the `pi_digits.txt` file for the computed value of pi.

## Requirements

- Python 3.x
- `decimal` and `math` modules (included in Python standard library)

## How it Works

The script utilizes the Bailey–Borwein–Plouffe formula, which is an algorithm for quickly finding the nth binary digit of pi. It iteratively calculates the value of pi with increasing precision until the desired number of decimal places is reached.

## Example

Suppose you want to compute pi to 100 decimal places. Here's how you can use the script:

```bash
$ python compute_pi.py
Please Enter Number of decimal places: 100
```

The script will output the value of pi to 100 decimal places and save it in the `pi_digits.txt` file.

