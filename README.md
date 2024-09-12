# Gonig trough Neural Networks: Zero to Hero from Andrej Karpathy(https://karpathy.ai/)

[Playlist for the videos used in this training.](https://www.youtube.com/embed/videoseries?si=kLqM_OkV6fV9nMgF&amp;list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ)

## Requierments:

### Python libraries:
* graphviz (https://pypi.org/project/graphviz/)
* numpy (https://numpy.org/)
* matplotlib (https://matplotlib.org/)

### Externals:
* graphviz (https://graphviz.org/download/) \
  (for windows it has to be added to the Path environment value [ex: C:\Program Files\Graphviz\bin])
* jupyter notebooks (https://jupyter.org/install)


## Chapters:

* The spelled-out intro to neural networks and backpropagation:\
  [the_spelled-out_intro_to_neural_networks_and_backpropagation_building_micrograd.ipynb](https://github.com/popescualexandrucristian/andrej_karpathy_ai_trainining_2024/blob/master/the_spelled-out_intro_to_neural_networks_and_backpropagation_building_micrograd.ipynb)

* The spelled-out intro to language modeling: building makemore:\
  [building_makemore/the_spelled-out_intro_to_language_modeling_building_makemore_01.ipynb](https://github.com/popescualexandrucristian/andrej_karpathy_ai_trainining_2024/blob/master/building_makemore/the_spelled-out_intro_to_language_modeling_building_makemore_01.ipynb) \
  [building_makemore/the_spelled-out_intro_to_language_modeling_building_makemore_02.ipynb](https://github.com/popescualexandrucristian/andrej_karpathy_ai_trainining_2024/blob/master/building_makemore/the_spelled-out_intro_to_language_modeling_building_makemore_02.ipynb)

* Building makemore Part 2: MLP: \
  [building_makemore/the_spelled-out_intro_to_language_modeling_building_makemore_03.ipynb](https://github.com/popescualexandrucristian/andrej_karpathy_ai_trainining_2024/blob/master/building_makemore/the_spelled-out_intro_to_language_modeling_building_makemore_03.ipynb)
  
* Building makemore Part 3: Activations & Gradients, BatchNorm: \
  [building_makemore/the_spelled-out_intro_to_language_modeling_building_makemore_04.ipynb](https://github.com/popescualexandrucristian/andrej_karpathy_ai_trainining_2024/blob/master/building_makemore/the_spelled-out_intro_to_language_modeling_building_makemore_04.ipynb) \
  [building_makemore/the_spelled-out_intro_to_language_modeling_building_makemore_05.ipynb](https://github.com/popescualexandrucristian/andrej_karpathy_ai_trainining_2024/blob/master/building_makemore/the_spelled-out_intro_to_language_modeling_building_makemore_05.ipynb)

* Building makemore Part 4: Becoming a Backprop Ninja: \
	[building_makemore/the_spelled-out_intro_to_language_modeling_building_makemore_06.ipynb](https://github.com/popescualexandrucristian/andrej_karpathy_ai_trainining_2024/blob/master/building_makemore/the_spelled-out_intro_to_language_modeling_building_makemore_06.ipynb)

* Building makemore Part 5: Building a WaveNet : \
	[building_makemore/Building_makemore_Part_5_Building_a_WaveNet.ipynb](https://github.com/popescualexandrucristian/andrej_karpathy_ai_trainining_2024/blob/public/building_makemore/Building_makemore_Part_5_Building_a_WaveNet.ipynb)

* Let's build GPT: from scratch, in code, spelled out : \
[Let's%20build%20GPT%20from%20scratch%2C%20in%20code%2C%20spelled%20out.ipynb](https://github.com/popescualexandrucristian/andrej_karpathy_ai_trainining_2024/blob/public/gpt/Let's%20build%20GPT%20from%20scratch%2C%20in%20code%2C%20spelled%20out.ipynb) \
[bigram.py](https://github.com/popescualexandrucristian/andrej_karpathy_ai_trainining_2024/blob/public/gpt/bigram.py) \
[gpt.py](https://github.com/popescualexandrucristian/andrej_karpathy_ai_trainining_2024/blob/public/gpt/gpt.py)

* Let's reproduce GPT-2 (124M)(this is just a fork of Andrej's repo from when I went troug the exercices) \ 
[https://github.com/popescualexandrucristian/build-nanogpt](https://github.com/popescualexandrucristian/build-nanogpt) \
lecture: [https://youtu.be/l8pRSuU81PU?si=MnfD2_DoEfp6pauF](https://youtu.be/l8pRSuU81PU?si=MnfD2_DoEfp6pauF)

## Referenced papers
* MLP(2003) \
  [Yoshua Bengio Réjean, Ducharme DUCHARME, Pascal Vincent, Christian Jauvin](https://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf)
* Delving Deep into Rectifiers: Surpassing Human-Level Performance on ImageNet Classification(2015) \
  [Kaiming He,Xiangyu Zhang,Shaoqing Ren,Jian Sun](https://arxiv.org/abs/1502.01852)

* Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift \
  [Sergey Ioffe, Christian Szegedy](https://arxiv.org/abs/1502.03167)

* Pytorch Internals \
  [Edward Z. Yang](http://blog.ezyang.com/2019/05/pytorch-internals/)

* Bessel's Correction \
  [The department of mathematics and computer science Oxford](https://mathcenter.oxford.emory.edu/site/math117/besselCorrection/)

* Dropout: A Simple Way to Prevent Neural Networks from Overfitting \
  [Journal of Machine Learning Research 15 (2014) 1929-1958 Submitted 11/13; Published 6/14](https://www.cs.toronto.edu/~rsalakhu/papers/srivastava14a.pdf)

* The bigram model with cuda support \
  [https://github.com/karpathy/ng-video-lecture/blob/master/bigram.py](https://github.com/karpathy/ng-video-lecture/blob/master/bigram.py)

* The gpt model with cuda support \
  [https://github.com/karpathy/ng-video-lecture/blob/master/gpt.py](https://github.com/karpathy/ng-video-lecture/blob/master/gpt.py)

* Nano GPT \
  [https://github.com/karpathy/nanoGPT](https://github.com/karpathy/nanoGPT)

* Language Models are Unsupervised Multitask Learners \
[https://gwern.net/doc/ai/nn/transformer/gpt/2/2019-radford.pdf](https://gwern.net/doc/ai/nn/transformer/gpt/2/2019-radford.pdf)

* Automatic Mixed Precision \
  [https://pytorch.org/tutorials/recipes/recipes/amp_recipe.html](https://pytorch.org/tutorials/recipes/recipes/amp_recipe.html)

* Attention Is All You Need \
  [https://proceedings.neurips.cc/paper_files/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Paper.pdf](https://proceedings.neurips.cc/paper_files/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Paper.pdf)

* Language Models are Few-Shot Learners \
  [https://arxiv.org/abs/2005.14165](https://arxiv.org/abs/2005.14165)

* Using the Output Embedding to Improve Language Models \
  [https://arxiv.org/abs/1608.05859](https://arxiv.org/abs/1608.05859)
  
* build nanoGPT \
  [https://github.com/karpathy/build-nanogpt](https://github.com/karpathy/build-nanogpt)

* FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness \
  [https://arxiv.org/abs/2205.14135](https://arxiv.org/abs/2205.14135)

* FlashAttention-2: Faster Attention with Better Parallelism and Work Partitioning \
  [https://arxiv.org/pdf/2307.08691](https://arxiv.org/pdf/2307.08691)

* Online normalizer calculation for softmax \
  [https://arxiv.org/abs/1805.02867](https://arxiv.org/abs/1805.02867)

* karpathy/llm.c \
  [https://github.com/karpathy/llm.c](https://github.com/karpathy/llm.c)

## Enable cuda
  pip install torch===2.3.1+cu118 torchvision torchaudio -f https://download.pytorch.org/whl/torch_stable.html
