
# Detecção de Veículos com IA

Este repositório contém o código-fonte e os recursos necessários para um projeto de detecção de veículos utilizando Inteligência Artificial. A detecção é realizada por meio da combinação de técnicas de Visão Computacional e Redes Neurais Convolucionais (CNN). Como o GitHub não permiti que carregue mais de 100 arquivos de uma vez e que o tamanho limite é de 15 TB, estarei deixando na secção de Referências o link do Dropbox com as imagens utilizadas para treinar a IA. 


<p align="center">
    <img src="https://i.imgur.com/5bSiK4U.png" alt="Logo do projeto - DETECCAR" />
</p>


## 🎥 Demonstração simples

<div align="center">
  <img     src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExaXJ3NHZ0eDJ0ZzlycHdncjVpMWd3YTdua3Vwd2IxdDAxenJtMXk4eCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/eRNVYSQj9UMYCow6ls/giphy.gif" />
</div>

## Stack utilizada

**Front-end:** Google Colab

**Back-end:** OpenCV, YOLO e Ultralytics


## Variáveis de Ambiente

Para rodar esse projeto, você vai precisar adicionar as seguintes variáveis de ambiente no seu Notebook Google Colab

```bash
# Às vezes Colab reclama por não conseguir ler caracteres especiais, por isso vamos localmente forçá-lo leio-o diretamente.
import locale
locale.getpreferredencoding = lambda: "UTF-8"
```

```bash
# Desativando os avisos no notebook para manter células de saída limpas
import warnings
warnings.filterwarnings('ignore')
```
## Instalação

Instalação necessária para rodar o código:

```bash
# Instalação da biblioteca Ultralytics
!pip install ultralytics
```


```bash
# Importação das bibliotecas necessárias
import os
import shutil
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import cv2
import yaml
from PIL import Image
from ultralytics import YOLO
from IPython.display import Videos
```
    
## Funcionalidades

- Detecção de veículos
- Detecção de veículos em tempo-real


## Aprendizados

O projeto Semáforo Inteligente foi um grande desafio e uma grande fonte de estímulo para o aprendizado e reflexão, empregando grande parte dos conhecimentos adquiridos ao longo do curso de Tecnologia em Análise e Desenvolvimento de Sistemas.


## Melhorias para Trabalhos  Futuros

Em perspectiva futuras atualizações do software, manifesta-se a possibilidade em ampliar a capacidade do sistema para detectar não somente veículos, mas também de pedestres. Planeja-se também a implementação do método para o controle da via. Outro ponto relevante para evolução é a introdução de câmeras inteligentes e sensores no sistema, visando o aprimoramento do software para poder ser utilizando em situação real de controle de tráfego de veículos e pedestres. As incorporações tecnológicas proporcionarão uma perspectiva mais ampla e aprofundada do ambiente, permitindo ajustes dinâmicos e eficientes nas condições do tráfego de veículos.


## Referências
Nesta seção, você encontrará a fonte dos dados como os códigos e bibliotecas que foram utilizados neste projeto. 

### Bibliotecas Utilizadas
 - [OpenCV](https://github.com/opencv/opencv)
 - [YOLO](https://github.com/AlexeyAB/darknet)
 - [Ultralytics](https://github.com/ultralytics/ultralytics)

### Trabalhos Correlatos
Esta subseção apresenta alguns trabalhos que foram utilizados como referência para o desenvolvimento deste trabalho. Estes trabalhos contribuíram para a escolha de alguns conceitos, tecnologias ou técnicas, que foram utilizados neste trabalho.

- [An intelligent control system for traffic lights with simulation-based evaluation](https://www.sciencedirect.com/science/article/abs/pii/S096706611630212X)

 - [Internet of smart-cameras for traffic lights optimization in smart cities](https://www.sciencedirect.com/science/article/pii/S2542660520300433)

### Fonte dos Dados e Código Utilizado
 - [Real-Time Traffic Density Estimation with YOLOv8](https://www.kaggle.com/code/farzadnekouei/real-time-traffic-density-estimation-with-yolov8)

Este conjunto de dados e código foram fundamentais para o desenvolvimento e treinamento do modelo de detecção de veículos neste projeto.

### Arquivo Completo do Código-Fonte & Imagens utilizadas
- [DropBox](https://www.dropbox.com/scl/fi/ykmx853vfkx6bf6ezph3r/DETECCAR.zip?rlkey=i521eryq319cwczij6fylwn3c&dl=0)

## Licença

[MIT](https://choosealicense.com/licenses/mit/)


## Autores

- [@pedrofratassi](https://github.com/pedrofratassi)

