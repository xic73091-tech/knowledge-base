---
domain: business-economics
subdomain: operations-research
title: "Operations Research"
description: "The use of advanced analytical methods to make better decisions"
created: 2026-06-02
updated: 2026-06-02
tags: [optimization, linear-programming, integer-programming, simulation, stochastic, queuing, decision-analysis]
prerequisites: [natural-sciences/mathematics, natural-sciences/statistics, business-economics/operations]
related: [natural-sciences/mathematics, natural-sciences/statistics, business-economics/operations, business-economics/supply-chain]
difficulty: advanced
completeness: comprehensive
---

# Operations Research

## Overview

Operations Research (OR), also known as Management Science, is the discipline of applying advanced analytical methods to make better decisions. It uses techniques from mathematics, statistics, computer science, and engineering to analyze complex systems and solve optimization problems. Operations research helps organizations allocate scarce resources, improve efficiency, reduce costs, and optimize performance across manufacturing, logistics, healthcare, finance, and many other domains.

## Core Concepts

### Linear Programming
- **Linear Programming Problem**: Objective function; constraints; decision variables; feasible region
- **Standard Form**: Maximize cᵀx subject to Ax ≤ b; x ≥ 0; basic feasible solutions
- **Simplex Method**: Corner point search; basic/non-basic variables; pivoting; Dantzig
- **Dual Problem**: Primal-dual relationships; shadow prices; economic interpretation
- **Sensitivity Analysis**: Right-hand side ranges; objective function ranges; shadow prices
- **Interior Point Methods**: Karmarkar's algorithm; polynomial time; large-scale problems
- **Linear Programming Applications**: Production planning; diet problem; transportation

### Integer Programming
- **Integer Variables**: Pure integer; mixed integer (MILP); binary variables
- **Branch and Bound**: Enumerating search tree; bounding; pruning; branching
- **Cutting Planes**: Gomory cuts; valid inequalities; tightening relaxations
- **Branch and Cut**: Combining B&B with cutting planes; global cuts
- **Dantzig-Wolfe Decomposition**: Master problem; subproblems; column generation
- **Applications**: Facility location; scheduling; routing; capital budgeting
- **Complexity**: NP-hard; exponential worst case; practical effectiveness

### Network Optimization
- **Graph Theory Basics**: Nodes; edges; paths; cycles; trees; connectivity
- **Shortest Path Problem**: Dijkstra's algorithm; Bellman-Ford; A*; label-setting/correcting
- **Minimum Spanning Tree**: Prim's algorithm; Kruskal's algorithm; cut property
- **Maximum Flow Problem**: Ford-Fulkerson; Edmonds-Karp; min-cut max-flow theorem
- **Minimum Cost Flow**: Network simplex; capacitated flow; transportation
- **Vehicle Routing**: VRP; Clarke-Wright savings; heuristic methods
- **Network Design**: Steiner tree; facility location; network optimization

### Dynamic Programming
- **Optimal Substructure**: Problem decomposition; recursive optimality
- **Memoization**: Storing subproblem solutions; avoiding recomputation
- **Bellman Equation**: Recursive optimization; state transitions; value function
- **Backward Induction**: Solving sequentially; terminal conditions; iteration
- **Stages and States**: Decomposition into stages; state definition
- **Applications**: Knapsack; shortest path; inventory; scheduling; resource allocation
- **Curse of Dimensionality**: State space explosion; approximations; truncation

### Nonlinear Programming
- **Nonlinear Objective/Constraints**: General optimization; local/global optima
- **Convex Optimization**: Convex sets; convex functions; unique global optimum
- **KKT Conditions**: First-order optimality; gradients; complementary slackness
- **Unconstrained Methods**: Steepest descent; Newton's method; quasi-Newton
- **Constrained Methods**: Penalty methods; barrier methods; augmented Lagrangian
- **Sequential Quadratic Programming (SQP)**: Quadratic approximation; Newton's method
- **Applications**: Portfolio optimization; engineering design; machine learning

