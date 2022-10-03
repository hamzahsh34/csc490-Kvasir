# csc490 Kvasir dataset

Group Name: Team Step Brothers

We aim to create a machine learning model with the goal of improving the classification system on the lower GI tract of the HyperKvasir dataset.

The HyperKvasir dataset provides 1000 segmented images, 99 000 unlabeled images, and 10 000 labeled images, granted we will have to create our own validation set, there is plenty of data to use when building our model. Another benefit to choosing this dataset is in its organization, since the data has already been organized by the authors, splitting the data to only choose images we need will be simple, in our case, we only wish to work with the Lower GI Tract, having the ability to filter through all 100 000 images is beneficial.

Looking at previous attempts using this dataset, a common issue amongst other groups was extrapolating the model to account for pathological findings in the upper and lower GI tract. Since the regions of a tract vary heavily, attempting to create a model that works effectively for both poses a challenge, we believe that an effective way to tackle this issue is to split the dataset and create separate models that are focused on the upper and lower half.
