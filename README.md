# Regression Discontinuity: Bandwidths, Manipulation and Close Elections

## Objective

I used simulated grant data and close U.S. House elections to see what changes at a cutoff.

## Methodology

- I simulated a grant with a true effect of 8 percentage points and compared a fit using all students with a fit near the cutoff.
- I repeated the simulation 300 times to compare bandwidths.
- I checked for a pileup near the cutoff and tested whether prior scores jumped there.
- I compared close Democratic wins and losses using ADA scores and checked my own RD function against the package output.

## Key Findings

The fit using all students gave 0.0357. The fit near the cutoff gave 0.0789 at a bandwidth of 16.1, much closer to the true effect. Across the simulations, a bandwidth of 20 had the lowest RMSE. The density test picked up the change when observations were moved across the cutoff (p = 0.0022). In close House races, a narrow Democratic win raised the estimated ADA score by 46.491 points.
