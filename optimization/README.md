# RISW Short Course Examples - Optimization

This folder contains documentation and examples for the RISW short course on multiple comparison procedures optimization.

## Files

### [RISW_optimization.Rmd](RISW_optimization.Rmd)
An R Markdown document demonstrating optimization techniques for multiple comparison procedures. This example includes:

- **Example 3**: A 4-hypothesis testing mentioned in the short course.

- **Optimization Methods**:
  - Initial weights optimization using [`optimalMCP::optim_w_dp()`](../R/)
  - Transition matrix optimization using [`optimalMCP::optim_G_dp()`](../R/)
  - Disjunctive power calculations and comparisons

- **Power Analysis**: Comparison between the original study design and optimized graph using simulation-based power calculations

### [RISW_optimization.html](RISW_optimization.html)
The rendered HTML output of the R Markdown document, providing a formatted presentation of the optimization example with embedded plots and results.

## Usage

To run the example:
1. Open [RISW_optimization.Rmd](RISW_optimization.Rmd) in RStudio
2. Ensure the `optimalMCP` package is loaded
3. Knit the document to generate the HTML output

The example demonstrates how optimization can  improve the statistical power of multiple testing procedures while maintaining proper Type I error control.
