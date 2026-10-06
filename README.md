# Simple Sales Summary in R

## Overview

Simple Sales Summary in R is a small R project that analyzes a set of fictional sales values. It demonstrates how Base R can be used to calculate total sales and average sales.

## Installation

No external packages are required.

1. Install R.
2. Open `sales_summary.R` in R or RStudio.
3. Run the script.

## Dependencies

- Base R only
- No external packages
- No external data files

## Usage

Run `sales_summary.R` in R or RStudio. The script calculates and displays the total sales and average sales values.

## Example Code

```r
sales <- c(120, 150, 135, 160, 145)

total_sales <- sum(sales)
average_sales <- mean(sales)

total_sales
average_sales
```

## License

This project is created for educational purposes as part of coursework.


## AI Assistance Disclosure

**AI tool used:** ChatGPT (GPT-5.6 Sol)

**Main prompts used for README development:**

**Step 1 - README Structure**
1. Seed Prompt: "Explain what sections a good GitHub README for an R data analysis project should include."
2. Refinement Prompt: "Revise the sections list so it's concise and uses Markdown headers and bullet formatting."
3. Critique/Validation Prompt: "Check the Markdown syntax for correctness and readability."

**Step 2 - README Draft and Revision**
1. Seed Prompt: "Here's a summary of my R project:
Project title: Simple Sales Summary in R
Main script: sales_summary.R
Purpose: The script analyzes a small set of fictional sales values and calculates basic summary information such as total sales and average sales.
Dependencies: Base R only. No external packages and no external data files.
Generate a professional README.md file using Markdown."
2. Refinement Prompt: "Add sections for Installation, Example Code, and License. Keep tone concise and professional."
3. Critique/Validation Prompt: "Review the Markdown for syntax errors and suggest 2 improvements for clarity."
4. Final Revision Prompt: "Revise the README by combining the Main Script and Usage sections to avoid repetition, and clarify that running sales_summary.R displays the total sales and average sales results. Keep the Markdown concise and professional."

**Changes made after reviewing the outputs:** 
I combined the Main Script and Usage sections to reduce repetition, clarified that running `sales_summary.R` displays the total sales and average sales results, and verified that the final Markdown rendered correctly on GitHub.
