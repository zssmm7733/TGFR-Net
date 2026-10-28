# TGFR-Net

Repository for **A Reliable Task-Guided Feature Refinement Network for Few-Shot Fine-Grained Image Classification (TGFR-Net)**.

## Model weights

[Browse all eight checkpoints in the model weights release](https://github.com/zssmm7733/TGFR-Net/releases/tag/weights-v1.0).

Eight checkpoints for the main experiments: two backbones (ResNet12 and Conv4), with one checkpoint per backbone for each of four datasets.

Choose the checkpoint matching your backbone and dataset. The CUB checkpoints use the cropped CUB-200-2011 setting.

### TGFRNet-ResNet12 - ResNet12 backbone

| Dataset | Checkpoint download | Size |
| --- | --- | --- |
| CUB-200-2011 (cropped) | [model_ResNet-12.CUB_cropped.pth](https://github.com/zssmm7733/TGFR-Net/releases/download/weights-v1.0/model_ResNet-12.CUB_cropped.pth) | 121.21 MiB |
| Stanford Dogs | [model_ResNet-12.Dogs.pth](https://github.com/zssmm7733/TGFR-Net/releases/download/weights-v1.0/model_ResNet-12.Dogs.pth) | 121.21 MiB |
| Stanford Cars | [model_ResNet-12.Cars.pth](https://github.com/zssmm7733/TGFR-Net/releases/download/weights-v1.0/model_ResNet-12.Cars.pth) | 121.21 MiB |
| FGVC-Aircraft | [model_ResNet-12.Air.pth](https://github.com/zssmm7733/TGFR-Net/releases/download/weights-v1.0/model_ResNet-12.Air.pth) | 121.21 MiB |

### TGFRNet-Conv4 - Conv4 backbone

| Dataset | Checkpoint download | Size |
| --- | --- | --- |
| CUB-200-2011 (cropped) | [model_Conv-4.CUB_croped.pth](https://github.com/zssmm7733/TGFR-Net/releases/download/weights-v1.0/model_Conv-4.CUB_croped.pth) | 40.83 MiB |
| Stanford Dogs | [model_Conv-4.Dogs.pth](https://github.com/zssmm7733/TGFR-Net/releases/download/weights-v1.0/model_Conv-4.Dogs.pth) | 40.83 MiB |
| Stanford Cars | [model_Conv-4.Cars.pth](https://github.com/zssmm7733/TGFR-Net/releases/download/weights-v1.0/model_Conv-4.Cars.pth) | 40.83 MiB |
| FGVC-Aircraft | [model_Conv-4.Air.pth](https://github.com/zssmm7733/TGFR-Net/releases/download/weights-v1.0/model_Conv-4.Air.pth) | 40.83 MiB |

### File naming

The two groups above correspond to the local folders `TGFRNet-ResNet12/` and `TGFRNet-Conv4/`. GitHub Release attachments use a flat file list; the backbone and dataset are included in every filename. GitHub normalizes parentheses in uploaded filenames to periods. The Conv4 filename retains the original spelling `CUB_croped`; it denotes the cropped CUB-200-2011 dataset.

<details>
<summary>SHA-256 checksums</summary>

```text
67faece8238c8e68abf01a2c86caba0d4be387375c68d0119a831a1e2d2be45c  model_ResNet-12.CUB_cropped.pth
81222fe963e3d6e0d14a7462fb81184f16450dfc66680fdc48cbd62619da7d97  model_ResNet-12.Dogs.pth
2a9081a55093be6a67e442eb5769f391a9f4e6b66974c4f8722041dcd28744c9  model_ResNet-12.Cars.pth
741a1cbea9180ae3625ff8a37866906f7c6febd7802c16ef40eeed44757d4824  model_ResNet-12.Air.pth
d3a37a6274dfcb05cd4c71c3a5d5ede30873016dc0e59ef86e363ce4d6a39308  model_Conv-4.CUB_croped.pth
2f96171eebcd651c9721a4591e90b3a154657432fb2f5647ff88d03f4d294d4c  model_Conv-4.Dogs.pth
e68b1543875651cdab4ba642d89cbda3fae57ee9a18e166f193f2a091a2c21fe  model_Conv-4.Cars.pth
e6244badedd8c93809513980d260c0f128bfb0a783a3be373507be171809075b  model_Conv-4.Air.pth
```

</details>
