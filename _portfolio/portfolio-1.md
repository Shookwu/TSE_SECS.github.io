
<div style="text-align: center;">
  <h1> <strong>TARGET SPEAKER EXTRACTION WITH SPEAKER  SIMILARITY AND CENTROID-BASED OPTIMIZATION</strong></h1>
</div>

## Abstract

Target Speaker Extraction (TSE) uses a reference cue to extract the target speech from a mixture. In TSE systems relying on audio cues, the speaker embedding from the enrolled speech is crucial for performance, as these embeddings directly affect system success. However, these embeddings may suffer from speaker identity confusion. Unlike previous studies that focus on enhancing the performance of speaker embedding extraction, we address this challenge by proposing a Speaker Encoder Cosine Similarity (SECS) loss, which integrates the speaker centroid. This approach improves the consistency of speaker features between the enrolled and extracted speech by constraining the similarity of their representations. Furthermore, the incorporation of conditional loss suppression into the SECS loss results in comprehensive performance improvements. Experimental results validate the effectiveness of the proposed method in advancing the TSE task. A speech sample is available online.

## Model Architecture

<embed src=" ../images/model.pdf" width="800px" height="600px" type="application/pdf" />

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
