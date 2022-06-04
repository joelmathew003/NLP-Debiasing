# NLP-Debiasing

## Aim

The objective of this project is to minimize gender bias in embeddings while preserving valuable qualities such as clustering comparable concepts and solving analogy tasks, in order to improve the ethical aspects in models dependent on such word embeddings.

## Debiasing Results

From the evaluation results (pre hard debiasing on profession words), we inferred that individual biases were not eliminated whereas pair biases were completely removed as our procedure consisted of neutralizing and equalizing the gender subspace. In order to remove individual biases we do hard debiasing on the target words where we now drop the correlation of the gender neutral word (a profession in our case) to a more general gender direction developed through the process of eliminating pair biases. This ensures proper debiasing on the gender subspace.
