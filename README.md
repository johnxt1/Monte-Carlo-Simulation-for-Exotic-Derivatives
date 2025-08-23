This project implements Monte Carlo simulation methods for pricing Asian options (both arithmetic and geometric averages).  

For the **Arithmetic Asian call option**, the program uses the payoff of the European call under the Black–Scholes model as a
control variate, reducing variance and improving accuracy.  

The **Geometric Asian option** does not require control variates since it has a closed-form solution under the Black–Scholes framework.

 Features:
- Simulates stock price paths under Geometric Brownian Motion (GBM)
- Prices:
  - Arithmetic Asian call & put
  - Geometric Asian call & put
- Includes Black–Scholes closed-form European call pricing
- Control variate technique for variance reduction
- Fully customizable simulation parameters
