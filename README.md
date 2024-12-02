# Projeto de Redução de Dimensionalidade em Imagens para Redes Neurais

Este projeto tem como objetivo demonstrar a transformação de imagens coloridas em escala de cinza e binarização, sem o uso de bibliotecas externas como OpenCV ou PIL. O código foi implementado em Python e está estruturado em um notebook Jupyter no Google Colab.

## 🚀 Teste no Google Colab

Para testar o código diretamente no Google Colab, clique no link abaixo:

[Abra o notebook no Google Colab](https://colab.research.google.com/github/eunafita/reducao-dimensionalidade-imagens/blob/main/notebooks/reducao_dimensionalidade_imagens.ipynb)

## Descrição

O projeto realiza as seguintes etapas de processamento de imagem:

1. **Conversão para Escala de Cinza**:
   - A imagem colorida é convertida para escala de cinza utilizando uma fórmula baseada em médias ponderadas para simular a percepção humana das cores. 
   - A fórmula usada é: `0.2989 * R + 0.5870 * G + 0.1140 * B`.

2. **Binarização**:
   - Após a conversão para escala de cinza, a imagem é binarizada com um limiar (127 por padrão), onde os pixels com valores acima do limiar são convertidos para 255 (branco) e os pixels abaixo para 0 (preto).

## Como Executar

1. Faça o download ou clone o repositório para o seu ambiente local.
   
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
   
## Instale as dependências do projeto:

```bash
Copiar código
pip install -r requirements.txt
```
Abra o notebook reducao_dimensionalidade_imagens.ipynb em um ambiente Jupyter ou no Google Colab.

Execute as células do notebook para ver a transformação das imagens coloridas para escala de cinza e binarização.

## Estrutura do Projeto

```bash
Copiar código
/images                # Imagens usadas no projeto
    /aisha.jpg         # Exemplo de imagem 1
    /cachorro_coelho.jpg  # Exemplo de imagem 2
    /lena.jpg          # Exemplo de imagem 3
/notebooks             # Jupyter Notebooks contendo o código
    /reduca_dimensionalidade_imagens.ipynb  # Notebook principal
.gitattributes         # Arquivo para atributos do Git
requirements.txt       # Dependências necessárias para o projeto
```
## Dependências

# O projeto depende das seguintes bibliotecas:

numpy: Para manipulação de arrays numéricos.
matplotlib: Para visualização das imagens antes e depois do processamento.
imageio: Para leitura de arquivos de imagem.
Você pode instalar as dependências usando o arquivo requirements.txt:

```bash
Copiar código
pip install -r requirements.txt
```

## Contribuição

Se você deseja contribuir para este projeto, fique à vontade para fazer um fork, criar uma branch e enviar um pull request.

## ⭐️ Se gostou, dê uma estrela!

Se você achou o projeto útil ou interessante, não esqueça de dar uma estrela no repositório! Isso ajuda outros usuários a encontrar o projeto e motiva a equipe a continuar melhorando. 

Obrigado por conferir o projeto!
