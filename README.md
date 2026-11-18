# JavaScript Price Calculator

A simple price calculator built with JavaScript. It calculates the discount, tax, and final price for a product.

## Features

- Calculate the discount amount
- Calculate tax after the discount
- Calculate the final price
- Print a price summary to the console

## Usage

Run the script with Node.js:

```bash
node priceCal.js
```

The script includes example calculations in `priceCal.js` and prints the results to the console.

## Calculation

The calculator uses these formulas:

```text
Discount = price × (discount percentage ÷ 100)
Tax = discounted price × (tax percentage ÷ 100)
Final price = price - discount + tax
```

## Project Reference

This project is based on the [JavaScript Price Calculator project](https://roadmap.sh/projects/js-price-calculator) from roadmap.sh.
