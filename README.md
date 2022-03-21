# Conteúdo:

### 1. Introdução NLP

# PASTA: REDES NEURAIS

### Redes Neurais com PyTorch

* 1: 

> Tensores como estrutura de dados.

> Manipulação de tensores no Pytorch.

> Colocando tensores na GPU.

* 2:

> Modelos lineares.

>Retas como classificadores lineares.

* 3:

> Perceptron como classificador linear.

> Camada Linear do PyTorch para criar um Perceptron.

* 4:

> Papel da função de ativação no perceptron.

> Funções limiar, sigmoide, Tanh e ReLU.

> Funções de ativação no PyTorch.

* 5:

> Problemas multi-classe.

> Multi-Layer Perceptron (MLP).

> Implementando uma arquitetura com nn.Sequential.

> Implementando uma arquitetura com nn.Module.

* 6:

> Funções de perda para regressão.

> Funções de perda para classificação.

* 7:

> Otimização de problemas com PyTorch

* 8:

> Carregamento de dados

* 9:

> Carregamento de dados

> Utilizando nossos próprios dados

* 10: CNN

> Datasets do torchvision e primeiros conceitos de cnn

* 11:

> Convolução 1D

* 12:

> Convolução 2D

* 13:

> Exemplos de filtros manualmente projetados

> Casamento de padrões complexos

* 14:

> Parâmetros da Convolução

> Controle de resolução da informação

> Construindo uma Conv2d

* 15:

> Pooling: Enumeramos em aula algumas vantagens da subamostragem em redes convolucionais. Em termos de custo computacional, reduzir a dimensionalidade espacial dos mapas de ativação permite uma grande economia de processamento. Por si só essa já é uma vantagem bastante convincente para usar o pooling, pois imagens são dados de altíssima dimensionalidade.

Um dos principais livros de Deep Learning [1] define o Pooling como um "resumo estatístico" das saídas de uma convolução. Isso porque a camada não realiza uma subamostragem aleatória dos mapas de ativação, mas destaca as características mais relevantes de cada vizinhança local (definida pelo campo de visão do pooling).

Um importante efeito disso é que o Pooling torna a representação aproximadamente invariante a pequenas translações. Em termos claros, se a imagem de entrada for levemente deslocada no espaço, uma boa parte do mapa de características resultante do pooling não será alterado. 

* 16:

> Camada de Batch Normalization: Normaliza a saída da camada convolucional (antes da ativação linear)

> Implementação de um bloco convolucional em PyTorch

* 17:

> Treinando uma cnn do zero

* 18:

> Fine-tuning

# Pasta KERAS:

* 1: 

> Criação de camadas no Keras;

> Pesos e viés;

> Otimização da rede;

> Transformação inversa dos dados escalonados.

> Estrutura de dados para previsão;

> Previsão de próximo com um único valor ponto;

> Previsão de próximo ponto com diversos valores.

> Conversão no formato de data;

> O que são redes recorrentes;

> Forma de entrada das redes recorrentes;

> Redes do tipo Long Short Term memory;

> Aplicação da LSTM.

> Otimizador RMSProp;

> Aplicação da LSTM;

> O que é uma Unidade recorrente fechada (GRU);

> Overfitting.