### Stochastic Processes
- **Random Variables & Distributions**: Discrete; continuous; expectation; variance
- **Markov Chains**: State space; transition probabilities; Chapman-Kolmogorov
- **Poisson Processes**: Arrival processes; exponential interarrival; superposition
- **Continuous-Time Markov Chains**: Infinitesimal generator; birth-death processes
- **Brownian Motion**: Wiener process; continuous paths; Ito calculus
- **Stationary Processes**: Time invariance; autocorrelation; ergodicity
- **Renewal Processes**: Regeneration; renewal reward theorem; limit theorems

### Queueing Theory
- **Queueing Systems**: Arrival process; service process; number of servers; capacity
- **Kendall Notation**: A/B/C/K/D/E; arrival; service; servers; capacity; discipline
- **Little's Law**: L = λW; average number; throughput; delay relationships
- **M/M/1 Queue**: Exponential arrivals; exponential service; one server
- **M/M/c Queue**: Multiple servers; Erlang formulas; blocking probability
- **Queueing Networks**: Open; closed; product-form networks; Jackson networks
- **Applications**: Call centers; telecommunications; healthcare; traffic engineering

### Decision Analysis
- **Decision Trees**: Sequential decisions; chance nodes; payoffs; rollback evaluation
- **Bayesian Analysis**: Prior/posterior; updating beliefs; expected value
- **Influence Diagrams**: Decision nodes; chance nodes; value nodes; graphical models
- **Utility Theory**: Risk preference; utility functions; certainty equivalent
- **Value of Information**: Perfect information; sample information; decision quality
- **Multi-Criteria Decision Making**: Multiple objectives; Pareto optimality; weighting
- **Group Decision Making**: Aggregation; voting; consensus; conflict resolution

### Simulation
- **Monte Carlo Simulation**: Random sampling; probabilistic modeling; law of large numbers
- **Discrete-Event Simulation**: Events; clock; entities; queues; state updates
- **Input Modeling**: Data collection; distribution fitting; parameter estimation
- **Output Analysis**: Point estimates; confidence intervals; replication-deletion
- **Variance Reduction**: Antithetic variates; control variates; importance sampling
- **Verification & Validation**: Building credible models; face validity; trace-driven
- **Simulation Software**: Arena; AnyLogic; Simul8; Python (SimPy); R (simmer)

### Heuristics & Metaheuristics
- **Greedy Algorithms**: Myopic choices; fast; not always optimal; approximation
- **Local Search**: Neighborhood; improving moves; local optima; intensification
- **Tabu Search**: Memory structures; avoiding cycles; short-term memory
- **Simulated Annealing**: Probabilistic improvement; temperature schedule; exploration
- **Genetic Algorithms**: Population; crossover; mutation; selection; evolution
- **Ant Colony Optimization**: Pheromone trails; collective intelligence; routing
- **Particle Swarm Optimization**: Swarm intelligence; particles; velocity; convergence

### Game Theory
- **Strategic Games**: Players; strategies; payoffs; normal form
- **Nash Equilibrium**: No unilateral deviation; mixed strategies; existence theorem
- **Zero-Sum Games**: Pure competition; maximin; minimax; value of game
- **Extensive Form Games**: Sequential moves; game tree; subgame perfection
- **Cooperative Games**: Coalitions; bargaining; Shapley value; nucleolus
- **Repeated Games**: Discounting; trigger strategies; folk theorems
- **Mechanism Design**: Incentives; allocation; revelation principle; auction design

### Inventory Theory
- **Deterministic Models**: Economic order quantity (EOQ); Wagner-Whitin
- **Newsvendor Model**: Single period; stochastic demand; critical fractile
- **(s, Q) Policy**: Continuous review; reorder point; order quantity
- **(S, s) Policy**: Periodic review; reorder up to level; state-dependent
- **Multi-Echelon Inventory**: Supply chain; bullwhip effect; optimization
- **Perishable Inventory**: Decaying items; blood products; aged inventory
- **Production Planning**: Lot sizing; Wagner-Whitin; Silver-Meal; lot-for-lot

