# covid19
COVID-19 Infection Dynamics Simulation

This project models the spread of the COVID-19 virus through a system of ODEs. We developed an SEIRS system to capture populations of susceptible, exposed, infected, and recovered individuals. We further introduce the possibility of a time-dependent quarantining and vaccine to model the effects of such policies at curbing disease spread. We focus our research on preventing total infections as well as minimizing the maximum number of infections at a given time period to "flatten the curve" and reduce burden on healthcare facilities. By forming a constrained optimization problem we determine the optimal policy interventions to achieve these desired results.

We further model an agent-based hierachical network structure to demonstrate the effect of clustering on such a system. Accounting for varying degrees of interaction among households and neighborhoods results in similar yet distinct trends particularly when implementing quarantining or social distancing policies.

The report of our findings is included am205_final.pdf file, and the attached code for the SEIRS base model as well as the agent based model can be found in SEIRS_simulation.ipynb and SEIRS_Nested_Network.ipynb respectively.
