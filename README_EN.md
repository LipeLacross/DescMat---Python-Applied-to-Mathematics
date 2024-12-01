## 🌐 [Versão em Português do README](README.md)

# Dijkstra Visualization with Manim

This project implements the visualization of Dijkstra's algorithm to find the shortest path in a graph. Using Manim, the animation library, the code creates a visual representation of a graph, runs Dijkstra's algorithm, and displays the minimum distances of each node, as well as the shortest path to the destination.

## 🔨 Project Features

### Visual Example of the Project

The project creates an animation that illustrates the following steps of Dijkstra's algorithm:

1. **Initial Graph**: The graph is displayed with its nodes (represented as circles) and edges (lines connecting the nodes), where each edge has an associated weight.
2. **Initial Distances**: The initial minimum distances for each node are shown at the start of the execution.
3. **Algorithm Execution**: The animation shows the execution of Dijkstra's algorithm and the updating of the minimum distances for each node as the algorithm progresses.
4. **Shortest Path**: After the execution, the shortest path from the initial node to the final node is highlighted with smooth animations.
5. **Final Result**: A completion message is displayed, showing the shortest path found.

![Visual Example](https://github.com/user-attachments/assets/fd270753-9622-485a-9dd9-3255baec606b)

## ✔️ Techniques and Technologies Used

- **Manim**: Library for creating mathematical animations.
- **Python**: Programming language used for implementing the code.
- **Heapq**: Python library used to implement the priority queue in Dijkstra's algorithm.
- **Dijkstra's Algorithm**: Used to find the shortest path in a weighted graph.

## 📁 Project Structure

The project structure is as follows:

- **LICENSE**: Project license file.
- **README.md**: Documentation file for the project.
- **README_EN.md**: English version of the project documentation.
- **dijkstra_visualization.ipynb**: Jupyter Notebook containing the project code and visualizations of the algorithm.
- **requirements.txt**: File containing the necessary dependencies to run the project.

## 🛠️ Running the Project

To run the project locally, follow the steps below:

### 1. **Ensure Python and Manim are installed**:

- Both [Python](https://www.python.org/) and [Manim](https://docs.manim.community/en/stable/) are required to run the project. You can check if you already have Python installed with:

  ```bash
  python --version
  ```

If you don't have it, download and install Python.

- To install Manim, run the following command:

  ```bash
  pip install manim
  ```

### 2. **Clone the Repository**:
- Copy the repository URL and run the following command in the terminal:

  ```bash
  git clone <REPOSITORY_URL>
  ```

### 3. **Run the Project**:
- Navigate to the project directory and run the following command to generate the animation:

  ```bash
  manim -ql -v WARNING dijkstra_visualization.py DijkstraVisualization
  ```

  This will generate the animation in low quality (`-ql`). If you want a higher-quality animation, replace `-ql` with `-qm` or `-qh`.

## 🌐 Deploy

To deploy the animation, you can follow these steps:

1. **Generate the video file**: Make sure that Manim has generated the desired animation in `.mp4` format or another video format.

2. **Host the video**: You can host the video on platforms such as:
    - **YouTube**: Upload the generated video to YouTube and share the link.
    - **Vimeo**: Use Vimeo to host higher-quality videos.

3. **Share**: Share the generated video link or embed the animation in your website or project.
