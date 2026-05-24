# Math_Solver_AI.ipynb
Lightweight local math &amp; puzzle solver using Qwen2.5-1.5B GGUF (llama.cpp) + SymPy symbolic engine + Gradio chat UI. Provides concise step-by-step solutions, LaTeX boxed answers, auto-plots, and handles equations, derivatives, integrals, matrices, optimization, puzzles.

Demo Math_Solver_AI Video Clips

https://github.com/user-attachments/assets/6ce954f1-79c7-4673-8af5-a1934d10fc9f


# 🧠 Upgraded Math Solver Chat

An intelligent math assistant that combines symbolic computation (SymPy) with a local LLM (Qwen2.5-1.5B) to solve equations, derivatives, integrals, optimization problems, and even generate graphs – all through a clean Gradio chat interface.

![Demo](https://via.placeholder.com/800x400?text=Math+Solver+Demo)  <!-- Replace with actual screenshot later -->

## ✨ Features

- ✅ **Symbolic solving** – equations, derivatives, integrals, matrices, optimization
- 🧮 **Step-by-step natural language explanations** – powered by a local GGUF LLM (Qwen 1.5B)
- 📈 **Graph plotting** – automatically draws functions when you ask to “plot” or “graph”
- 💬 **Interactive chat UI** – built with Gradio, supports LaTeX and boxed answers
- ⚡ **Lightweight** – runs on CPU (no GPU required), uses llama.cpp for efficient inference
- 🧪 **Robust input cleaning** – converts natural language math into valid SymPy expressions

## 🛠️ Tech Stack

- **Python 3.9+**
- [Gradio](https://gradio.app/) – chat interface
- [SymPy](https://www.sympy.org/) – symbolic mathematics
- [llama-cpp-python](https://github.com/abetlen/llama-cpp-python) – CPU‑efficient LLM inference
- [Hugging Face Hub](https://huggingface.co/) – downloads the GGUF model
- [Matplotlib](https://matplotlib.org/) + NumPy – graph generation
- SciPy, PuLP – numerical optimization (PuLP imported, ready for extension)

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/math-solver-chat.git
   cd math-solver-chat

   Create a virtual environment (recommended)

python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

Install dependencies

pip install -r requirements.txt

Note: llama-cpp-python may require a C++ compiler. On Windows, install Visual Studio Build Tools; on Linux, build-essential. For faster CPU inference, you can compile with OpenBLAS or other optimisations.

Download the model automatically
The first time you run the script, it will download qwen2.5-1.5b-instruct-q5_k_m.gguf (~1 GB) from Hugging Face. Ensure you have enough disk space and a stable internet connection.