### Reliability Engineering
- **Component Reliability**: Failure distributions; exponential; Weibull; bathtub curve
- **System Reliability**: Series; parallel; k-out-of-n; redundancy
- **Redundancy Strategies**: Active; standby; cold; hot; redundancy optimization
- **Maintenance Policies**: Corrective; preventive; predictive; condition-based
- **Availability**: Uptime; downtime; MTBF; MTTR; steady-state availability
- **Warranty Models**: Pro-rata; free replacement; warranty cost analysis
- **Reliability Optimization**: Cost-reliability trade-offs; redundancy allocation

### Transportation & Logistics
- **Transportation Problem**: Hitchcock; supply; demand; Northwest corner; MODI
- **Assignment Problem**: Hungarian method; bipartite matching; optimization
- **Traveling Salesman Problem (TSP)**: Hamiltonian cycle; NP-hard; heuristics
- **Vehicle Routing Problem (VRP)**: Capacitated VRP; VRPTW; heuristics; metaheuristics
- **Facility Location**: p-median; p-center; covering models; strategic decisions
- **Supply Chain Optimization**: Network design; inventory; transportation coordination
- **Crowdshipping**: Gig economy; last-mile; dynamic routing; crowdsourced delivery

### Production & Operations Management
- **Aggregate Planning**: Matching capacity to demand; chase; level; hybrid strategies
- **Scheduling**: Single machine; flow shop; job shop; makespan minimization
- **Theory of Constraints (TOC)**: Drum-buffer-rope; bottleneck identification; throughput
- **Lean Manufacturing**: Waste elimination; just-in-time; continuous improvement
- **Six Sigma**: DMAIC; statistical process control; variation reduction
- **Capacity Planning**: Long-term; medium-term; capacity requirements planning
- **Sequencing Rules**: SPT; EDD; LPT; dispatching rules; rule-based scheduling

### Financial Optimization
- **Portfolio Optimization**: Mean-variance; efficient frontier; risk-return trade-off
- **Asset Liability Management**: Matching assets and liabilities; immunisation
- **Risk Management**: VaR; CVaR; optimization under risk; diversification
- **Option Pricing**: Black-Scholes; binomial trees; Monte Carlo
- **Corporate Finance**: Capital budgeting; investment selection; NPV optimization
- **Algorithmic Trading**: Execution; market making; arbitrage; optimization

### Healthcare Operations
- **Capacity Management**: Hospital beds; OR scheduling; emergency department
- **Patient Flow**: Streamlining; bottlenecks; access; quality
- **Appointment Scheduling**: Overbooking; no-shows; sequencing; templates
- **Staff Scheduling**: Physician; nurse; shift scheduling; fairness
- **Emergency Response**: Ambulance location; disaster planning; network design
- **Organ Transplantation**: Allocation; waiting lists; logistics; equity

### Energy & Utilities
- **Unit Commitment**: Power generation; startup costs; shut-down; economic dispatch
- **Power Flow Analysis**: DC; AC; optimal power flow; economic dispatch
- **Renewable Integration**: Intermittency; storage; grid management
- **Water Resource Management**: Reservoir operation; allocation; sustainability
- **Natural Gas Logistics**: Pipeline; storage; transportation; distribution
- **Energy Efficiency**: Building optimization; demand response; smart grids

### Data-Driven Operations Research
- **Data Envelopment Analysis (DEA)**: Efficiency measurement; frontier analysis
- **Stochastic Optimization**: Chance constraints; two-stage recourse; robust optimization
- **Data Mining in OR**: Clustering; classification; association rules; patterns
- **Machine Learning Integration**: Predict-then-optimize; end-to-end learning
- **Online Optimization**: Sequential decisions; learning; real-time optimization
- **Prescriptive Analytics**: From descriptive to predictive to prescriptive

### Software & Tools
- **Optimization Solvers**: CPLEX; Gurobi; GLPK; open-source alternatives
- **Modeling Languages**: AMPL; GAMS; JuMP; Pyomo; CVXPY
- **Simulation Software**: AnyLogic; Arena; Simul8; NetLogo; R/Simulation
- **Spreadsheet Optimization**: Excel Solver; what-if analysis; data tables
- **Statistical Software**: R; Python (SciPy, PuLP); MATLAB; Julia
- **Specialized Packages**: NetworkX; OR-Tools; Metaheuristics libraries

