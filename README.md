This project uses **Monte Carlo simulation** to price arithmetic and geometric **Asian options**.

For the **Arithmetic Asian call and put options**, the program uses the corresponding European call and put payoffs under the **Black–Scholes model** as
**control variates** to reduce variance and improving accuracy.  

The **Geometric Asian options** do not require control variates since they have a closed-form solution under the Black–Scholes framework. However, this project still prices them using Monte Carlo.

 ## Features
- Simulates stock price paths under Geometric Brownian Motion (GBM)
- Reuses the same paths for fair comparisons
- Prices arithmetic and geometric Asian calls & puts
- prices European call & puts under the Black–Scholes model
- Uses control variates for variance reduction
- Fully customizable simulation parameters
