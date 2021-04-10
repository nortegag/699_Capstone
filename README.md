# 699_Capstone
SI699 Capstone: MSD Popularity Prediction

Relevant notebooks, in order:
- prep-data-search
- spotify-data-search
- retrieval-eval
- spotify-data-features
- data-merge
- reg-sampling

The other notebooks are foundational. The modeling one was used as basis for regression with sampling. The hybrid-model was a classification approach that was eventually abandoned. The PCA nb tries PCA, and uses that output in the Modeling nb. Deep learning was early on, but no more dev on that.

Note that the whole SongCSVFull.csv is not included because of limits in file size. Still, to run modeling, you should only go to the reg-sampling nb and use the "dataModel.csv"
