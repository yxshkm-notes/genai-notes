# 🤖 Gen AI Notes

> *"Artificial intelligence is one of the most profound things we're working on as humanity. It's more profound than fire or electricity."*
> — **Sundar Pichai** (CEO, Google)

A structured, beginner-to-advanced documentation for **Generative AI** — covering everything from foundational math to LLMs, RAG, Agents, and beyond — built with [MkDocs Material](https://squidfunk.github.io/mkdocs-material/) and hosted on GitHub Pages.

🌐 **Live Site:** [yxshkm-notes.github.io/genai-notes](https://yxshkm-notes.github.io/genai-notes/)

![MkDocs](https://img.shields.io/badge/MkDocs-Material-blue?logo=materialformkdocs)
![GitHub Pages](https://img.shields.io/badge/Hosted-GitHub%20Pages-222?logo=github)
![License](https://img.shields.io/badge/License-MIT-green)
![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-orange)

---

## 📚 Topics Covered

<details>
<summary>🧱 Foundations</summary>

- What is Gen AI
- History & Evolution
- Types of Gen AI Models
- AI vs ML vs DL vs Gen AI

</details>

<details>
<summary>📐 Math & ML Basics</summary>

- Linear Algebra
- Probability & Statistics
- Calculus & Backpropagation
- Neural Networks Basics
- Optimization & Loss Functions

</details>

<details>
<summary>🧠 Deep Learning</summary>

- CNNs
- RNNs & LSTMs
- Attention Mechanism
- Encoder-Decoder Architecture

</details>

<details>
<summary>⚡ Transformers</summary>

- Transformer Architecture
- Self-Attention
- Positional Encoding
- BERT
- GPT Series
- Vision Transformer (ViT)

</details>

<details>
<summary>🗣️ Large Language Models</summary>

- What are LLMs
- Pretraining
- Tokenization
- Context Window
- Scaling Laws
- Emergent Abilities
- Popular LLMs

</details>

<details>
<summary>💬 Prompt Engineering</summary>

- Basic Prompting
- Zero-Shot & Few-Shot
- Chain of Thought
- Tree of Thought
- ReAct Prompting
- Prompt Chaining
- Prompt Injection & Security

</details>

<details>
<summary>🎛️ Fine-Tuning</summary>

- Why Fine-Tune
- Full Fine-Tuning
- LoRA & QLoRA
- RLHF
- DPO
- Instruction Tuning
- Dataset Preparation

</details>

<details>
<summary>🔍 Embeddings & Vector Search</summary>

- What are Embeddings
- Word2Vec & GloVe
- Sentence Embeddings
- Vector Databases
- Similarity Search
- ANN Algorithms

</details>

<details>
<summary>📦 RAG</summary>

- What is RAG
- Naive RAG
- Advanced RAG
- Modular RAG
- Chunking Strategies
- Retrieval Strategies
- Reranking
- RAG Evaluation

</details>

<details>
<summary>🤖 AI Agents</summary>

- What are Agents
- Agent Architectures
- Tool Use & Function Calling
- Memory Types
- Planning & Reasoning
- Multi-Agent Systems
- Agentic Frameworks

</details>

<details>
<summary>🛠️ Frameworks & Tools</summary>

- LangChain
- LlamaIndex
- LangGraph
- HuggingFace
- OpenAI SDK
- Ollama

</details>

<details>
<summary>🎨 Multimodal AI</summary>

- Text to Image
- Image to Text
- Text to Audio
- Text to Video
- Vision Language Models
- Speech Models

</details>

<details>
<summary>🌊 Diffusion Models</summary>

- What are Diffusion Models
- DDPM
- Stable Diffusion Architecture
- Guidance & Conditioning
- ControlNet & LoRA

</details>

<details>
<summary>📊 Evaluation & Benchmarks</summary>

- LLM Evaluation Metrics
- RAG Evaluation
- Benchmarks
- Hallucination Detection
- Human Eval vs Auto Eval

</details>

<details>
<summary>🚀 Deployment & MLOps</summary>

- Model Serving
- Quantization
- Distillation
- Inference Optimization
- LLMOps
- Monitoring LLMs

</details>

<details>
<summary>🛡️ Safety & Alignment</summary>

- AI Alignment
- Hallucinations
- Bias & Fairness
- Red Teaming
- Guardrails
- Responsible AI

</details>

<details>
<summary>💼 Use Cases</summary>

- Chatbots & Assistants
- Code Generation
- Summarization
- Question Answering
- Content Generation
- Enterprise Gen AI

</details>

---

## 🛠️ Built With

| Tool | Purpose |
|------|---------|
| [MkDocs](https://www.mkdocs.org/) | Static site generator |
| [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) | Theme |
| [GitHub Pages](https://pages.github.com/) | Hosting |
| Markdown | Content writing |

---

## 🚀 Run Locally

Follow these steps to run the project on your machine:

### 1. Clone the repo
```bash
git clone https://github.com/yxshkm-notes/genai-notes.git
cd genai-notes
```

### 2. Create & activate virtual environment
```bash
python -m venv venv

# Mac/Linux
source venv/bin/activate

# Windows
venv\Scripts\activate
```

### 3. Install dependencies
```bash
pip install mkdocs mkdocs-material
```

### 4. Preview locally
```bash
mkdocs serve
```
Open [http://127.0.0.1:8000](http://127.0.0.1:8000) in your browser.

### 5. Deploy to GitHub Pages
```bash
mkdocs gh-deploy
```

---

## 📁 Project Structure

```
genai-notes/
├── docs/
│   ├── index.md
│   ├── Foundations/
│   ├── Math & ML Basics/
│   ├── Deep Learning/
│   ├── Transformers/
│   ├── Large Language Models/
│   ├── Prompt Engineering/
│   ├── Fine-Tuning/
│   ├── Embeddings & Vector Search/
│   ├── RAG/
│   ├── AI Agents/
│   ├── Frameworks & Tools/
│   ├── Multimodal AI/
│   ├── Diffusion Models/
│   ├── Evaluation & Benchmarks/
│   ├── Deployment & MLOps/
│   ├── Safety & Alignment/
│   └── Use Cases/
├── mkdocs.yml
└── README.md
```

---

## 🤝 Contributing

Contributions are welcome and appreciated! Whether it's fixing a typo, improving an explanation, or adding new examples — every bit helps. 🙌

### ✅ What You Can Contribute

- Fix typos or grammar mistakes
- Improve or simplify existing explanations
- Add better examples or diagrams
- Add missing topics or subtopics
- Fix broken links or formatting issues

---

### 📋 Contribution Steps

**1. Fork the repository**

Click the **Fork** button at the top right of this page.

**2. Clone your fork**
```bash
git clone https://github.com/your-username/genai-notes.git
cd genai-notes
```

**3. Create a new branch**
```bash
git checkout -b your-branch-name
# Example: git checkout -b fix/rag-typo
# Example: git checkout -b add/lora-examples
```

**4. Set up the project locally**
```bash
python -m venv venv
source venv/bin/activate     # Mac/Linux
venv\Scripts\activate        # Windows

pip install mkdocs mkdocs-material
```

**5. Make your changes**

Edit the relevant `.md` file inside the `docs/` folder.

**6. Preview your changes**
```bash
mkdocs serve
```
Open [http://127.0.0.1:8000](http://127.0.0.1:8000) and verify everything looks correct.

**7. Commit your changes**
```bash
git add .
git commit -m "fix: corrected typo in RAG.md"
```

**8. Push to your fork**
```bash
git push origin your-branch-name
```

**9. Open a Pull Request**

Go to the original repo on GitHub and click **"New Pull Request"**. Describe what you changed and why.

---

### 📝 Commit Message Format

Please follow this format for commit messages:

| Prefix | When to use |
|--------|-------------|
| `fix:` | Bug fix, typo correction |
| `add:` | New content or topic added |
| `update:` | Improving existing content |
| `remove:` | Removing outdated content |
| `style:` | Formatting changes only |

**Examples:**
```
fix: corrected explanation in Tokenization.md
add: added LoRA diagram in Fine-Tuning.md
update: improved RAG chunking strategies section
style: fixed code block formatting in Transformers.md
```

---

### 🗂️ Writing Style Guide

To keep the docs consistent, please follow these guidelines when writing content:

- Use **simple, beginner-friendly language**
- Always include a **visual or example** for every concept where possible
- Add **diagrams or pseudocode** to explain architectures
- Use admonitions for tips, warnings, and notes:
  ```
  !!! tip "Title"
      Your tip here.

  !!! warning "Title"
      Your warning here.

  !!! info "Title"
      Your info here.
  ```
- Use **tables** for comparisons (e.g., BERT vs GPT, RAG vs Fine-tuning)
- Keep explanations **concise and focused**

---

### 🐛 Reporting Issues

Found a mistake or something that can be improved?

1. Go to the [Issues](https://github.com/yxshkm-notes/genai-notes/issues) tab
2. Click **"New Issue"**
3. Describe the problem clearly with the page name and what needs to be fixed

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

⭐ If you find this helpful, give it a star — it keeps the motivation going!