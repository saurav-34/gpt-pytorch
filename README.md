# gpt-pytorch
 

A step-by-step derivation and implementation of the GPT architecture from scratch, following the original paper on GPT: [Improving Language Understanding by Generative Pre-Training (Radford et al. 2018)](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf) and the transformer model: [Attention is All You Need (Vaswani et al. 2017)](https://arxiv.org/abs/1706.03762). This is mostly a personal exercise to deepen my understanding on multi-head self-attention, transformer, causal languaging modelling and unsupervised pretraining, but can also serve as a guide for anyone interested to derive the GPT architecture from first principle.

## Usage

The complete derivation walkthrough is on the Jupyter notebook `derive-gpt-from-scratch.ipynb`.

At the end of the walkthrough, we will get a GPT model that can write Shakespeare-style plays (or gibberish).

Sample output of it trained on CPU for 20000 steps:
```
broathed's construns of that love, which are--

GLOUCESTER:
And he own cuntest of his hounds, poor country,-
With honest lose, he was it sincer.

NORTLANNE:
How not to says from his lord's guilt.
Nothing munis is toesth heme,
Rounce to nare have cold.

GLOUCESTER:
But how ip, nor morue way dear who spay, and I
Thou, somence that dath knowns, and for it the Claudio;
Thou clook, and, way to merry, hell a Volst's mock of
a grepard and the king of sorrower the treto the fhight
varter's habste son; a sunce of yet combriness are gone stouch,
my poor to-mooth, sir have, oil.
Now officery, proner, we men you come in the vient tower,
Know have a kised in succeite used
To Onch: no childs a parsuest, where your goodlish!

HENRY PELIZABOL:
Ay, a city molece took dayying worse more:
Camilonius long pose it; farewell.

QUEEN MARGARET:
Come, goes my ging trough, from you my head.

KING EDWE RICHARD IV:
Not-none. Boy: shief, my love,
Lord lord, art it is nothier are than he your had,
With hast him
The
```

## Acknowledgments

This project references the following resources:

- [Improving Language Understanding by Generative Pre-Training (Radford et al. 2018)](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf)
- [Attention is All You Need (Vaswani et al. 2017)](https://arxiv.org/abs/1706.03762)
- [GPT Guide by Andrej Karpathy](https://m.youtube.com/watch?v=kCc8FmEb1nY)
