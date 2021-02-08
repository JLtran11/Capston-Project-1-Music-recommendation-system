# Capston-Project-1-Music-recommendation-system
The repository contains all the files associated with the first capstone project

- Utilized the nowplaying-rs dataset of over 17 million listening events to build music recommender system.
- Cleaned and merged three separate tables with pandas to facilitate analysis amd modeling.
- Conducted time series analysis to investigate individual and cohort listening habits, and identify anomolies.
- Constructed user/item sparse matrix object of shape (21220,81343) for algorithm.
- Utilized ALS and Lightfm packages to build two recommenders for comparison.
- Models evaluated with precision at k for performance comparison : ALS: 0.068,  lightfm: 0.125
