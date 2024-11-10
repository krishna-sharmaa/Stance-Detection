# Stance-Detection

# Political Stance Detection using TwinViews-13k Dataset

This project explores political stance detection using the **TwinViews-13k** dataset, which contains 13,855 pairs of left-leaning and right-leaning political statements. Each statement pair is matched by topic, making the dataset suitable for studying political bias and ideological balance in machine learning models. The project aims to evaluate various models in detecting political stance by comparing performance metrics such as accuracy, recall, and F1 score.

## Dataset Overview

**TwinViews-13k** provides a unique resource for analyzing political stance, featuring:
- **13,855 pairs** of left-leaning and right-leaning statements
- Statements matched by topic (e.g., taxes, climate, education)
- Statements generated with GPT-3.5 Turbo and curated to maintain ideological balance and relevance

The dataset facilitates the study of political bias in machine learning, focusing on truthfulness alignment in reward models and language models.

- **Curated by**: Suyash Fulay, William Brannon, Shrestha Mohanty, Cassandra Overney, Elinor Poole-Dayan, Deb Roy, Jad Kabbara
- **License**: cc-by-4.0
- **Sources**:
  - [GitHub Repository](https://github.com/sfulay/truth_politics)
  - [Research Paper](https://arxiv.org/abs/2409.05283)

## Models Used

The following models are implemented to perform stance detection on the dataset:

1. **Logistic Regression**: A simple yet effective linear model for binary classification.
2. **Naive Bayes**: Probabilistic classifier that assumes feature independence.
3. **Decision Tree**: Non-linear model that partitions data based on feature splits.
4. **Support Vector Machine (SVM)**: Finds a hyperplane that maximally separates left-leaning and right-leaning statements.
5. **DistilBERT with Sequence Classification Head**: A transformer-based model fine-tuned for sequence classification to leverage deep learning in detecting stance.

## Evaluation Metrics

The models are evaluated on the following metrics:

- **Accuracy**: Measures the proportion of correctly classified instances.
- **Recall**: Measures the model's ability to capture all relevant instances of each class.
- **F1 Score**: Balances precision and recall to provide a single metric for model performance.

## Project Goals

- To compare the performance of simpler models and a transformer-based model (DistilBERT) for political stance detection.
- To understand how well each model can capture the ideological distinctions present in the TwinViews-13k dataset.
- To explore the impact of different model architectures on detecting political stance in machine-generated political statements.

## Usage

Clone the repository and run the provided notebook or scripts to train and evaluate the models on the TwinViews-13k dataset. Results will be saved and can be visualized to compare each model's performance metrics.

```shell
git clone https://github.com/krishna-sharmaa/Stance-Detection.git
