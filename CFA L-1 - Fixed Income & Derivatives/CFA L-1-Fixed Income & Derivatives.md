# Chartered Financial Analyst (CFA) Level 1 Notes  
## Fixed Income and Derivatives

---

## Overview

This repository provides structured and concept-driven notes for the Chartered Financial Analyst (CFA) Level 1 curriculum, focusing on Fixed Income and Derivatives. The material is designed not only for theoretical understanding but also for developing strong analytical and problem-solving skills through mathematical modeling.

The content integrates financial intuition with rigorous quantitative frameworks, enabling a deeper understanding of how debt markets and derivative instruments are priced, analyzed, and used in practice.

---

## Fixed Income

Fixed Income forms the backbone of global financial markets. This section develops a strong foundation in bond valuation, interest rate dynamics, and credit risk analysis.

### Bond Pricing and Valuation

The value of a bond is the present value of its future cash flows:

P = Σ [ C / (1 + y)^t ] + FV / (1 + y)^N

Where:
- C = Coupon payment  
- y = Yield to maturity  
- FV = Face value  

This formulation establishes the fundamental inverse relationship between price and yield.

### Yield Measures

Effective annual yield accounts for compounding effects:

EAY = (1 + y/n)^n - 1

Yield spreads measure relative risk:

Spread = y_bond - y_benchmark

These are critical for comparing bonds across issuers and markets.

### Term Structure of Interest Rates

Spot rates are used to discount individual cash flows:

P = Σ [ CF_t / (1 + S_t)^t ]

Forward rates are derived from spot rates:

f(1,1) = [(1 + S2)^2 / (1 + S1)] - 1

These relationships define the yield curve and expectations of future interest rates.

### Duration and Interest Rate Risk

Duration measures sensitivity of bond prices to interest rate changes:

ModDur = MacDur / (1 + y)

Approximate price change:

ΔP / P ≈ -ModDur × Δy

This is a first-order approximation of interest rate risk.

### Convexity Adjustment

To improve accuracy:

ΔP / P ≈ -ModDur × Δy + (1/2) × C × (Δy)^2

Convexity captures the curvature in the price-yield relationship.

### Credit Risk Modeling

Expected loss is modeled as:

EL = PD × LGD

Where:
- PD = Probability of default  
- LGD = Loss given default  

This framework explains credit spreads and risk premiums.

### Securitization

Asset-backed securities transform illiquid assets into tradable instruments.

Cash flow structure is modeled through tranching:

- Senior tranches → low risk, low return  
- Junior tranches → high risk, high return  

This enables risk redistribution across investors.

---

## Derivatives

Derivatives are financial instruments whose value is derived from an underlying asset. They are essential for hedging, speculation, and arbitrage.

### Forward and Futures Pricing

Forward price under no-arbitrage:

F0(T) = S0 (1 + r)^T

With cost of carry:

F0(T) = S0 e^(r + c - b)T

These models ensure arbitrage-free pricing.

### Forward Valuation

Value of a forward during its life:

Vt = St - F0(T)(1 + r)^-(T - t)

This determines profit or loss before maturity.

### Option Payoffs

Call and put option payoffs:

cT = max(0, ST - X)

pT = max(0, X - ST)

These define nonlinear payoff structures.

### Put-Call Parity

A fundamental arbitrage relationship:

c0 + X(1 + r)^(-T) = S0 + p0

This enables construction of synthetic positions.

### Binomial Option Pricing

Option valuation using risk-neutral probability:

π = (1 + r - d) / (u - d)

c0 = [πc+ + (1 - π)c-] / (1 + r)

This discrete-time model forms the basis for more advanced pricing methods.

---

## Key Features

- Structured notes aligned with CFA Level 1 curriculum  
- Strong integration of financial theory and mathematical modeling  
- Emphasis on intuition behind formulas  
- Clear separation of fixed income and derivatives concepts  
- Useful for both first-time learning and revision  

---

## Applications

- CFA Level 1 exam preparation  
- Fixed income analysis and bond portfolio management  
- Derivatives pricing and risk management  
- Quantitative finance fundamentals  
- Interview preparation for finance and consulting roles  

---

## How to Use

1. Study each concept along with its mathematical formulation  
2. Focus on understanding relationships between variables  
3. Practice applying formulas to numerical problems  
4. Use as a revision guide before exams  

---

## Future Improvements

- Inclusion of solved numerical examples  
- Case studies on bond markets and derivatives  
- Implementation of pricing models in Python/MATLAB  
- Visualization of yield curves and payoff diagrams  

---

## License

This repository is intended for educational purposes only.

---

## Acknowledgements

This work is based on foundational concepts from the CFA Program curriculum and standard financial theory, including:

- Fixed Income Analysis  
- Derivatives and Risk Management  
- Financial Mathematics  
