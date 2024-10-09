<h1 align="center">kaggle_leash_bio</h1>

<h4 align="center">BELKA Binding Affinity Prediction using Graph Convolutional Neural Networks (GCN)</h4>

This repository contains the code for predicting the binding affinity of small molecules to specific protein targets using a Graph Convolutional Neural Network (GCN) implemented in PyTorch. The model was built as a submission to the Kaggle competition hosted by Leash Biosciences, which focuses on accelerating drug discovery by leveraging machine learning to predict small molecule-protein interactions.

## Overview
In this competition, participants develop machine learning models to predict the binding affinity of small molecules to three different protein targets. The provided dataset, BELKA, contains millions of data points generated from DNA-encoded chemical library (DEL) technology, offering a unique opportunity for large-scale machine learning applications in drug discovery.

This project uses Graph Convolutional Neural Networks (GCN) to model small molecules as graphs where atoms are nodes and bonds are edges. The GCN-based model learns molecular representations to predict binding affinity to a given protein target.
## Deploying

We use [bump-my-version](https://github.com/callowayproject/bump-my-version) to release a new version.
This will create a git tag that is used by [poetry-dynamic-version](https://github.com/mtkennerly/poetry-dynamic-versioning) to generate version strings and update `CHANGELOG.md`.

For example, to bump the `minor` version you would run the following command.

```bash
poetry run bump-my-version bump minor
```

After releasing a new version, you need to push and include all tags.

```bash
git push --follow-tags
```

## License

This project is released under the MIT License as specified in `LICENSE.md`.
