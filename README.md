# Brian-Portfolio
## Project 1: Pricing of vanilla options using the object oriented (OPP) approach
This project presents a research on pricing vanilla options using object oriented programming (OPP) approach.
At the end of the project, the option greeks are calculated. We also plot the option prices against the strike prices to visualize the option curves.
* The implementation is done in Python programming
* The Black-Scholes-Merton model has been used to price European call and put options
### Steps followed
 * Setting up class and constructors
 * Defining and initializing the option parameters: Stock price, Strike price, Interest rate, Dividend yield, Expiry, Volatility
 * Calculating d1 and d2
 * Implementing the closed form solution based on the Black-Scholes equation
 * Plotting the option prices against strike prices
 * Calculating the option greeks
 
## Project 2: Pricing European Up-and-Out options using Monte Carlo Simulation
This is a research on using Monte Carlo Simulation to price path dependent exotic options. 
The Up-and-Out barrier option barrier option was chosen for this project.
This type of option expires when the underlying stock price touches the barrier level. Otherwise, the option will stay active and give a payoff at the maturity.
  * The Risk-Neutral-Pricing is considered in the valuation of path dependent options using Monte Carlo Simulation
  * Risk-neutral stock prices paths will be simulated 
### Steps followed
  * Defining and initializing the option parameters: Stock price, Strike price, Barrier, Interest rate, Dividend yield, Expiry, Volatility, Number of time steps and   simulations
  * Implementing iterations for the Monte Carlo Simulation; simulating stock prices using the Geometric Brownian Motion
  * Calculating the payoffs and option price
  * Plotting the simulated stock prices
