---
domain: natural-sciences
subdomain: network-science
title: "Network Science"
description: "The interdisciplinary study of complex networks and their properties"
created: 2026-06-02
updated: 2026-06-02
tags: [networks, graphs, nodes, edges, connectivity, dynamics, social-networks, complex-systems]
prerequisites: [natural-sciences/mathematics, natural-sciences/statistics]
related: [natural-sciences/complexity-science, social-sciences/sociology, engineering-technology/data-science]
difficulty: advanced
completeness: comprehensive
---

# Network Science

## Overview

Network science is an interdisciplinary field that studies complex networks and their properties, structure, and behavior. It provides tools and frameworks for understanding systems composed of interacting elements—from social networks and the internet to biological systems and infrastructure. Network science combines graph theory, statistical physics, computer science, and social science to analyze how the structure of connections influences the function, dynamics, and resilience of complex systems. It has applications across virtually every scientific discipline and in understanding social, technological, and biological phenomena.

## Core Concepts

### Graph Theory Fundamentals
- **Graph Definition**: Vertices (nodes); edges (links); directed vs undirected; weighted vs unweighted
- **Adjacency Matrix**: Representation; properties; eigenvalues; spectral analysis
- **Incidence Matrix**: Edge-vertex relationships; directed; undirected
- **Graph Types**: Simple; multigraph; pseudograph; bipartite; hypergraph
- **Paths & Connectivity**: Walks; trails; paths; cycles; connected; components
- **Trees & Forests**: Acyclic graphs; spanning trees; properties; algorithms
- **Planar Graphs**: Euler's formula; planar embedding; graph coloring; K5/K3,3

### Network Topology & Structure
- **Degree Distribution**: Node degrees; average degree; degree sequences
- **Power Law Distributions**: Scale-free networks; heavy tails; log-normal; hubs
- **Clustering Coefficient**: Transitivity; local clustering; triangles; global clustering
- **Shortest Path Length**: Diameter; average path length; small-world phenomenon
- **Centrality Measures**: Degree; betweenness; closeness; eigenvector; PageRank
- **Assortativity**: Degree correlation; mixing patterns; homophily; disassortativity
- **Reciprocity**: Mutual connections; directed networks; dyadic patterns

### Social Network Analysis
- **Social Network Structure**: Egocentric; sociocentric; whole networks
- **Social Ties**: Strong ties; weak ties (Granovetter); tie strength; multiplex ties
- **Structural Holes**: Burt's theory; brokerage; information benefits; constraints
- **Social Capital**: Network capital; bonding; bridging; Coleman; Putnam
- **Diffusion & Contagion**: Information spread; epidemics; cascades; thresholds
- **Community Detection**: Modularity; Louvain; Girvan-Newman; overlapping communities
- **Influence & Social Proof**: Social influence; viral spread; social learning

### Network Dynamics & Evolution
- **Network Growth Models**: Preferential attachment; BA model; node fitness; growth processes
- **Edge Dynamics**: Adding; removing; rewiring; temporal networks
- **Node Dynamics**: Activation; birth; death; dormancy; reactivation
- **Network Formation Games**: Strategic network formation; cooperative; competitive
- **Evolutionary Network Theory**: Co-evolution of structure and behavior
- **Temporal Networks**: Time-aggregated; time-respecting; dynamic communities
- **Network Resilience**: Robustness; attacks; percolation; cascading failures

### Small-World Networks
- **Small-World Phenomenon**: Short paths; high clustering; Watts-Strogatz model
- **Watts-Strogatz Model**: Random rewiring; clustering; path length trade-off
- **Kleinberg's Model**: Geographic small worlds; navigable networks
- **Milgram's Experiments**: Six degrees of separation; small-world experiments
- **Navigation & Search**: Greedy routing; navigability; decentralized search
- **Small-World Effects**: Information; epidemics; synchronization; robust percolation
- **Real-World Small Worlds**: Social; internet; metabolic; citation networks

### Scale-Free Networks
- **Power Law Degree Distributions**: Scale-free property; hubs; robustness paradox
- **Barabási-Albert Model**: Preferential attachment; linear preferential attachment
- **Growth & Preferential Attachment**: Rich-get-richer; cumulative advantage; Yule process
- **Emergence of Scale-Freeness**: Preferential attachment; fitness; optimization
- **Robustness & Fragility**: Error tolerance; attack vulnerability; percolation
- **Diameter & Growth**: Logarithmic growth; densification; shrinking diameters
- **Real Scale-Free Networks**: Internet; WWW; citation; protein; actor networks

