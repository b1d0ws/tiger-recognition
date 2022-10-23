# tiger-recognition

<br/>

Projeto criado para...

Link Download Negativas - A pasta utilizada foi a mesma contida no OneDrive das aulas.

Link Download Positivas - https://images.cv/dataset/tiger-image-classification-dataset

<br/>

Último estágio do treinamento

![finalStage](https://user-images.githubusercontent.com/58514930/197423619-c510c602-8459-4d9b-a13c-0426f940913b.png)

Resultado do treinamento

![resultado1](https://user-images.githubusercontent.com/58514930/197424056-d0d3f971-6d35-47e9-8cef-6d3cb05d35d3.png)
![resultado2](https://user-images.githubusercontent.com/58514930/197424059-d0a5021d-f7b7-4d9e-ae0c-f4c7c26ca594.png)

Dentro da pasta testes existem 5 imagens testadas, porém, faz-se necessário a alteração do grayScale para melhor resultado em cada imagem.

teste.jpg - Pega bem com 1.2 e 1.5

teste2.jpg - Pega bem com 1.2

teste3.jpg - Pega bem com 1.25

teste4.jpg - Pega bem com 1.26

teste5.jpg - Pega bem com 1.09

<br/>

### Descrição dos diretórios e arquivos:

#### Diretório negatives
Contém as imagens negativas.

#### Diretório testes
Contém 5 imagens que foram devidamente testadas.

#### Diretório tigres
Contém as imagens usadas para treinar o algoritmo dentro do diretório *train* e imagens que podem ser usadas para testes dentro do diretório *test*.

#### Diretório treinamento
Contém os xml gerados pelo treinamento da IA.

#### Arquivo criaListaNegatives.py
Gera um arquivo para listar as imagens negativas

#### Arquivo negatives.txt
Contém a listagem das imagens negativas geradas pelo criaListaNegatives.py

#### Arquivo saida.txt
Contém o resultado do reconhecimento manual feito nos tigres

#### Arquivo testeFinal.py
Utilizado para usar uma imagem como teste da IA.

#### Arquivo vec.vec
Arquivo de vetor gerado para utilizar no treinamento da IA.
