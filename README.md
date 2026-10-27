# Deep Networks 2026/2027

Zadania z przedmiotu Deep Learning. Każdy projekt jest w osobnym katalogu i zaimplementowany w PyTorch.

## Zadania

1. **[Highway Network na CIFAR-10](highway-cifar10/)**  
   Zaimplementować sieć Highway Network i wytrenować ją na zbiorze CIFAR-10.  
   Artykuł: [Highway Networks](https://arxiv.org/pdf/1505.00387)

2. **ResNet-56 na CIFAR-10**  
   Zaimplementować sieć ResNet-56 i wytrenować ją na zbiorze CIFAR-10.  
   Artykuł: [Deep Residual Learning for Image Recognition](https://arxiv.org/abs/1512.03385)

3. **GPT-2 na Tiny Shakespeare**  
   Zaimplementować kompletny system GPT-2 (trening oraz inferencję autoregresyjną) w dwóch wariantach warstwy uwagi: własna implementacja multi-head attention oraz wbudowana uwaga z PyTorch. Porównać czas treningu i jakość działania. Zbiór danych: Tiny Shakespeare.  
   Artykuł: [Attention Is All You Need](https://arxiv.org/abs/1706.03762)

4. **Stable Diffusion**  
   Zaimplementować i wytrenować Stable Diffusion, korzystając z gotowych, wstępnie wytrenowanych komponentów:
   - VAE: `stabilityai/sd-vae-ft-mse`
   - enkoder tekstu CLIP: `openai/clip-vit-large-patch14`  
   Zbiór danych: `AlekseyKorshuk/celeba-hq-blip`  
   Artykuł: [High-Resolution Image Synthesis with Latent Diffusion Models](https://arxiv.org/pdf/2112.10752)