### Community Structure
- **Community Definition**: Dense internal; sparse external; overlapping vs disjoint
- **Modularity Optimization**: Modularity measure; quality function; resolution limit
- **Louvain Algorithm**: Multi-level optimization; efficiency; quality; applications
- **Spectral Clustering**: Laplacian matrix; eigenvectors; bisection; normalized cuts
- **Hierarchical Clustering**: Dendrograms; hierarchical decomposition; nested communities
- **Overlapping Communities**: Clique percolation; fuzzy clustering; link communities
- **Dynamic Communities**: Evolution; tracking; birth; death; split; merge

### Epidemics & Spreading Processes
- **Epidemic Models**: SI; SIS; SIR; SIRS; compartments; differential equations
- **Network Epidemics**: Heterogeneous susceptibility; contact structure; invasion
- **Percolation Theory**: Bond; site; epidemic threshold; giant component
- **Contact Networks**: Mixing patterns; degree-correlated; age-structured
- **Immunization Strategies**: Random; targeted; acquaintance; percolation-based
- **Superspreaders**: High-degree nodes; superedges; influence maximization
- **Information Diffusion**: Viral; cascades; thresholds; rumors; innovation

### Biological Networks
- **Protein-Protein Interactions**: Interaction networks; hub proteins; complexes
- **Gene Regulatory Networks**: Transcription factors; targets; motifs; dynamics
- **Metabolic Networks**: Reactions; metabolites; pathways; flux; optimization
- **Neural Networks**: Brain networks; connectomes; functional connectivity; dynamics
- **Food Webs**: Trophic links; predator-prey; stability; species; energy flow
- **Ecological Networks**: Mutualistic; plant-pollinator; seed dispersal; robustness
- **Biomolecular Networks**: Signaling; pathways; cross-talk; disease modules

### Technological Networks
- **Internet Topology**: Router; AS level; power law; hierarchical; evolution
- **World Wide Web**: Links; hubs; authorities; PageRank; structure
- **Power Grids**: Transmission; vulnerability; cascades; blackouts; stability
- **Transportation Networks**: Roads; railways; airlines; route planning; resilience
- **Citation Networks**: Academic papers; citations; impact; knowledge flow
- **Phone Networks**: Call patterns; temporal; mobile; communication dynamics
- **Infrastructure Networks**: Interdependencies; coupled networks; cascading failures

### Information Networks
- **Knowledge Networks**: Semantic networks; ontologies; concept relationships
- **Collaboration Networks**: Co-authorship; joint ventures; team formation
- **Voting Networks**: Approval; preferential; deliberation; polarization
- **Trust Networks**: Reputation; recommendation; trust propagation
- **Recommendation Networks**: User-item; similarity; collaborative filtering
- **Online Social Networks**: Platforms; interaction; virality; influence
- **Financial Networks**: Banks; trades; systemic risk; contagion

### Network Control & Optimization
- **Network Controllability**: Driver nodes; control; minimum set; structural control
- **Network Observability**: Sensor placement; monitoring; network inference
- **Optimal Influence**: Influence maximization; key players; cascades; approximation
- **Network Design**: Cost; performance; robust; resilient; optimization
- **Resource Allocation**: Flow; routing; bandwidth; traffic engineering
- **Network Flow**: Maximum flow; minimum cut; transportation; circulation
- **Distributed Optimization**: Consensus; coordination; decentralized algorithms

### Random Graph Models
- **Erdős-Rényi Model**: Random graphs; G(n,p); G(n,m); properties; phases
- **Configuration Model**: Arbitrary degree sequences; stub matching; random rewiring
- **Random Regular Graphs**: Constant degree; properties; ensemble; limits
- **Small-World Model**: Rewiring; clustering; shortcuts; Watts-Strogatz
- **Random Geometric Graphs**: Spatial; proximity; threshold; connectivity
- **Chung-Lu Model**: Expected degree sequence; general; flexible
- **Inhomogeneous Random Graphs**: Rank; kernel; degree-corrected; general framework

### Statistical Physics of Networks
- **Phase Transitions**: Giant component; percolation; order parameter
- **Percolation Theory**: Site; bond; continuum; critical phenomena
- **Critical Phenomena**: Critical exponents; universality; scaling; renormalization
- **Statistical Ensembles**: Microcanonical; canonical; exponential; configuration
- **Entropy of Networks**: Graph entropy; structural information; complexity
- **Thermodynamics of Networks**: Energy models; Potts; Ising; spin glasses
- **Synchronization**: Kuramoto model; coupled oscillators; network synchronization

