# controlQA300

A curated question–answering dataset for control systems courses, designed for supervised fine-tuning and multidimensional evaluation of large language models.

## Overview

**controlQA300** contains 236 manually reviewed problems with standardized solutions, metadata, and auxiliary materials. Each problem is organized as a self-contained directory, covering core topics in linear control systems: system modeling, differential equations, Laplace transforms, transfer functions, stability, time-domain response, frequency-domain analysis, and controller design.

The dataset is intended to support research on:

- LoRA-based parameter-efficient fine-tuning
- Model scale and rank effects
- Educational question-answering evaluation
- Structured teaching expressions (Solution–Method–Teaching Points)

All problems and solutions are written in English. The dataset was constructed from official course materials and reference solutions, and each sample has been human-checked for correctness and consistency.

## Dataset Structure

The repository is organized as follows:

```
problems/
│
├── problem_001/
│   ├── problem.md           # Main problem description
│   ├── solution.md          # Detailed solution
│   ├── metadata.json        # Problem metadata
│   ├── images/              # Related figures (optional)
│   ├── code/                # Relevant code files (optional)
│   └── references/          # References or sources (optional)
│
├── problem_002/
│   └── ...
...
└── problem_236/
```

Each `problem_XXX` directory is self-contained and follows the same layout.

## File Format

### `problem.md`

Contains the full problem statement, including:

- Problem description
- Subproblems (if any)
- Additional information (assumptions, conventions)
- Constraints (e.g., qualitative explanations required, use of basic terminology)

### `solution.md`

Contains the complete reference solution, structured as:

- **General Remarks** (optional)
- **Solution** for each subproblem
- **Teaching Points**
- **Common Mistakes**

Solutions include mathematical derivations, LaTeX formulas, and clear explanations.

### `metadata.json`

A JSON object describing the problem. Example fields:

```json
{
  "id": "problem_001",
  "title": "Interpretation of Block Diagrams in Control Systems",
  "difficulty": "easy_to_medium",
  "difficulty_score": 0.55,
  "expert_rating": 4.2,
  "expert_review": "Good introductory problem for understanding control system block diagrams",
  "keywords": ["block-diagram", "control-system", "open-loop", "closed-loop", "feedback", "dynamic-system"],
  "subjects": ["control-systems", "systems-theory"],
  "prerequisites": ["basic-control-theory", "linear-systems"],
  "tags": ["undergraduate", "introductory", "conceptual"],
  "created_date": "2026-01-05",
  "last_modified": "2026-01-05",
  "estimated_time": 12,
  "source": "Control Systems Textbook - Chapter 1",
  "problem_type": "conceptual_analysis",
  "skill_levels": {
    "conceptual": 4,
    "procedural": 2,
    "problem_solving": 3
  },
  "bloom_taxonomy": ["understand", "analyze"],
  "common_misconceptions": [
    "assuming all systems are dynamic",
    "misinterpreting feedback paths",
    "confusing reference and disturbance signals"
  ],
  "learning_objectives": [
    "Identify components of control system block diagrams",
    "Distinguish between open-loop and closed-loop systems",
    "Recognize static and dynamic system behavior",
    "Relate block-diagram signals to physical quantities"
  ]
}
```

**Field descriptions:**

| Field | Description |
|-------|-------------|
| `id` | Unique identifier (e.g., `problem_001`) |
| `title` | Short descriptive title |
| `difficulty` | Categorical difficulty level |
| `difficulty_score` | Numeric difficulty score (0–1) |
| `expert_rating` | Expert rating (1–5) |
| `expert_review` | Brief expert comment |
| `keywords` | List of keywords |
| `subjects` | Subject areas |
| `prerequisites` | Required background knowledge |
| `tags` | Additional tags (audience, type) |
| `created_date` | Date of creation |
| `last_modified` | Date of last modification |
| `estimated_time` | Estimated solving time (minutes) |
| `source` | Source of the problem |
| `problem_type` | Type of problem (e.g., conceptual, computational) |
| `skill_levels` | Self-assessed skill levels (1–5) |
| `bloom_taxonomy` | Bloom's taxonomy levels |
| `common_misconceptions` | Typical student misconceptions |
| `learning_objectives` | Learning objectives |

## Example

For `problem_001`, see:

- [`problem_001/problem.md`](problems/problem_001/problem.md)
- [`problem_001/solution.md`](problems/problem_001/solution.md)
- [`problem_001/metadata.json`](problems/problem_001/metadata.json)

## Usage

### Loading the dataset

You can load all problems by iterating over the `problems/` directory. Each problem is a directory containing the three main files. For example, in Python:

```python
import json
import os

base_dir = "problems"
problems = []

for problem_id in sorted(os.listdir(base_dir)):
    problem_dir = os.path.join(base_dir, problem_id)
    if os.path.isdir(problem_dir):
        with open(os.path.join(problem_dir, "metadata.json"), "r", encoding="utf-8") as f:
            metadata = json.load(f)
        with open(os.path.join(problem_dir, "problem.md"), "r", encoding="utf-8") as f:
            problem_text = f.read()
        with open(os.path.join(problem_dir, "solution.md"), "r", encoding="utf-8") as f:
            solution_text = f.read()
        problems.append({
            "id": problem_id,
            "metadata": metadata,
            "problem": problem_text,
            "solution": solution_text
        })
```

### Converting to fine-tuning format

To use this dataset for supervised fine-tuning (e.g., with LoRA), you can convert each problem into a `system–user–assistant` conversation:

- **system**: "You are a control systems teaching assistant. Provide structured answers with Solution, Method, and Teaching Points."
- **user**: The content of `problem.md`
- **assistant**: The content of `solution.md`

Store the resulting samples as JSONL.

## License

The dataset is released under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license. You are free to share and adapt the material for any purpose, provided you give appropriate credit.

Please add a `LICENSE` file to the repository with the full license text.

## Citation
If you use controlQA300 in your research, please cite:

```bibtex
@article{controlQA300,
  title = {LoRA Fine-Tuned Models for Control Systems Course Q\&A: A Multidimensional Evaluation of Model Scale and Rank Effects},
  author = {Shaowen Lu, Chengxu Liu, Ping Zhou and Tao Yang},
  year = {2026},
  howpublished = {\url{arXiv:2609.13918}},
  note = {Dataset}
}
```

## Contributing

Contributions are welcome. To add a new problem:

1. Create a new directory under `problems/` named `problem_XXX` (use the next available number).
2. Add `problem.md`, `solution.md`, and `metadata.json` following the formats above.
3. Optional: add `images/`, `code/`, or `references/` if needed.
4. Ensure all formulas use LaTeX and that solutions are clearly structured.
5. Submit a pull request.

Please maintain the same quality standards: human-reviewed, consistent terminology, and clear pedagogical structure.

## Contact

For questions or suggestions, please open an issue or contact the maintainers lusw@mail.neu.edu.cn.

---

**controlQA300** – Supporting reproducible research in educational question answering and parameter-efficient fine-tuning for control systems.
