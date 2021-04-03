# Beautiful Results with Neural Style Transfer

- <https://towardsdatascience.com/how-to-get-beautiful-results-with-neural-style-transfer-75d0c05d6489>
- [Assiciated repo](https://github.com/EugenHotaj/pytorch-generative)

- [Google Collab](https://colab.research.google.com/)

## Operate

Just open <https://colab.research.google.com/github/EugenHotaj/pytorch-generative/blob/master/notebooks/style_transfer.ipynb>

## Below: attempts to recreate 2020-04-03 version

- Cleanup notebook code to have this self contained
  - Notebook point to it's own repo (which has change or evolved)

I also copied the repo as used originally on 2020-04-03 into `notebooks-2020-04-03/`

Just open <https://colab.research.google.com/github/daneroo/style-transfer/blob/main/notebooks-2020-04-03/style_transfer.ipynb>

And replace the first block with

```bash
!pip install kornia
!rm -rf nn_hallucinations style-transfer
!git clone https://github.com/daneroo/style-transfer 
!mv 'style-transfer/notebooks-2020-04-03' nn_hallucinations
!ls
```

![Example Result](./results/dali-dan-pub-result.png  "Example Result")
