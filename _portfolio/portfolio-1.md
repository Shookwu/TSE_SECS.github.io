---
title: "Speech Separation Experiment Results"
excerpt: "Displaying speech separation results before and after separation, with audio examples and experimental data <br/><img src='/images/500x300.png'>"
collection: portfolio
---

# Paper Title: **Speech Separation Using BSRNN and DPCCN Models**

## Abstract

This paper presents a comparison between two state-of-the-art models for speech separation: BSRNN (Bidirectional Speech Recurrent Neural Network) and DPCCN (Deep Parallel Convolutional Channel Network). We evaluate the effectiveness of these models on mixed speech data and report experimental results, including the performance of the models on SNR, SDR, ISR, and other relevant metrics. Additionally, we provide audio samples to demonstrate the separation performance before and after applying the models.

## Model Architecture

![Model Architecture](images/model.png)

### Speech Separation Experiment Display

#### 1. BSRNN-Based Results

##### Audio Comparison Table

| Audio ID | Mixed Audio           | Method 1 Separation   | Method 2 Separation   | Ground Truth (Speaker 1) |
|----------|-----------------------|-----------------------|-----------------------|--------------------------|
| 1        | <audio controls><source src="/audio/mixed_audio_1.wav" type="audio/wav">Your browser does not support audio playback.</audio> | <audio controls><source src="/audio/separated_audio_method1_1.wav" type="audio/wav">Your browser does not support audio playback.</audio> | <audio controls><source src="/audio/separated_audio_method2_1.wav" type="audio/wav">Your browser does not support audio playback.</audio> | <audio controls><source src="/audio/first_speaker_groundtruth_1.wav" type="audio/wav">Your browser does not support audio playback.</audio> |
| 2        | <audio controls><source src="/audio/mixed_audio_2.wav" type="audio/wav">Your browser does not support audio playback.</audio> | <audio controls><source src="/audio/separated_audio_method1_2.wav" type="audio/wav">Your browser does not support audio playback.</audio> | <audio controls><source src="/audio/separated_audio_method2_2.wav" type="audio/wav">Your browser does not support audio playback.</audio> | <audio controls><source src="/audio/first_speaker_groundtruth_2.wav" type="audio/wav">Your browser does not support audio playback.</audio> |
| 3        | <audio controls><source src="/audio/mixed_audio_3.wav" type="audio/wav">Your browser does not support audio playback.</audio> | <audio controls><source src="/audio/separated_audio_method1_3.wav" type="audio/wav">Your browser does not support audio playback.</audio> | <audio controls><source src="/audio/separated_audio_method2_3.wav" type="audio/wav">Your browser does not support audio playback.</audio> | <audio controls><source src="/audio/first_speaker_groundtruth_3.wav" type="audio/wav">Your browser does not support audio playback.</audio> |

##### Experiment Results

![BSRNN-based Experiment Results](/images/bsrnn_results.png)

---

#### 2. DPCCN-Based Results

##### Audio Comparison Table

| Audio ID | Mixed Audio           | Method 1 Separation   | Method 2 Separation   | Ground Truth (Speaker 1) |
|----------|-----------------------|-----------------------|-----------------------|--------------------------|
| 1        | <audio controls><source src="/audio/mixed_audio_1.wav" type="audio/wav">Your browser does not support audio playback.</audio> | <audio controls><source src="/audio/separated_audio_method1_1.wav" type="audio/wav">Your browser does not support audio playback.</audio> | <audio controls><source src="/audio/separated_audio_method2_1.wav" type="audio/wav">Your browser does not support audio playback.</audio> | <audio controls><source src="/audio/first_speaker_groundtruth_1.wav" type="audio/wav">Your browser does not support audio playback.</audio> |
| 2        | <audio controls><source src="/audio/mixed_audio_2.wav" type="audio/wav">Your browser does not support audio playback.</audio> | <audio controls><source src="/audio/separated_audio_method1_2.wav" type="audio/wav">Your browser does not support audio playback.</audio> | <audio controls><source src="/audio/separated_audio_method2_2.wav" type="audio/wav">Your browser does not support audio playback.</audio> | <audio controls><source src="/audio/first_speaker_groundtruth_2.wav" type="audio/wav">Your browser does not support audio playback.</audio> |
| 3        | <audio controls><source src="/audio/mixed_audio_3.wav" type="audio/wav">Your browser does not support audio playback.</audio> | <audio controls><source src="/audio/separated_audio_method1_3.wav" type="audio/wav">Your browser does not support audio playback.</audio> | <audio controls><source src="/audio/separated_audio_method2_3.wav" type="audio/wav">Your browser does not support audio playback.</audio> | <audio controls><source src="/audio/first_speaker_groundtruth_3.wav" type="audio/wav">Your browser does not support audio playback.</audio> |

##### Experiment Results

![DPCCN-based Experiment Results](/images/dpccn_results.png)

---
