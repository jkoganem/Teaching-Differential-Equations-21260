# 21-260 Differential Equations

Welcome to the **21-260 Differential Equations** repository. This is a collection of lecture notes, example code, and other resources for students enrolled in 21-260 Differential Equations at Carnegie Mellon University (or for anyone interested in learning about differential equations).

For students enrolled in the course, please access additional resources (such as Gradescope for homework submissions and Piazza for Q&A) through [Canvas](https://canvas.cmu.edu/courses/45779).

## Author

**Junichi Koganemaru** ([@jkoganem](https://github.com/jkoganem))  
Email: [jkoganem@andrew.cmu.edu](mailto:jkoganem@andrew.cmu.edu)  

> **Note for students:** Please include the header “21-260” in the subject line of your email when you email me; otherwise, your email may not be noticed promptly.

## Table of Contents
1. [About the Course](#about-the-course)  
2. [Repo Structure](#repo-structure)  
3. [How to Use These Materials](#how-to-use-these-materials)  
4. [Installation & Setup](#installation--setup)  
5. [License](#license)  
6. [Contact](#contact)  

---

## 1. About the Course

**21-260 Differential Equations** explores the theory, methods, and applications of ordinary and partial differential equations. The key topics we cover include:

- First-order ODEs 
- Second and higher-order linear ODEs 
- Systems of differential equations, stability analysis
- Laplace transforms and their applications  
- Numerical methods  
- Linear partial differential equations (Laplace, heat, wave)

The course aims to provide a solid theoretical foundation while highlighting practical problem-solving strategies.

---

## 2. Repo Structure

- **code/**: Folder containing scripts demonstrating concepts and numerical methods.  
- **notes/**: Folder for lecture notes.  
- **homework/**: Folder for homework problems and solutions.

---

## 3. How to Use These Materials

1. **Lecture and Recitation Notes**  
   - Download and review the notes before or after lectures/recitations to solidify your understanding.

2. **Code Examples**  
   - Code (`.ipynb` files) demonstrating numerical methods is hosted in [`code/`](code/).  
   - These notebooks illustrate how to approximate solutions to ODEs and PDEs numerically.

---

## 4. Installation & Setup

> **Note:** If you just want to read `.pdf` files, you can simply download or open them directly in your browser (e.g., GitHub’s PDF viewer or your preferred PDF reader). 

### 4.1 Git: Cloning the Repository

1. **Git (Command Line)**  
   - Make sure you have Git installed.  
   - In your terminal, navigate to the folder where you want to clone the course repository, then run:
     ```bash
     git clone https://github.com/YourUsername/YourRepoName.git
     cd YourRepoName
     ```
2. **GitHub Desktop (GUI Option)**  
   - [Download GitHub Desktop](https://desktop.github.com/) (available for Windows and macOS).  
   - Open GitHub Desktop and sign in with your GitHub account.  
   - Click **File** > **Clone repository**, select your repository, and choose a local path to clone into.

### 4.2 Local Environment (VS Code + Anaconda + Jupyter)

1. **Install VS Code**  
   - [Download Visual Studio Code](https://code.visualstudio.com/download) (available for Windows, macOS, and Linux).  
   - Install the **Python** extension in VS Code for syntax highlighting, linting, and Jupyter notebook support.

2. **Install Anaconda/Miniconda**  
   - [Download Anaconda](https://www.anaconda.com/products/individual) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html).  
   - This provides `conda`, a powerful tool for creating and managing Python environments.

3. **Create a Conda Environment**  
   - Open a terminal (or Anaconda Prompt if on Windows) and navigate to the cloned repo.
   - Use the provided `environment.yml` file to create a new virtual environment:
     ```bash
     conda env create -f environment.yml
     conda activate my-env-name 
     ```

4. **Open Jupyter Notebooks in VS Code**  
   - Launch VS Code and open your cloned repository folder.  
   - Open a `.ipynb` file.  
   - VS Code’s Jupyter extension will automatically detect your conda environment; you can choose it from the top-right kernel selection menu.  
   - Run code cells interactively within VS Code.

---

### 4.3 Cloud: Google Colab

If you prefer a **cloud-based** environment (no local installs):

1. Go to [Google Colab](https://colab.research.google.com/).  
2. **Open a notebook** from GitHub:  
   - Click **File** > **Open notebook** > **GitHub** tab.  
   - Search for your repository name or paste its GitHub URL.  
   - Select the notebook (`.ipynb`) you want to open.  
3. **Run and edit** directly in your browser:  
   - Google Colab provides free CPU/GPU usage (with some usage limits).  
   - No need to install Python or Jupyter locally.

---

*Choose the approach based on your setup and preferences. For quick fixes and demos, Google Colab is convenient; for full development, a local VS Code + conda environment is often more robust.*  

## 5. License

This repository uses **two different licenses**:

- **Code** in the [`code/`](code) directory is licensed under the [MIT License](LICENSE). This means you’re free to reuse and modify the code as long as you provide attribution and include the same license notice in your copies or forks.

- **Documentation and teaching materials** (including PDFs, lecture slides, and worksheets) in the [`docs/`](docs) directory are licensed under the [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](LICENSE-docs.md).  
  - You may share and adapt these materials for **non-commercial** purposes, but you must give appropriate credit and link back to this repository.  
  - Commercial use is **not** permitted without explicit permission.

---

## 6. Contact

- **Instructor**: Junichi Koganemaru ([jkoganem@andrew.cmu.edu](mailto:jkoganem@andrew.cmu.edu))  
- **Teaching Assistants**:  
  - Emma Kim ([egkim@andrew.cmu.edu](mailto:egkim@andrew.cmu.edu))  
  - Aniruddh Vasishta ([avasisht@andrew.cmu.edu](mailto:avasisht@andrew.cmu.edu))  
  - Sharon Xue ([slxue@andrew.cmu.edu](mailto:slxue@andrew.cmu.edu))  

For issues or questions related to the repository, please open a [GitHub issue](../../issues) or email the instructor.