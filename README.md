# Whitening Black-Box Neural Networks, ICLR'18

#### Seong Joon Oh, Max Augustin, Bernt Schiele, Mario Fritz.

#### Max-Planck Institute for Informatics.

[Whitening Black-Box Neural Networks](https://arxiv.org/abs/1711.01768), ICLR'18

Many deployed learned models are black boxes: given input, returns output. Internal information about the model, such as the architecture, optimisation procedure, or training data, is not disclosed explicitly as it might contain proprietary information or make the system more vulnerable. This work shows that such attributes of neural networks can be exposed from a sequence of queries. This has multiple implications. On the one hand, our work exposes the vulnerability of black-box neural networks to different types of attacks -- we show that the revealed internal information helps generate more effective adversarial examples against the black box model. On the other hand, this technique can be used for better protection of private content from automatic recognition models using adversarial examples. Our paper suggests that it is actually hard to draw a line between white box and black box models.

## Installation

Clone this repository recursively.

```bash
$ git clone https://github.com/coallaoh/WhitenBlackBox.git --recursive
```