# LLM4Decompile: Reconstructing C Code from Binaries

This repository contains a Python-based solution leveraging one of the **LLM4Decompile** models to achieve decompilation of compiled binaries into their original C code. The goal is to evaluate how accurately the reconstructed code aligns with the original source.

The implementation is provided in a Jupyter Notebook, which you can explore and execute using Google Colab for an interactive experience.

---

## Features

- **Decompilation:** Utilizes a powerful language model trained for code deconstruction to convert binary files back into C source code.
- **Accuracy Assessment:** Compares the reconstructed C code with the original code to measure accuracy and fidelity.
- **Python Implementation:** A complete Python solution for processing binary files, interfacing with the LLM4Decompile model, and evaluating results.
- **Colab Compatibility:** Run the solution seamlessly in Google Colab for accessibility and ease of use.

---

## Getting Started

### Prerequisites

- **Python 3.7+**
- Jupyter Notebook (optional if running locally)
- Google Colab account (for hosted execution)

### Running the Notebook

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/LLM4Decompile.git
   cd LLM4Decompile
   ```
2. Open the notebook (`LLM4Decompile_Task.ipynb`) in your environment of choice:
   - **Locally:** Launch Jupyter Notebook or JupyterLab.
   - **Colab:** Upload the notebook to your Google Colab account.
3. Follow the instructions in the notebook to:
   - Load the binary input files.
   - Execute the decompilation using the LLM4Decompile model.
   - Compare the results with the original source code.

---

## Files and Structure

- **LLM4Decompile_Task.ipynb:** Main notebook containing the Python-based solution.
- **README.md:** Overview and instructions.
- **Input Files:** Include or reference binary files for testing.

---

## Model Details

The decompilation process leverages an **LLM4Decompile model** pre-trained on diverse codebases and designed to handle binary-to-source translations. The model aims to maximize accuracy by preserving logical and structural integrity.

---

## Results and Evaluation

The notebook includes metrics and visualizations to assess:
- Structural similarity between reconstructed and original code.
- Functional equivalence through test cases (if available).

---

## License

This project's code part is licensed under myself. Except the sources [[LICENSE](https://github.com/albertan017/LLM4Decompile)]([LICENSE](https://huggingface.co/arise-sustech/llm4decompile-1.3b)) resources for details.

---

## Acknowledgments

- **LLM4Decompile:** For providing the decompilation model.
- Community contributors for supporting the development of binary-to-source translation tools.
