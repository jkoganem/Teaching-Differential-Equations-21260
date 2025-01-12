# 21-260 Differential Equations

Welcome to the **21-260 Differential Equations** repository. This is a collection of lecture notes, code, and other resources for students enrolled in the 21-260 Differential Equations at Carnegie Mellon University (or for anyone interested in learning about differential equations).

For students enrolled in the course, please access additional resources (such as Gradescope for homework submissions and Piazza for Q&A) through [Canvas](https://canvas.cmu.edu/courses/45779).

## Author

**Junichi Koganemaru** ([@jkoganem](https://github.com/jkoganem))  
Email: [jkoganem@andrew.cmu.edu](jkoganem@andrew.cmu.edu)  

> **Note for students:** please include the header “21-260” in the subject line of your email when you email me, otherwise your email might get lost in the shuffle.

## Table of Contents
1. [About the Course](#about-the-course)  
2. [Repo Structure](#repo-structure)  
3. [How to Use These Materials](#how-to-use-these-materials)  
4. [Installation & Setup](#installation--setup)  
5. [License](#license)  
6. [Contributing](#contributing)  
7. [Contact](#contact)  
---

## 1. About the Course

In this course we explore the theory, methods, and applications of ordinary and partial differential equations. The key topics we cover include:

- First-order ODEs, existence and uniqueness of solutions  
- Second and higher-order linear ODEs 
- Systems of differential equations, stability analysis
- Laplace transforms and their applications  
- Numerical methods  
- Linear partial differential equations (Laplace, heat, wave)

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

> **Note:** If you just want to read the files (`.pdf` or `.ipynb`), you can simply  open them directly in your browser. 

The following steps guide you through setting up a local environment to run the Jupyter Notebooks and other code examples. Cloning the repository also ensures that you can easily update the local files as needed.

### 4.1. Git: Cloning the Repository

1. **Git (Command Line)**  
   - Make sure you have Git installed.  
   - In your terminal, navigate to the folder where you want to clone the course repository, then run:
     ```bash
     git clone https://github.com/your-username/your-repo-name.git
     cd your-repo-name
     ```
2. **GitHub Desktop (GUI Option)**  
   - [Download GitHub Desktop](https://desktop.github.com/) (available for Windows and macOS).  
   - Open GitHub Desktop and sign in with your GitHub account.  
   - Click **File** > **Clone repository**, select your repository, and choose a local path to clone into.

### 4.2. Local Environment for running Jupyter Notebooks (VS Code + Anaconda + Jupyter): 

1. **Install VS Code**  
   - [Download Visual Studio Code](https://code.visualstudio.com/download) (available for Windows, macOS, and Linux).  
   - Install the **Python** extension in VS Code for syntax highlighting, linting, and Jupyter notebook support.

2. **Install Anaconda/Miniconda**  
   - [Download Anaconda](https://www.anaconda.com/products/individual) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html).  
   - This provides `conda`, a powerful tool for creating and managing Python environments.

3. **Create a Conda Environment**  
   - Open a terminal (or Anaconda Prompt if on Windows) and navigate to the cloned repo.
   - Use the provided `environment.yml` file and create a new virtual environment:
     ```bash
     # Using environment.yml:
     conda env create -f environment.yml -n my-env-name
     conda activate my-env-name 
     ```
4. **Open Jupyter Notebooks in VS Code**  
   - Launch VS Code and open your cloned repository folder.
   - Open a `.ipynb` file.
   - VS Code’s Jupyter extension will automatically detect your conda environment; you can choose it from the top-right kernel selection menu.
   - Run code cells interactively within VS Code.

---

### 4.3. Google Colab: Cloud-based environment for Jupyter Notebooks

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

*For quick demos, Google Colab is convenient; for full development, a local VS Code + conda environment is often more robust.*  

### 4.4. Troubleshooting

If you encounter any issues during the setup process, consider the following tips:

1. **Environment Issues**:
    - Ensure that the correct conda environment is activated.
    - Check for any missing dependencies and install them using `conda` or `pip`.

2. **Jupyter Notebook Issues**:
    - If Jupyter notebooks are not opening in VS Code, ensure the Jupyter extension is installed and enabled.
    - Restart VS Code and try reopening the notebook.

3. **Git Issues**:
    - If you face issues with cloning the repository, check your internet connection and Git installation.
    - Ensure you have the correct permissions to access the repository.

For further assistance, feel free to open a [GitHub issue](../../issues) or contact the instructor.

---

### 4.5. Additional Resources

For more information on the tools and technologies used in this course, refer to the following resources:

- [Python Documentation](https://docs.python.org/3/)
- [Git Documentation](https://git-scm.com/doc)
- [Anaconda Documentation](https://docs.anaconda.com/)
- [VS Code Documentation](https://code.visualstudio.com/docs)
- [Jupyter Documentation](https://jupyter.org/documentation)

These resources provide comprehensive guides and tutorials to help you get the most out of the tools used in this course.


## 5. License

This repository uses **two different licenses**:

- **Code** in the [`code/`](code) directory is licensed under the [MIT License](LICENSE). This means you’re free to reuse and modify the code as long as you provide attribution and include the same license notice in your copies or forks.

- **Documentation and teaching materials** (including PDFs, lecture slides, worksheets) in the [`docs/`](docs) directory are licensed under the [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](LICENSE-docs.md).  
  - You may share and adapt these materials for **non-commercial** purposes, but you must give appropriate credit and link back to this repository.  
  - Commercial use is **not** permitted without explicit permission.


## 6. Contact

- **Instructor**: Junichi Koganemaru (jkoganem@andrew.cmu.edu)
- **Teaching Assistants**: Emma Kim (egkim@andrew.cmu.edu), Aniruddh Vasishta (avasisht@andrew.cmu.edu), Sharon Xue (slxue@andrew.cmu.edu)
- For issues or questions related to the repository, please open a [GitHub issue](../../issues) or email the instructor.

---