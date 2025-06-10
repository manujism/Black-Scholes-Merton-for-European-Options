# Black-Scholes-Merton-for-European-Options

Overview
----
The Black-Scholes model is a widely used mathematical model for pricing European-style options. It is based on the assumption that the price of the underlying asset follows a geometric Brownian motion. The model provides a closed-form solution to price both call and put options.

This project implements the Black-Scholes model for pricing European options and calculates the Greeks—Delta, Gamma, Theta, Vega, and Rho—which help understand the sensitivity of the option's price to various factors like the underlying asset price, volatility, time to maturity, and interest rates.


-----

Assumptions of the Black-Scholes Model
-----

The model relies on the following assumptions:

1. No dividends are paid during the life of the option.
2. No transaction costs in buying or selling the option.
3. The price of the underlying asset follows geometric Brownian motion.
4. Markets are efficient, meaning that all available information is reflected in the prices.
5. Risk-free rate and volatility are constant and known.
6. The option is European, which means it can only be exercised at expiration.

Black-Scholes Formula
--------
<img width="627" alt="image" src="https://github.com/user-attachments/assets/8a0d92e6-ed83-4511-8bc2-6f0adfbad7e3" />


------

Greeks Calculations
----
**The Greeks** are key metrics that measure the sensitivity of the option price to various factors. These include:

**Delta (Δ):** Measures the sensitivity of the option price to changes in the underlying asset's price.

**Gamma (Γ):** Measures the rate of change of Delta with respect to the underlying asset's price.

**Theta (Θ):** Measures the sensitivity of the option price to the passage of time.

**Vega (ν):** Measures the sensitivity of the option price to changes in volatility.

**Rho (ρ):** Measures the sensitivity of the option price to changes in the risk-free interest rate.

------------

Conclusion
----

The Black-Scholes option pricing model provides a theoretical approach to pricing European-style options and calculating the Greeks to assess the impact of various market factors. By understanding how the Greeks behave, investors can better manage their portfolios and assess risks associated with options trading.

The plots presented here give valuable insights into how the option price changes in response to different factors such as the underlying asset price, time to maturity, volatility, and interest rates.



