

# Block 6: Introduction to Deep Learning

## Overview

In this block, we explore the foundations of deep learning, beginning with a hands-on project using the fast.ai library. The focus is on training and interpreting a convolutional neural network (CNN) to classify images, gaining intuition about neural network architecture, and understanding how deep learning differs from traditional machine learning.

## Goals

- Understand what neural networks are and how they work
- Learn the basic structure of deep learning models (layers, activations, loss)
- Train and evaluate an image classifier using fast.ai Lesson 1
- Experiment with hyperparameters and datasets
- Communicate deep learning results in a human-centered, explainable way

## Tools and Resources

- `fast.ai` Lesson 1 (2022 edition)
- Optional: Andrew Ng's Coursera course on Neural Networks and Deep Learning
- Google Colab with GPU (recommended)
- Jupyter Notebooks (locally via VSCode or Colab)

## 8-Day Schedule

| Day | Objective                                                       | Key Deliverables                                                   |
|-----|------------------------------------------------------------------|--------------------------------------------------------------------|
| 1   | Define goals and set up environment                             | fast.ai or Colab environment, `block6_schedule.md`              |
| 2   | Train CNN on fast.ai pet dataset                                | `lesson1_pet_model.ipynb`, model `.pkl` saved                   |
| 3   | Learn and document NN terminology                               | Updated notebook with markdown, `glossary.md`                   |
| 4   | Experiment with a training parameter                            | `lesson1_experiment.ipynb`, notes on training change            |
| 5   | Train model on new dataset (e.g., MNIST)                        | `lesson1_alt_dataset.ipynb`, new model trained                  |
| 6   | Generate predictions and visualizations                         | `plots/predictions_sample.png`, visuals in notebook             |
| 7   | Write summary for a non-technical audience                      | `neural_net_summary.md`, plain-language explanation             |
| 8   | Clean notebooks, tag repo, finalize README                      | Clean notebooks, 🔖 `block6_complete` tag, updated `README.md`  |

## Folder Structure

```
block6_intro_to_deep_learning/
├── notebooks/
├── models/
├── plots/
│   └── summary/
├── data/
├── README.md
```

## End of Block Deliverables

- Trained fast.ai CNN model on pet dataset and new dataset
- Annotated notebooks with markdown explanations
- Visual prediction outputs and performance interpretation
- Human-centered summary of neural network function
- Updated documentation and clean version-controlled repo