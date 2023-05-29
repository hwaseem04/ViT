# ViT
Reimplementation always fills the gaps for better understanding.

## Implementation
Replicated from [Phil Wang's repository](https://github.com/lucidrains/vit-pytorch#faq). But my [code](main.ipynb) is highly commented, so anyone reading the code can understand whats happening at each line.

I believe this will help in understanding the ViT paper much better.

The code implementation is based on the following two paper:
1. [An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale](https://arxiv.org/abs/2010.11929)
2. [Better plain ViT baselines for ImageNet-1k](https://arxiv.org/abs/2205.01580)

## Resources
I would suggest going through the following resources in order for better comprehension of the code.

1. [The Illustrated Transformer - Jay Alammar](https://jalammar.github.io/illustrated-transformer/)
2. [An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale](https://arxiv.org/abs/2010.11929)
3. [Better plain ViT baselines for ImageNet-1k](https://arxiv.org/abs/2205.01580)
4. [Einops](https://einops.rocks/)
5. Then the implementation [here](main.ipynb)

## ToDo (plans)
1. Calculation of Attention weights at each layer
2. Comparing layers of CNN(ResNets) and a Strong ViT based on Centered Kernel Alignment (CKA) - refer FlexiViT
3. Visualisation of attention maps

>Caveat: I dont have pretrained weights for Phil Wang's implementation of ViT (which is what I have replicated here). My system will die, if I train it from scratch :)  So I am planning to use hugging face's vision [repository](https://github.com/huggingface/pytorch-image-models)
