# AI23231 - Principles of Artificial Intelligence Lab (POAI)

**Rajalakshmi Engineering College**  
**Department of Artificial Intelligence and Machine Learning**  
**Regulation 2023 | I Year – II Semester**  
**Repository:** [https://github.com/Ragshanth/POAI](https://github.com/Ragshanth/POAI)

---

## 📂 Laboratory Experiments & Code Files

Every experiment from the lab manual is implemented in its own dedicated file named after the experiment:

| Ex. No. | Experiment Title | File Name | Language |
| :---: | :--- | :--- | :---: |
| **1** | **Implement Eight Queens Problem** | [`eight_queens_problem.py`](./eight_queens_problem.py) | Python |
| **1b** | **Implementation of Depth First Search** | [`depth_first_search.py`](./depth_first_search.py) | Python |
| **1c** | **Implementation of Minimax Algorithm** | [`minimax_algorithm.py`](./minimax_algorithm.py) | Python |
| **1d** | **Implementation of A* Search Algorithm** | [`a_star_search_algorithm.py`](./a_star_search_algorithm.py) | Python |
| **2** | **Decision Making & Knowledge Representation (Prolog)** | [`decision_making_and_knowledge_representation.pl`](./decision_making_and_knowledge_representation.pl) | Prolog |
| **2 (alt)** | **Decision Making & Knowledge Representation (Python)** | [`decision_making_and_knowledge_representation.py`](./decision_making_and_knowledge_representation.py) | Python |
| **5 (part)** | **Find Minimum and Maximum of Two Numbers** | [`find_minimum_maximum_of_two_numbers.pl`](./find_minimum_maximum_of_two_numbers.pl) | Prolog |
| **6 (part)** | **Implementation of Simple Clause** | [`simple_clause.pl`](./simple_clause.pl) | Prolog |
| **2b** | **Implementation of Unification and Resolution Algorithm** | [`unification_and_resolution_algorithm.py`](./unification_and_resolution_algorithm.py) | Python |
| **2c** | **Implementation of Backward Chaining** | [`backward_chaining.py`](./backward_chaining.py) | Python |
| **2d** | **Implementation of Forward Chaining** | [`forward_chaining.py`](./forward_chaining.py) | Python |
| **3a** | **Implementation of Blocks World Program** | [`blocks_world_program.py`](./blocks_world_program.py) | Python |
| **3b** | **Implementation of a Fuzzy Inference System** | [`fuzzy_inference_system.py`](./fuzzy_inference_system.py) | Python |
| **Viva** | **35 Viva Questions with Answers** | [`viva_questions_and_answers.md`](./viva_questions_and_answers.md) | Markdown |

> *Note: For convenience with lab number indexing, numbered aliases (`ex1_...`, `ex1b_...`, etc.) are also retained.*

---

## 🛠️ Requirements & Setup

### Python Dependencies
To install dependencies for the experiments (specifically for fuzzy inference):
```bash
pip install -r requirements.txt
```
*(Dependencies: `numpy`, `scikit-fuzzy`)*

### Prolog Setup
For Prolog files (`.pl`):
- Run using [SWI-Prolog](https://www.swi-prolog.org/) or GNU Prolog.
- Example execution:
  ```bash
  swipl decision_making_and_knowledge_representation.pl
  ```
- Alternatively, you can run the equivalent Python simulation: `decision_making_and_knowledge_representation.py`.

---

## 🚀 How to Upload / Push to GitHub (`Ragshanth/POAI`)

### Method 1: Using the GitHub Web Interface (Easiest & Fastest)
1. Open your repository in your browser: [https://github.com/Ragshanth/POAI](https://github.com/Ragshanth/POAI).
2. Click **Add file** ➔ **Upload files**.
3. Drag and drop all the files from this folder (`C:\Users\PREM PA\.gemini\antigravity\scratch\POAI`).
4. Enter commit message (e.g., `Add POAI lab experiments and manual codes`) and click **Commit changes**.

### Method 2: Using Git CLI (Once Git is installed)
```bash
cd "C:\Users\PREM PA\.gemini\antigravity\scratch\POAI"
git init
git add .
git commit -m "Add POAI lab experiments from lab manual"
git branch -M main
git remote add origin https://github.com/Ragshanth/POAI.git
git push -u origin main
```
