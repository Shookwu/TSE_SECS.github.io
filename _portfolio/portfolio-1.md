---
title: "语音分离实验结果"
excerpt: "展示语音分离前后的音频及实验数据 <br/><img src='/images/500x300.png'>"
collection: portfolio
---

## 语音分离实验展示

### 1. 分离前的音频
<audio controls>
    <source src="/audio/mixed_audio.wav" type="audio/wav">
    您的浏览器不支持音频播放。
</audio>

### 2. 分离后的音频
**说话人 1**
<audio controls>
    <source src="/audio/first_speaker_audio.wav" type="audio/wav">
    您的浏览器不支持音频播放。
</audio>

**说话人 2**
<audio controls>
    <source src="/audio/second_speaker_audio.wav" type="audio/wav">
    您的浏览器不支持音频播放。
</audio>

### 3. 实验结果对比

| 评估指标 | 分离前 | 分离后 |
|----------|--------|--------|
| SNR (dB) | 15.2   | 23.8   |
| SDR (dB) | -5.3   | 10.5   |
| ISR (dB) | 2.1    | 9.7    |

**说明：**
- `SNR`（信噪比）：衡量信号质量的提升情况。
- `SDR`（信号失真比）：评估分离后音频的质量。
- `ISR`（干扰信号比）：衡量抑制干扰的效果。

---
如果你将此文件命名为 `.md` 并放入 Jekyll 的 `portfolio` 目录下，它会自动解析，并在前端展示音频播放器和表格。  