### Implementation & Practice
- **Problem Formulation**: Translating real problems into mathematical models
- **Model Validation**: Testing; sensitivity; verification; face validity
- **Solution Implementation**: Deployment; integration; change management
- **OR in Practice**: INFORMS; OR society; industry applications; case studies
- **Communication**: Presenting results; visualization; executive summary
- **Ethical Considerations**: Fairness; transparency; unintended consequences

## Key Theories

| Theory | Key Figure | Core Idea |
|--------|-----------|-----------|
| Simplex Method | George Dantzig | Efficient algorithm for linear programming by traversing corner points |
| Inventory Theory | Harris; Wilson | Economic order quantity formula for optimal inventory decisions |
| Queuing Theory | Erlang | Mathematical models for waiting lines and service systems |
| Game Theory | Nash | Equilibrium concepts for strategic interaction |
| Theory of Constraints | Eliyahu Goldratt | Focus on system bottlenecks to improve throughput |
| Markov Decision Processes | Bellman | Sequential decision-making under uncertainty |

## Important Figures

- **George Dantzig**: Simplex method; linear programming; father of OR
- **John von Neumann**: Game theory; minimax theorem; computer science pioneer
- **Richard Bellman**: Dynamic programming; Bellman equation; optimal control
- **Leonard Kleinrock**: Queueing theory; ARPANET; Internet protocols
- **Egon Balas**: Integer programming; disjunctive programming; Gomory cuts
- **Karmarkar**: Interior point algorithm; polynomial time linear programming
- **Robert Herman**: Traffic flow; queueing theory; transportation
- **Gerald B. Dantzig**: Linear programming; stochastic programming pioneer
- **Frederick Winslow Taylor**: Scientific management; efficiency; time studies
- **Eliyahu Goldratt**: Theory of constraints; Critical Chain; TOC

## Frontiers

- **Prescriptive Analytics**: From prediction to optimal decisions; end-to-end learning
- **Online Algorithms**: Real-time decisions; dynamic pricing; resource allocation
- **Stochastic Optimization**: Better handling of uncertainty; robust solutions
- **OR in Machine Learning**: Optimization for ML; learning for optimization
- **Sustainability OR**: Green supply chains; carbon optimization; circular economy
- **Healthcare Analytics**: Precision medicine; personalized treatment; system optimization
- **Fairness & Ethics**: Equity considerations; algorithmic accountability
- **Quantum Optimization**: QAOA; quantum annealing; potential speedups

## Applications

- **Supply Chain Management**: Network design; inventory; transportation; coordination
- **Transportation**: Routing; scheduling; fleet management; public transit
- **Manufacturing**: Production planning; scheduling; quality control; lean
- **Healthcare**: Capacity; scheduling; resource allocation; treatment protocols
- **Finance**: Portfolio; risk; trading; insurance; credit scoring
- **Energy**: Grid optimization; renewable integration; demand response
- **Telecommunications**: Network design; routing; spectrum allocation
- **Government & Defense**: Military logistics; emergency response; resource allocation

## Classic Works

- **"Introduction to Operations Research"** by Hillier & Lieberman — Classic textbook
- **"Linear Programming"** by Chvátal — Comprehensive LP text
- **"Network Flows"** by Ahuja, Magnanti & Orlin — Network optimization
- **"Stochastic Processes"** by Ross — Probability and stochastic processes
- **"Principles of Operations Research"** by Wagner — Classic management science
- **"In Pursuit of the Traveling Salesman"** by Cook — TSP history and algorithms
- **"The Goal"** by Goldratt — Theory of constraints; accessible OR novel

## See Also

- [Mathematics](mathematics.md) — Mathematical foundations
- [Statistics](statistics.md) — Statistical methods
- [Operations](operations.md) — Operations management
- [Supply Chain](supply-chain.md) — Supply chain optimization
