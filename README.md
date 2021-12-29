# rit
reverse informational theory on lobbying

# design
add some visualization how you create multivariate signals to causal graph per legisators and summarize those (more than 400 * 20 years?) to one .. MEAN OF GRAPH

# methodological issues

Sparsity
- Sparse Granger Casuality 

Discrete 
- Categorical Granger https://epubs.siam.org/doi/pdf/10.1137/20M133097X

Any other data types? (other than ts) 
- like before/after probability distribution (averaged out)

Transfer Entropy 
  - Relation to G-Causality 
    - Granger causality and transfer entropy are equivalent for Gaussian variables https://arxiv.org/abs/0910.4514
      - refer to this lit for use of det for multi-variate generalization

  - Multivariate Time Series Forecasting with Transfer Entropy Graph (GNN+TE+Granger)

* note that Transfer Entropy is studied with Granger Causality because of its equivalence on Gaussian Assumption

Deep approach
  - Causal Discovery with Attention-Based
Convolutional Neural Networks

Deermination of How to Slice the Window of Interest (hyperparameter)
  - Maybe using the average contract period of observations (e.g. Samsung - Square Patton Boogs - 2 years) 

Limits of Granger
  - linear
  - Stationaery 
  
We need a model that can tackle non-linear, non-stationaery mts

Non linear causality
