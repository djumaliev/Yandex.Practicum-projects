# YP_project_for_wikishop
Yandex Practicum Data Science and Machine Learning Bootcamp: Project for "Wikishop".

The online store "Wikishop" is launching a new service. Now users can edit and supplement product descriptions, similar to wiki communities. In other words, customers suggest their edits and comment on changes made by others. The store needs a tool that will identify toxic comments and send them for moderation.

Train a model to classify comments as positive or negative. You have a dataset with annotations indicating the toxicity of edits.

Build a model with an F1 score of at least 0.75.

Research plan:
- Load and prepare the data.
- Train different models.
- Choose the most accurate model based on the training results.

Data description:

- text: The text of the comment.
- toxic: The target label indicating toxicity.
- The data is located in the file '/datasets/toxic_comments.csv'.

Used lybraries: pandas, matplotlib, numpy, sklearn, seaborn, os, lightgbm, catboost(1.0.3), torch, transformers, re, ntlk, os, random, spacy
