## 🌐 [English Version of README](README_EN.md)

# Dijkstra Visualization with Manim

Este projeto implementa a visualização do algoritmo de Dijkstra para encontrar o caminho mais curto em um grafo. Usando o Manim, a biblioteca de animação, o código cria uma representação visual de um grafo, executa o algoritmo de Dijkstra, resolve sistemas de equações lineares relacionados a fluxos no grafo e exibe os resultados.

## 🔨 Funcionalidades do Projeto

### Exemplo Visual do Projeto
![download](https://github.com/user-attachments/assets/dcafb93b-a889-47b6-9233-a0487f630ab7)

O projeto cria uma animação que ilustra as seguintes etapas:

1. **Grafo Inicial**: O grafo é exibido com seus nós (representados por círculos) e as arestas (linhas conectando os nós), onde cada aresta tem um peso associado.
2. **Distâncias Iniciais**: As distâncias mínimas para cada nó são exibidas no início da execução do algoritmo.
3. **Execução do Algoritmo**: A animação mostra a execução passo a passo do algoritmo de Dijkstra e a atualização das distâncias mínimas para cada nó à medida que o algoritmo avança.
4. **Caminho Mais Curto**: Após a execução, o caminho mais curto do nó inicial até o nó final é destacado com animações suaves.
5. **Solução de Fluxos no Grafo**: O sistema de equações lineares baseado nos fluxos nas arestas é resolvido, e os resultados são apresentados graficamente.
6. **Resultado Final**: Uma mensagem de conclusão é exibida, mostrando o caminho mais curto e a solução do sistema linear.

## ✔️ Técnicas e Tecnologias Utilizadas

- **Manim**: Biblioteca para criação de animações matemáticas.
- **Python**: Linguagem de programação utilizada para a implementação do código.
- **Heapq**: Biblioteca do Python utilizada para implementar a fila de prioridade no algoritmo de Dijkstra.
- **NumPy**: Usado para manipulação da matriz de adjacência do grafo.
- **SymPy**: Utilizado para resolver sistemas de equações lineares relacionados aos fluxos no grafo.
- **Algoritmo de Dijkstra**: Usado para encontrar o caminho mais curto em um grafo ponderado.

## 📁 Estrutura do Projeto

A estrutura do projeto é a seguinte:

- **LICENSE**: Arquivo de licença do projeto.
- **README.md**: Arquivo com a documentação do projeto.
- **README_EN.md**: Versão em inglês do arquivo de documentação.
- **dijkstra_visualization.ipynb**: Jupyter Notebook contendo o código do projeto e visualizações do algoritmo.
- **requirements.txt**: Arquivo contendo as dependências necessárias para rodar o projeto.

## 🛠️ Abrir e Rodar o Projeto

Para iniciar o projeto localmente, siga os passos abaixo:

### 1. **Certifique-se de que o Python e o Manim estão instalados**:

- O [Python](https://www.python.org/) e o [Manim](https://docs.manim.community/en/stable/) são necessários para rodar o projeto. Você pode verificar se já tem o Python instalado com:
  
  ```bash
  python --version
  ```

  Se não tiver, baixe e instale o Python.

- Para instalar o Manim e outras dependências necessárias, execute os comandos abaixo:

  ```bash
  sudo apt update
  sudo apt install libcairo2-dev ffmpeg \
      texlive texlive-latex-extra texlive-fonts-extra \
      texlive-latex-recommended texlive-science \
      tipa libpango1.0-dev
  pip install manim
  pip install IPython==8.21.0
  pip install numpy
  pip install sympy
  ```

### 2. **Clone o Repositório**:
- Copie a URL do repositório e execute o comando abaixo no terminal:

  ```bash
  git clone <URL_DO_REPOSITORIO>
  ```

### 3. **Instale as Dependências**:
- Certifique-se de estar no diretório raiz do projeto e instale as dependências com:

  ```bash
  pip install -r requirements.txt
  ```

### 4. **Rodar o Projeto**:
- Navegue até o diretório do projeto e execute o seguinte comando para gerar a animação:

  ```bash
  manim -ql -v WARNING dijkstra_visualization.py DijkstraVisualization
  ```

  Isso irá gerar a animação em qualidade baixa (`-ql`). Se quiser uma animação de maior qualidade, substitua `-ql` por `-qm` ou `-qh`.

## 🌐 Deploy

Para fazer o deploy da animação, você pode seguir os seguintes passos:

1. **Gerar o arquivo de vídeo**:
   - Certifique-se de que o Manim gerou a animação desejada em formato `.mp4` ou outro formato de vídeo.

2. **Hospedar o vídeo**:
   - Você pode hospedar o vídeo em plataformas como:
     - **YouTube**: Carregar o vídeo gerado no YouTube e compartilhar o link.
     - **Vimeo**: Usar o Vimeo para hospedar vídeos de maior qualidade.

3. **Compartilhar**:
   - Compartilhe o link do vídeo gerado ou incorpore a animação em seu site ou projeto.

