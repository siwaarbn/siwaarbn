## Siwar Ben Nejma

I build LLM systems and the tools around them. I'm doing my M.Sc. in Computer Science at TU Darmstadt, work as an AI/ML working student at MorgenFund (DWS) in Frankfurt, where I build LLM pipelines for document processing, and teach Parallel Programming as a TA.

**Portfolio:** [siwaarbn.github.io](https://siwaarbn.github.io)

---

### Research

**Masked diffusion language models for code generation.** Seminar work on how diffusion LLMs write code by unmasking tokens in parallel, and on making their RL training more stable. I proposed tracking "AR-ness" as an early warning signal during training and an adaptive temperature schedule for rollouts. Currently under review with Springer.

---

### Projects

**[Python Mental Model Linter](https://github.com/siwaarbn/python-mental-model-linter)** · my Bachelor thesis (graded 1.0). Finds the wrong belief behind a beginner's Python bug, not just the broken line. 22 readable AST rules detect 11 misconceptions without running the code, and each finding opens up in four layers of feedback. FastAPI, React, TypeScript; usability score 86.9 with 13 testers.

**[GROF](https://github.com/siwaarbn/grof)** · GPU profiler for AI workloads, built in a team of 5 at TU Darmstadt. Links CPU call stacks to the GPU kernels they launch using eBPF and CUDA, at under 5% overhead. I built the backend (FastAPI, PostgreSQL, Redis) and the dashboard (React, D3.js flamegraphs and GPU timeline).

**[codesearch](https://github.com/siwaarbn/codesearch)** · semantic code search. Find functions by what they *do*, not what they're called. tree-sitter for parsing, sentence-transformers for embeddings, FAISS for retrieval, with a CLI and a small web UI.

**[ragbase](https://github.com/siwaarbn/ragbase)** · question answering over PDFs. Every answer cites the pages it came from, and a RAGAS check scores how faithful it is. PyMuPDF, ChromaDB, Llama 3.3 via Groq, Streamlit.

---

### Stack

`Python` `TypeScript` `React` `FastAPI` `PostgreSQL` `Docker` `LLMs` `RAG` `FAISS` `ChromaDB` `eBPF` `CUDA`

---

### Contact

[Portfolio](https://siwaarbn.github.io) · [LinkedIn](https://www.linkedin.com/in/siwar-ben-nejma-879606403) · siwarbennejma2@gmail.com · Darmstadt, Germany
