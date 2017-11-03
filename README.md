# LeafClassification_ML
Various learning algorithms are tested for the identification of 99 species of plants from binary leaf images and extracted features, including shape, margin & texture.
The dataset used is from the UCI machine learning repository.

# Dataset

The dataset consists approximately 1,584 images of leaf specimens (16 samples each of 99 species) which have been converted to binary black leaves against white backgrounds. Three sets of features are also provided per image: a shape contiguous descriptor, an interior texture histogram, and a ﬁne-scale margin histogram. For each feature, a 64-attribute vector is given per leaf sample.

# Data fields

id - an anonymous id unique to an image
margin_1, margin_2, margin_3, ..., margin_64 - each of the 64 attribute vectors for the margin feature
shape_1, shape_2, shape_3, ..., shape_64 - each of the 64 attribute vectors for the shape feature
texture_1, texture_2, texture_3, ..., texture_64 - each of the 64 attribute vectors for the texture feature

