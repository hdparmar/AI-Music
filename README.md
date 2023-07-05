# Ai Music Generation Challenge 2022 - RAVE Reel Generation

This project is a submission for the Ai Music Generation Challenge 2022, specifically focusing on the sub-challenge of generating plausible reels using RAVE (Realtime Audio Variational autoEncoder).

## Table of Contents
- [Introduction](#introduction)
- [System Overview](#system-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [References](#references)

## Introduction
This project aims to build an artificial system that generates reels, adhering to the standards and characteristics of the reels published in F. O'Neill's "The Dance Music of Ireland: O'Neill's 1001" (1907). RAVE, a Realtime Audio Variational autoEncoder, is utilized for fast and high-quality audio waveform synthesis.

## System Overview
The system consists of the following components:
- Data preprocessing: Preparing the training data by extracting and transforming the reels from F. O'Neill's collection into a suitable format for training RAVE.
- Model architecture: Implementing the RAVE model architecture for audio waveform synthesis.
- Training procedure: Training RAVE using the preprocessed reel dataset, incorporating the two-stage training procedure (representation learning and adversarial fine-tuning) mentioned in the RAVE paper.
- Reel generation: Utilizing the trained RAVE model to generate a collection of plausible reels.

