** DCE Training

*** Introduction to engineering data analysis and reproducible workflows

Problem-driven DCE training for engineers.
I would like us to develop at least 6 examples, which should each include:
 - Begin with a real example engineering problem. Industry-specific problems are perfectly fine, provided the key concepts can be followed by other engineers.
 - Present incrementally more detailed solutions, explaining the benefit of the additional information that they provide:
 - Intuitive solution
 - Standardised solution
 - Informative solution (some sort of computational statistics)
 - Ideally, each example will also help communicate the message of reproducible workflows using code, rather than spreadsheets.

**** Introduction Session: What is DCE

 - How engineers have historically demonstrated safety
 - How novel methods of collecting and analysing data might change this
 - The role of uncertainty in risk management
 - Overview of terminology: CS, ML, AI, probabilistic, neural network
 - Overview of course - engineering-specific and problem focused!

**** Proposed Example 1: Analysing Material Test Data

A small number of fracture toughness tests have been performed:

 - Why is there some variation in the results when the same material is being tested in the same way?
    Discussion of material heterogeneity (aleatory uncertainty).

 - How should you decide which value(s) to use in your calculations?
    Calculate BS 7910 MOTE.
    Calculate "characteristic value" (from structural reliability), using MLE.
    Discussion of sample size and epistemic uncertainty.
    Disucssion of a starting point (prior information) i.e. would you believe a very unlikley test result?
    Find a posterior predictive distribution.

 - How can you identify whether more data is required?
    Consider the need for this data in the context of a decision problem
    Create a utility/cost function
    Provide an overview of experimental design and VoI.

 - If more data is required, which test procedure should be used: Charpy vs. SENB/SENT
    Discussion of data quality.
    What are the imperfect features of test data, and how can they be described quantitatively?


**** Proposed Example 2: System Reliability

Case study: Boeing MCAS failures which led to many fatalities accross multiple flights

- Overview of study
    Many technical and organisational reasons for failure, which were considered in new designs.

- One part of solution: Use of data from multiple AoA sensor.
    How does this make the system safer?
    How much safer does this make the system?
    What questions would you have as a regulator, assessing the new design?

 - Calulation
    Use simulated data to estimate the probability of an erroneous nosedive
    FORM solution + (discussion of SORM) + Monte Carlo methods

 - Consider dependency between performance of 2 sensors
    Introduce multi-variate probabilistic models
    Use simulated test data to fit a copula model
    Discussion of the role of uncertainty in this approach

**** Proposed Example 3: 

**** Proposed Example 4: 

**** Proposed Example 5: 

**** Proposed Example 6: 