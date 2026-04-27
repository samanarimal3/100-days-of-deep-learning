# Day 09 — DataLoaders & Full Training Pipeline

## What I learned
- Custom Dataset class: __len__ and __getitem__
- DataLoader: batching, shuffling, num_workers
- Train / val / test split with random_split
- Mini-batch training loop (per-batch updates)
- StepLR learning rate scheduler
- Model checkpointing: save best, load for inference
- Separate train_one_epoch() and evaluate() functions

# Day 10 — Convolutional Neural Networks (CNNs)

## What I learned
- How convolutions work: filters, stride, padding
- MaxPooling for downsampling and translation invariance
- CNN architecture: Conv+Pool blocks → Flatten → Linear
- torchvision datasets and transforms
- Training on MNIST — 60,000 handwritten digit images
- Visualizing predictions: green=correct, red=wrong