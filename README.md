## 🌐 [English Version of README](README_EN.md)

# Dijkstra Visualization with Manim

Este projeto implementa a visualização do algoritmo de Dijkstra para encontrar o caminho mais curto em um grafo. Além disso, integra conceitos de álgebra linear para modelar fluxos no grafo. Usando o Manim, a biblioteca de animação, o código cria uma representação visual interativa do grafo, executa o algoritmo de Dijkstra e resolve um sistema de equações relacionado aos fluxos nas arestas.

## 🔧 Funcionalidades do Projeto

### Exemplo Visual do Projeto

O projeto cria uma animação que ilustra as seguintes etapas:

1. **Grafo Inicial**:
   - Exibição dos nós do grafo (representados por círculos) e suas arestas (linhas conectando os nós).
   - Cada aresta possui um peso associado que representa o custo de conexão.

2. **Execução do Algoritmo de Dijkstra**:
   - Cálculo do caminho mais curto entre um nó de origem e um nó de destino.
   - Destaque das atualizações de distâncias mínimas e dos nós processados durante a execução.

3. **Caminho Mais Curto**:
   - Após a execução do algoritmo, o caminho mais curto encontrado é destacado no grafo com cores diferenciadas.

4. **Álgebra Linear no Grafo**:
   - Modelagem de fluxos nas arestas como um sistema de equações lineares.
   - Resolução do sistema usando SymPy para determinar os valores dos fluxos que satisfazem as condições do grafo.

5. **Resultado Final**:
   - Apresentação do caminho mais curto e exibição dos fluxos resolvidos nas arestas.

![Exemplo Visual](https://github.com/user-attachments/assets/dcafb93b-a889-47b6-9233-a0487f630ab7)

## ✔️ Técnicas e Tecnologias Utilizadas

- **Manim**: Biblioteca para criação de animações matemáticas interativas.
- **Python**: Linguagem de programação utilizada para a implementação do código.
- **NumPy**: Manipulação da matriz de adjacência do grafo.
- **Heapq**: Implementação eficiente de fila de prioridade para o algoritmo de Dijkstra.
- **SymPy**: Resolução do sistema de equações lineares relacionado aos fluxos.

## 📁 Estrutura do Projeto

- **LICENSE**: Arquivo de licença do projeto.
- **README.md**: Arquivo com a documentação principal do projeto.
- **README_EN.md**: Versão em inglês do arquivo de documentação.
- **dijkstra_visualization.ipynb**: Jupyter Notebook contendo o código do projeto e visualizações.
- **requirements.txt**: Arquivo com as dependências necessárias para rodar o projeto.

## 🛠️ Como Rodar o Projeto

Para iniciar o projeto localmente, siga os passos abaixo:

### 1. **Instale o Python e o Manim**:

- Verifique se o [Python](https://www.python.org/) está instalado:

  ```bash
  python --version
  ```

- Caso não esteja instalado, baixe e instale o Python.

- Instale o [Manim](https://docs.manim.community/en/stable/) com o seguinte comando:

  ```bash
  pip install manim
  ```

### 2. **Clone o Repositório**:

- Copie a URL do repositório e execute o comando abaixo no terminal:

  ```bash
  git clone <URL_DO_REPOSITORIO>
  ```

### 3. **Execute o Código**:

- Navegue até o diretório do projeto e execute o seguinte comando para gerar a animação:

  ```bash
  manim -ql -v WARNING dijkstra_visualization.py DijkstraVisualization
  ```

- Para maior qualidade na animação, substitua `-ql` por `-qh` para alta qualidade.

## 🌐 Deploy

Para compartilhar ou hospedar o vídeo gerado pela animação:

1. **Gere o arquivo de vídeo**:
   - Certifique-se de que o Manim criou a animação no formato `.mp4`.

2. **Hospede o vídeo**:
   - **YouTube**: Carregue o vídeo no YouTube para ampla distribuição.
   - **Vimeo**: Use o Vimeo para hospedar vídeos de maior qualidade.

3. **Compartilhe**:
   - Compartilhe o link do vídeo gerado ou incorpore a animação em sites ou projetos pessoais.

