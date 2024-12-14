# Dijkstra Visualization with Manim

This project implements a visualization of Dijkstra's algorithm to find the shortest path in a graph. Using Manim, the animation library, the code creates a visual representation of a graph, executes Dijkstra's algorithm, solves systems of linear equations related to flows in the graph, and displays the results.

## 🔨 Project Features

### Visual Example of the Project
![download](https://github.com/user-attachments/assets/dcafb93b-a889-47b6-9233-a0487f630ab7)

The project creates an animation illustrating the following steps:

1. **Initial Graph**: The graph is displayed with its nodes (represented by circles) and edges (lines connecting the nodes), where each edge has an associated weight.
2. **Initial Distances**: The minimum distances for each node are displayed at the start of the algorithm execution.
3. **Algorithm Execution**: The animation shows the step-by-step execution of Dijkstra's algorithm and the updating of minimum distances for each node as the algorithm progresses.
4. **Shortest Path**: After execution, the shortest path from the starting node to the destination node is highlighted with smooth animations.
5. **Flow Solution in the Graph**: The system of linear equations based on the flows on the edges is solved, and the results are graphically presented.
6. **Final Result**: A conclusion message is displayed, showing the shortest path and the solution to the linear system.

## ✔️ Techniques and Technologies Used

- **Manim**: Library for creating mathematical animations.
- **Python**: Programming language used for implementing the code.
- **Heapq**: Python library used to implement the priority queue in Dijkstra's algorithm.
- **NumPy**: Used for handling the graph's adjacency matrix.
- **SymPy**: Used for solving systems of linear equations related to graph flows.
- **Dijkstra's Algorithm**: Used to find the shortest path in a weighted graph.

## 📁 Project Structure

The project structure is as follows:

- **LICENSE**: License file for the project.
- **README.md**: Project documentation file.
- **README_EN.md**: English version of the documentation file.
- **dijkstra_visualization.ipynb**: Jupyter Notebook containing the project code and algorithm visualizations.
- **requirements.txt**: File containing the necessary dependencies to run the project.

## 🛠️ Setting Up and Running the Project

To set up and run the project locally, follow these steps:

### 1. **Ensure Python and Manim are Installed**:

- [Python](https://www.python.org/) and [Manim](https://docs.manim.community/en/stable/) are required to run the project. You can check if Python is installed with:

  ```bash
  python --version
  ```

  If not installed, download and install Python.

- To install Manim and other required dependencies, run the following commands:

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

### 2. **Clone the Repository**:
- Copy the repository URL and run the following command in the terminal:

  ```bash
  git clone <REPOSITORY_URL>
  ```

### 3. **Install Dependencies**:
- Make sure you are in the project's root directory and install the dependencies with:

  ```bash
  pip install -r requirements.txt
  ```

### 4. **Run the Project**:
- Navigate to the project directory and run the following command to generate the animation:

  ```bash
  manim -ql -v WARNING dijkstra_visualization.py DijkstraVisualization
  ```

  This will generate the animation in low quality (`-ql`). For higher quality, replace `-ql` with `-qm` or `-qh`.

## 🌐 Deployment

To deploy the animation, you can follow these steps:

1. **Generate the Video File**:
   - Ensure Manim has generated the desired animation in `.mp4` or another video format.

2. **Host the Video**:
   - You can host the video on platforms such as:
     - **YouTube**: Upload the generated video to YouTube and share the link.
     - **Vimeo**: Use Vimeo to host high-quality videos.

3. **Share**:
   - Share the generated video's link or embed the animation in your website or project.

