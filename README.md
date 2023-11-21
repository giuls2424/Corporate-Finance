# Corporate-Finance
This repository contains the code used for the Real Option Valuation of Novo Nordisk. All the drugs produced in pipeline are splitted into 4 categories: diabete care, obesity care, other rare disease and rare chronic disease. For each of them, the NPV and the corresponding strike price is used to estimate the option price using a Binomial Lattice model and the classical Black-Scholes model with its inputs.

Some underlying assumptions are made, in particular:
- all the patents will expire in 10 years, and at the 9th we assume the sales peak after which sales will be decreasing since the drug is no longer protected by the patent
- we consider the US market only
- drugs are all in the first year of their phase but they go out of the market 5 years after the expiration of the patent
- we assumed a long horizon for the computation of the NPV and quite a conservative approach in term of growth rate
- volatility depends on the terapeuthic area we are considering
