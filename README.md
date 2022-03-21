# quordle-solver

This code solves the daily Quordle. The first guess is share. For the second guess, it generates the best guess for each quadrant and then picks the best of those 4. This is needed for the computation to not take hours. For future guesses, it simulates the best guess from any possible remaining guess from any quadrant.
