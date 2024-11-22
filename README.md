# Intro

This project adds text generation into a data augmentation pipeline for biomedical text data. The text generated is intended to provide context to a body of text data that is then used to perform 
information extraction tasks with NLP models, like PubMedBERT.

## Requirements

Refer to the [requirements](REQUIREMENTS.txt) file.

## Data

Our data comes from a publicly available data set and intended for relation extraction tasks. To make it easier for viewers to access, we have included the files that we used here, in the [RE-Data/BC5CDR](RE-Data/BC5CDR/) directory.

## Files to Use

The [Modified_Implementation](Modified_Implementation/) directory contains the python notebook for augmenting the data and the augmented files created from it. The final notebook shows the comparison between the augmented data and the original on the relation extraction task.
