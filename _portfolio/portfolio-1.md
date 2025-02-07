---
title: "BSRNN 实验结果"
excerpt: "展示 BSRNN 与提出方法的实验结果 <br/><img src='/images/500x300.png'>"
collection: portfolio
---

## BSRNN 实验结果

### 语音分离前后展示

<figure>
  <figcaption>原始混合语音与分离后语音示例</figcaption>
  <audio controls>
    <source src="path_to_original_audio" type="audio/wav">
    Your browser does not support the audio element.
  </audio>
  <audio controls>
    <source src="path_to_separated_audio" type="audio/wav">
    Your browser does not support the audio element.
  </audio>
</figure>

### 实验概述

此表展示了使用 ECAPA-TDNN 和 ResNet34 两种说话人编码器结构，并结合预训练和联合训练两种策略的 BSRNN 实验结果。上升箭头表示较高的数值代表更好的性能。

### 结果表格

<table border="1" style="width:100%; border-collapse: collapse;">
    <thead>
        <tr>
            <th colspan="2"><b>Speaker Model</b></th>
            <th><b>Train Method</b></th>
            <th><b>Loss</b></th>
            <th><b>CLS</b></th>
            <th><b>SI_SDR</b><br>(dB↑)</th>
            <th><b>Acc.</b><br>(%)↑</th>
            <th><b>Sim.</b><br>(%)↑</th>
            <th><b>SDR</b><br>(dB↑)</th>
            <th><b>PESQ</b><br>(↑)</th>
            <th><b>STOI</b><br>(↑)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="3"><b>ECAPA</b></td>
            <td rowspan="3"><b>Pretrained</b></td>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
            <td>13.34</td>
            <td>90.08</td>
            <td>84.28</td>
            <td>14.80</td>
            <td>2.72</td>
            <td>90.34</td>
        </tr>
        <tr>
            <td>✔</td>
            <td>&nbsp;</td>
            <td>13.85</td>
            <td>92.10</td>
            <td><b>86.92</b></td>
            <td>14.85</td>
            <td>2.74</td>
            <td>92.95</td>
        </tr>
        <tr>
            <td>✔</td>
            <td>✔</td>
            <td><b>14.29</b></td>
            <td><b>95.15</b></td>
            <td>86.83</td>
            <td><b>15.19</b></td>
            <td><b>2.77</b></td>
            <td><b>91.06</b></td>
        </tr>
        <tr>
            <td rowspan="3"><b>ResNet34</b></td>
            <td rowspan="3"><b>Pretrained</b></td>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
            <td>13.21</td>
            <td>92.26</td>
            <td>85.84</td>
            <td>14.58</td>
            <td>2.71</td>
            <td>90.08</td>
        </tr>
        <tr>
            <td>✔</td>
            <td>&nbsp;</td>
            <td>13.64</td>
            <td>93.82</td>
            <td><b>86.81</b></td>
            <td>14.68</td>
            <td><b>2.73</b></td>
            <td>90.33</td>
        </tr>
        <tr>
            <td>✔</td>
            <td>✔</td>
            <td><b>13.70</b></td>
            <td><b>94.36</b></td>
            <td>86.57</td>
            <td><b>14.72</b></td>
            <td>2.71</td>
            <td><b>90.82</b></td>
        </tr>
    </tbody>
</table>
