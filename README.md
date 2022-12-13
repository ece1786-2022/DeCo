# ECE1786 | Project Name: DeCo.

## Team members: Tan Xu, Mukesh Reddy Kayadapuram

## Introduction

The goal of Project DeCo. is to create an application that can classify companies into multiple industry groups by analyzing their descriptions, annual reports, and other text artifacts that detail their business strategy and operations. Leading classification standards in the market only label companies with a single industry group, providing an incomplete picture that often ignores a company's new expansions or business ventures.

Our new multi-industry group classification approach allows for a more detailed and nuanced view of a company's operations. This can provide investors with additional insights when building a diversified stock portfolio with targeted industry exposures. A weighting system can be further developed to help compute the industry group ratio of a portfolio. For example, Amazon could be further decomposed into "Retailing", "Software & Services", and "Media & Entertainment" to better reflect its e-commerce, cloud services, and content creation segments.

In today's rapidly changing business environment, companies often enter and exit new businesses quickly. NLP and ML models can be used to monitor companies' up-to-date information from different sources to detect changes in their operations. This allows for real-time updating of classifications and potential integration into data engineering pipelines. This approach shifts the decision-making process from relying only on revenue to using text-based data to classify a company.

## Illustration / Figure

![alt text](https://github.com/ece1786-2022/DeCo/blob/final_edits/data/project_figure.png)


**Note:** Some data files are split into parts as Github is not allowed to upload a file greater than 25 MB.
Files that are splitted:
1. dataset_1.parquet
2. train_validation_data_with_embeddings.csv

To get the original data files, please extract them from here: https://drive.google.com/drive/folders/1JNNcgxbIXvwYSVubrmQ99_hxK0fcrWEg?usp=share_link
