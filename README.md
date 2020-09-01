# London gang social network analysis

A simple exploratory analysis in R of a social network consisting of criminals in a London-based gang.

Data is on co-offending in a London-based inner-city street gang, 2005-2009, operating from a social housing estate. The data comes from anonymized police arrest and conviction data for all confirmed members of the gang. It consists of four networks: hang-out together, co-offend together, commit serious crime together and commit serious crime together & kin. 

We compute a number of simple network statistics, like degree distribution, proportion of homophilic ties and modularity. We also provide a number of network plots and comment on our observations throughout.

We then perform Conditional Uniform Graph tests to test whether same age group ties and ties between individuals of a common birthplace are more likely, first conditioned on network size and then additionally on the number of isolated nodes. Our findings suggest e.g. that individuals of a common birthplace are significantly more likely to commit serious crime together.

We note that more sophisticated techniques like Quadratic Assignment Procedures or Exponential Random Graph Models could have been used to perform the tests.