### Spectral Methods
- **Adjacency Matrix**: Eigenvalues; eigenvectors; spectral gap; mixing
- **Laplacian Matrix**: Normalized; combinatorial; spectral clustering; Fiedler value
- **Signless Laplacian**: Estrada index; bipartiteness; clustering
- **Random Walk Theory**: Transition matrix; stationary distribution; hitting times
- **PageRank**: Random walk; teleportation; damping; search; ranking
- **Spectral Graph Theory**: Isomorphism; characterization; graph invariants
- **Message Passing**: Belief propagation; cavity method; inference; dynamics

### Multilayer & Multiplex Networks
- **Multilayer Networks**: Layers; dimensions; interdependencies; coupling
- **Multiplex Networks**: Multiple relation types; same nodes; different layers
- **Interdependent Networks**: Cascading failures; coupled percolation; resilience
- **Multilayer Centrality**: Extending centrality; layer aggregation; multiplex
- **Multilayer Community Detection**: Layer coupling; jointly optimizing; consensus
- **Temporal Networks**: Time-ordered; contact sequences; dynamic processes
- **Network of Networks**: Super-networks; mega networks; hierarchical

### Higher-Order Structures
- **Motifs**: Subgraphs; significance; Z-score; over-represented; functional motifs
- **Motif Detection**: ESU algorithm; Fanmod; stochastic; sampling
- **Network Motifs**: Feedforward loops; bi-fans; regulatory; structural roles
- **Clique Analysis**: Cliques; cores; k-cores; plexes; dense subgraphs
- **Simplicial Complexes**: Higher-order topology; homology; complexes; Hodge
- **Hypergraphs**: Hyperedges; beyond pairwise; multi-way; hypergraph models
- **Topological Data Analysis**: Persistent homology; Betti numbers; shape; networks

### Information & Communication Networks
- **Network Flow**: Traffic; bandwidth; congestion; routing; optimization
- **Search Algorithms**: BFS; DFS; Dijkstra; A*; heuristic search
- **Routing Protocols**: Shortest path; OSPF; BGP; hierarchical; distributed
- **Network Traffic**: Models; bursts; heavy tails; self-similarity; scaling
- **Protocol Design**: Layers; TCP/IP; distributed; congestion control
- **Network Latency**: Delays; geographic; processing; queuing; optimization
- **Network Throughput**: Capacity; bottleneck; max-flow; min-cut

### Resilience & Robustness
- **Network Robustness**: Node removal; edge removal; percolation; giant component
- **Error Tolerance**: Random failures; robustness; scale-free; attack vs error
- **Targeted Attacks**: Degree-targeted; betweenness-targeted; optimal attacks
- **Cascading Failures**: Overload; failure propagation; Load; capacity; models
- **Percolation-Based Resilience**: Phase transitions; critical thresholds; recovery
- **Resilience Metrics**: Size of giant component; efficiency; connectivity
- **Network Recovery**: Restoration; repair; regeneration; self-healing

### Network Inference & Mining
- **Network Reconstruction**: From data; pairwise; conditional; maximum likelihood
- **Link Prediction**: Similarity; common neighbors; preferential attachment; temporal
- **Node Classification**: Semi-supervised; label propagation; collective classification
- **Community Discovery**: Unsupervised; overlapping; hierarchical; dynamic
- **Anomaly Detection**: Outlier nodes; edges; subgraphs; attacks; fraud
- **Network Sampling**: Random walk; snowball; exploration; sampling bias
- **Graph Neural Networks**: Deep learning; node embeddings; graph convolution

### Applications in Different Domains
- **Public Health**: Disease spread; contact tracing; intervention; modeling
- **Marketing**: Social influence; word-of-mouth; viral marketing; targeting
- **Security**: Terrorism networks; counterterrorism; intelligence analysis
- **Finance**: Systemic risk; contagion; credit networks; portfolio optimization
- **Urban Planning**: Transportation; infrastructure; mobility; smart cities
- **Neuroscience**: Brain networks; connectomes; cognitive functions; disease
- **Ecology**: Food webs; ecosystems; species interactions; conservation
- **Sociology**: Stratification; mobility; segregation; social capital

### Computational Tools & Libraries
- **NetworkX**: Python library; algorithms; analysis; visualization
- **igraph**: R/Python/C; graph analysis; large networks; efficient
- **Gephi**: Visualization; interactive; platforms; layout algorithms
- **SNAP**: Stanford; large-scale networks; mining; efficient
- **Graph-tool**: Python; statistics; visualization; efficient C++
- **Cytoscape**: Biological networks; apps; plugins; integration
- **Neo4j**: Graph database; query language; Cypher; large-scale storage

### Temporal & Dynamic Networks
- **Time-Varying Networks**: Edge activation; temporal dynamics; sequences
- **Temporal Patterns**: Bursty; periodic; burstiness; inter-event times
- **Temporal Paths**: Time-respecting paths; reachability; delays; windows
- **Dynamic Processes**: Epidemics; diffusion; synchronization; evolution
- **Temporal Metrics**: Centrality evolution; persistence; stability
- **Temporal Clustering**: Dynamic communities; tracking; fate; transitions
- **Simulation**: Dynamics; Gillespie; temporal; agent-based

