1. Dataset

Link: manythings.org/anki

The dataset used to build the model in this project is the Tab-delimited Bilingual Sentence Pairs (Japanese - English). The dataset consists of bilingual sentence pairs selected by the author from the Tatoeba Project, with the criteria that the sentence pairs must be contributed by native speakers and the English translations must be of sufficient quality. The original dataset contains 93,356 Japanese-English bilingual sentence pairs, with each data row consisting of three attributes:

EN: the English sentence.

JAP: the Japanese sentence that has a similar meaning to the English sentence in the EN column.

citation: the source of the contribution and the contributor.

2. Project Description

Built a custom Japanese-to-English machine translation model using TensorFlow, trained on parallel corpora.

Preprocessed text data with tokenization and padding.

Implemented an encoder-decoder architecture with attention mechanism to improve translation accuracy and fluency.
