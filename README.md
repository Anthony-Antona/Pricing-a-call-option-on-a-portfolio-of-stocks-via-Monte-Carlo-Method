# Project-of-IT-on-Matlab
Thetask in this coursework is implementing thecodefor pricing a call option on a portfolio of stocks via Monte Carlo Method.
The prices of thetwo stocks can be described with thefollowing model under therisk-neutral measure:
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
where W1 and W2 aretwo independent Wiener processes, r is therisk-freeinterest rate, ρ∈[-1,1] is thecorrelation coefficient, σ1 and σ2
arethevolatility components of the first and second stock, respectively.
The payoff of thecall option on a portfolio of stocks in this model is given by:
(α * ST,1 +(1−α) * ST,2
) − K) +
where α ∈ [0,1] is the portfolio composition, Tis the period time, K is thestrike price.
