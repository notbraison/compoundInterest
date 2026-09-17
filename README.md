# Compound Interest Calculator

A lightweight single-page web app for calculating compound growth and exploring how interest accumulates over time.

## Overview

This project lets you enter:

- principal amount
- annual interest rate
- investment duration in years
- compounding frequency

It then calculates the final balance, total interest earned, and a per-period breakdown of growth.

## Formula

The app uses the standard compound interest formula:

A = P(1 + r/n)^(nt)

Where:

- A = final amount
- P = principal
- r = annual interest rate
- n = number of compounding periods per year
- t = time in years

## Features

- instant calculation with a modern, responsive layout
- supports annual, semi-annual, quarterly, monthly, and daily compounding
- shows final value and total interest earned
- includes a detailed period-by-period breakdown table
- validates input for invalid or negative values

## Project Structure

```text
compoundInterest/
├── index.html
├── README.md
└── assets/   (if added later)
```

## Running the App

1. Open the project folder.
2. Launch `index.html` in a browser.
3. Enter your values and click the calculate button.

You do not need a build step or package installation for this static project.

## Example

If you invest $1,000 at 6% annual interest for 10 years with monthly compounding:

- principal: $1,000
- annual rate: 6%
- years: 10
- compounding: monthly

The calculator will estimate the final balance and show the interest gained over each month.

## Notes

This is a simple front-end calculator designed for quick financial estimates and educational use. It is not a financial advisor or accounting tool.
