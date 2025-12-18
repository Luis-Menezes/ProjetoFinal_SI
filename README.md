# Ataques Adversariais: Explorando a Vulnerabilidade de Modelos de IA na Classificação de Imagens

Este repositório consiste no projeto final da disciplina de Segurança da Informação, ministrada pelo professor Dr. Fabio Augusto Menocci Cappabianco na Universidade Federal de São Paulo (UNIFESP). 

## Alunos:

- Arthur Moreira Craveiro - RA: 163597
- Isabella Mariana Cardoso Pinto - RA: 164915
- Luis Filipe Carvalho de Menezes - RA: 164924

## Arquitetura do Projeto:

O objetivo principal é demonstrar como redes neurais modernas (Deep Learning) são vulneráveis a **Ataques Adversariais**. O projeto utiliza método matemático para gerar ruídos imperceptíveis em imagens, confundindo um classificador pré-treinado. O cenário explorado é a distinção entre **Imagens Reais vs. Imagens Geradas por IA**. Portanto, consiste em enganar um modelo de IA para que ele classifique uma imagem falsa (IA) como verdadeira (Real) e vice-versa.

## Ferramentas Utilizadas:

- Linguagem: Python
- Frameworks: [PyTorch](https://pytorch.org/), [Hugging Face Transformers](https://huggingface.co/)
- Dataset: [Kaggle - AI vs Real Images](https://www.kaggle.com/datasets/cashbowman/ai-generated-images-vs-real-images)
- Modelo Alvo: `umm-maybe/AI-image-detector`
- Ambiente: Google Colab / Jupyter Notebook (Suporte a GPU/CUDA)
