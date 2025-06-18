# Summary: Understanding a Neural Network (Plain Language)

A neural network is a kind of computer program that learns to recognize patterns by looking at many examples. Instead of being told the rules for how to tell one thing from another, it figures them out on its own. It’s inspired by how the human brain works, using layers of simple math operations to gradually improve its guesses.

In this project, I trained a neural network to tell the difference between the handwritten digits 3 and 7. I used a small, clean dataset of labeled examples, and taught the model using a process called “fine-tuning” — starting with a pretrained model and then showing it only 3s and 7s. The model learned to correctly classify these digits with over 99% accuracy on unseen test data.

One interesting challenge came when trying to classify digits drawn by hand in a sketchpad. Even though the model performed nearly perfectly on traditional images, it struggled at first with hand-drawn inputs until I adjusted the image formatting to match the training style (e.g. centering, padding, inverting). Once the inputs were properly preprocessed, the model performed reliably again.

This project shows how even a small, well-scoped neural network can be surprisingly powerful, as long as the inputs match what it was trained on. It also highlights how thoughtful design — especially in how people interact with models — is key to success in human-centered machine learning.