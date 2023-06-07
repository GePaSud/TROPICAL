# TROPICAL: TRiplet Opinion Polynesian Information for Cultural and Local Tourism

## Description

TROPICAL is a unique French Natural Language Processing (NLP) dataset designed specifically for sentiment analysis of tourist reviews. Comprising a collection of tourist reviews sourced from [TripAdvisor](https://www.tripadvisor.com/), the focus of this dataset is on accommodation experiences in French Polynesia. Our goal with TROPICAL is to drive forward research and advancements in the sentiment analysis field for the French language.

The repository houses the TROPICAL dataset, featuring `1592` distinct comments and a total of `10729` sentiment triplets. The data has been structured into two mutually exclusive subsets, characterized by the presence or absence of overlapping triplets, where the aspect or opinion of a triplet is found within another triplet of the same comment.

For ease of use, the dataset, along with its subsets, has been partitioned into training, validation, and test sets, using the following distribution:

- Training set: 70%
- Validation set: 15%
- Test set: 15%

In addition, the untouched, unsplitted dataset is readily available, residing within its respective folder and labeled according to the folder's name.

## Dataset Structure

The TROPICAL dataset is divided into the following segments:

1. **Original Dataset**: This collection includes all triplets, housed within the `original_dataset` folder.
2. **Overlapping Triplets**: This subset consists of comments that feature overlapping triplets. It is located within the `overlapping_subset` folder and includes `1125` comments, amounting to `8494` triplets.
3. **No Overlapping Triplets**: This subset contains comments that are free from overlapping triplets. It is located within the `no_overlapping_subset` folder and includes `467` comments, amounting to `2235` triplets.

Each sentiment triplet in the dataset conforms to the (Aspect, Opinion, Sentiment) schema. The sentiment is categorized as either positive or negative, whereas the aspect and opinion are textual strings. Each element of the triplet, apart from the sentiment, is accompanied by its position within the comment. Furthermore, each comment is available in an array format.

## References

For in-depth understanding of the methodologies employed in the collation and processing of this dataset, we recommend referring to our research paper:

- **REFERENCE TO FUTURE PAPER**.

## HuggingFace 

In addition to this repository, TROPICAL, along with its related subsets, is also conveniently accessible via the [Hugging Face]() platform.
