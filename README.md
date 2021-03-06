# TimbreTransfer

**Timbre Transfer using Differentiable Digital Signal Processing based on "DDSP" repository.**

![example](ddsp_autoencoder.png)

**Check how it works on Google Colab:**
- Russian Language [![Colab](https://camo.githubusercontent.com/52feade06f2fecbf006889a904d221e6a730c194/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/github/tg-bomze/TimbreTransfer/blob/master/TimbreTransfer_Rus.ipynb)
- Bad English Translation [![Colab](https://camo.githubusercontent.com/52feade06f2fecbf006889a904d221e6a730c194/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/github/tg-bomze/TimbreTransfer/blob/master/TimbreTransfer_Eng.ipynb)

*Attention. Sound recording doesn't work on all browsers. Testing was in Google Chrome and Opera.*

**Based on:** [DDSP](https://github.com/magenta/ddsp)

**Article:** [Differentiable Digital Signal Processing](https://openreview.net/forum?id=B1x1ma4tDr)

**Examples:** [Audio](https://storage.googleapis.com/ddsp/index.html)

Differentiable Digital Signal Procressing (DDSP) enables direct integration of classic signal processing elements with end-to-end learning, utilizing strong inductive biases without sacrificing the expressive power of neural networks. This approach enables high-fidelity audio synthesis without the need for large autoregressive models or adversarial losses, and permits interpretable manipulation of each separate model component. In all figures below, linear-frequency log-magnitude spectrograms are used to visualize the audio, which is synthesized with a sample rate of 16kHz.

**Result Example:**

[![YouTube](youtube.png)](https://youtu.be/6x17-1_5Znc)

**Citation**

```latex
@inproceedings{
  engel2020ddsp,
  title={DDSP: Differentiable Digital Signal Processing},
  author={Jesse Engel and Lamtharn (Hanoi) Hantrakul and Chenjie Gu and Adam Roberts},
  booktitle={International Conference on Learning Representations},
  year={2020},
  url={https://openreview.net/forum?id=B1x1ma4tDr}
}
```
