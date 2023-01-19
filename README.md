# Project-of-IT-on-Matlab
The task in this coursework is implementing the code for pricing a call option on a portfolio of stocks via Monte Carlo Method.
The prices of the two stocks can be described with the following model under the risk-neutral measure:
dSt,1 = St,1
* r * dt + St,1
* σ1
* (1 + sin(4t)) * dWt,2
;
dSt,2 = St,2
* r * dt + St,2
* σ2
* (ρ*dWt,1 + √(1 - ρ
2
) * dWt,2
);
where W1 and W2 are two independent Wiener processes, r is the risk-free interest rate, ρ∈[-1,1] is the correlation coefficient, σ1 and σ2
are the volatility components of the first and second stock, respectively.
The payoff of the call option on a portfolio of stocks in this model is given by:
(α * ST,1 +(1−α) * ST,2
) − K) +
where α ∈ [0,1] is the portfolio composition, Tis the period time, K is thestrike price.
