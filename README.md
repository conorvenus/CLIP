# CLIP Reimplementation

🔍 **Reproduced implementation of OpenAI's CLIP model for vision-language understanding.**

## Overview

This repository contains a reimplementation of the CLIP (Contrastive Language–Image Pretraining) model originally developed by OpenAI. CLIP is designed to simultaneously learn a space for images and texts, mapping semantically similar images and text to similar vector angles in the space. I reproduce the initial results using the method followed in the paper.

## Features

- End-to-end reimplementation of CLIP
- Can optionally use pretrained DistilBERT and ResNet-50
- Supports training on custom image-text datasets
- Uses the `annoy` library (approximate nearest neighbours) to quickly process queries by building an index of embeddings

## Installation

To use this repository, clone it and install the necessary dependencies:

**TODO**