### Machine Learning on Networks
- **Node Embeddings**: DeepWalk; node2vec; LINE; Skip-Gram; representations
- **Graph Neural Networks**: Message passing; GCN; GAT; pooling; applications
- **Graph Autoencoders**: Unsupervised; link prediction; reconstruction loss
- **Network Embedding**: Transductive; inductive; knowledge graphs; attributes
- **Graph Generation**: Generative models; RNNs; VAEs; adversarial; molecules
- **Graph Attention**: Self-attention; multi-head; inductive; interpretability
- **Link Prediction**: Feature-based; embedding-based; graph neural networks

### Interdisciplinary Connections
- **Sociology**: Social networks; social capital; structuralism; social psychology
- **Physics**: Statistical mechanics; phase transitions; complex systems
- **Computer Science**: Algorithms; data structures; distributed computing
- **Mathematics**: Graph theory; combinatorics; probability; algebra
- **Biology**: Systems biology; ecology; neuroscience; genetics
- **Economics**: Networks; markets; trade; innovation; organizational
- **Epidemiology**: Disease spread; public health; interventions; modeling

## Key Theories

| Theory | Key Figure | Core Idea |
|--------|-----------|-----------|
| Small-World Networks | Watts & Strogatz | Short path lengths and high clustering simultaneously |
| Scale-Free Networks | Barabási & Albert | Power-law degree distribution from preferential attachment |
| Six Degrees of Separation | Milgram; Watts | Any two people connected by short chains |
| Structural Holes | Ronald Burt | Brokerage positions provide social and information advantages |
| Strength of Weak Ties | Mark Granovetter | Weak ties provide novel information and opportunities |
| PageRank | Page & Brin | Importance through random walk with teleportation |

## Important Figures

- **Paul Erdős & Alfréd Rényi**: Random graph theory; G(n,p) model; percolation
- **Duncan Watts**: Small-world networks; social dynamics; algorithms
- **Steven Strogatz**: Small-world; synchronization; complex systems
- **Albert-László Barabási**: Scale-free networks; BA model; network science
- **Mark Granovetter**: Weak ties; social networks; embeddedness
- **Ronald Burt**: Structural holes; social capital; brokerage
- **Santo Fortunato**: Community detection; modularity; benchmarks
- **Mark Newman**: Networks; random graphs; scientific networks
- **Steven Strogatz (again)**: Dynamics; synchronization; Kuramoto
- **James Bagrow**: Network science; systems; collective behavior

## Frontiers

- **Network Neuroscience**: Brain connectivity; cognitive; disorders; dynamics
- **Multilayer Networks**: Interdependencies; coupling; resilience; dynamics
- **Temporal Networks**: Dynamic processes; evolution; causality; information
- **Higher-Order Models**: Beyond pairwise; simplices; hypergraphs; flows
- **Network Geometry**: Latent geometry; hyperbolic; embedding; navigation
- **Network Control**: Controllability; observability; interventions; dynamics
- **Machine Learning on Graphs**: Graph neural networks; embeddings; generation
- **Network Resilience**: Recovery; adaptation; biological; engineered systems

## Applications

- **Social Media**: Influence; communities; recommendation; virality
- **Epidemiology**: Disease modeling; control; vaccination; pandemics
- **Transportation**: Routing; congestion; optimization; resilience
- **Biology**: Protein interactions; disease; evolution; drug targets
- **Finance**: Risk; contagion; trading; systemic risk
- **Internet & WWW**: Search; routing; structure; dynamics
- **Organizations**: Collaboration; innovation; power; culture
- **Smart Cities**: Mobility; infrastructure; energy; sustainability

## Classic Works

- **"Networks, Crowds, and Markets"** by Easley & Kleinberg — Comprehensive intro
- **"Network Science"** by Barabási — Scale-free; emergence; universality
- **"Linked"** by Albert-László Barabási — Popular science network book
- **"Small Worlds"** by Duncan Watts — Small-world phenomenon
- **"Social Network Analysis"** by Borgatti et al. — Methods and applications
- **"Network Analysis"** by Brandes & Erlebach — Algorithmic perspective
- **"Dynamical Systems on Networks"** by Porter & Gleeson — Dynamics on graphs

## See Also

- [Complexity Science](complexity-science.md) — Complex systems foundations
- [Sociology](sociology.md) — Social networks context
- [Data Science](data-science.md) — Data analysis methods
- [Mathematics](mathematics.md) — Graph theory foundations
