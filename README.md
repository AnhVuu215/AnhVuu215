## Hi, I'm Tuấn Anh 👋

Final-year student at HUCE (Hanoi) working toward **AI Engineering**: retrieval-augmented systems that cite their sources, refuse when they should, and come with an evaluation that says how well they actually work.

🎯 Looking for an **AI Engineer / Backend internship**.

### 🚀 Projects

**[huce-regulation-qa](https://github.com/AnhVuu215/huce-regulation-qa)** · Python · FastAPI · bge-m3 · Gemini<br>
RAG assistant that answers students' questions about HUCE academic regulations, citing the exact Article/Clause from the regulation version that applies to the student's cohort.
- Structure-aware chunking (Article/Clause/Point), hybrid vector + BM25 retrieval, cohort-based version filtering: Recall@5 0.75 → 0.94, wrong-version results in top-5 44% → 0%
- GPA and grading computed by code through function calling; every cited Article verified by code against the retrieved passages
- Evaluated with step-by-step ablation, a held-out set of real student questions, and hand grading to check the LLM judge; CI with ruff, mypy and 128 tests

**[HUCEScholar](https://github.com/AnhVuu215/HUCEScholar)** · Next.js · NestJS · PostgreSQL · Redis<br>
Learning-materials platform for HUCE students: read PDFs in the browser with per-page notes, highlights and flashcards; students contribute documents, admins review them before publishing.
- Upload pipeline with virus scanning (ClamAV) and Word → PDF conversion in a background worker
- Role-based permissions, document moderation workflow, PWA, Playwright end-to-end tests

**[interview-practice-ai](https://github.com/ToraidolGiang/interview-practice-ai)** · Spring Boot · React · PostgreSQL · team project<br>
AI mock-interview platform in Vietnamese: speech-to-text, LLM scoring against a rubric, text-to-speech. One of the two main contributors.
- Asynchronous scoring (202 + polling), AI services behind adapters, JWT + RBAC

### 🛠️ Tech

<p>
  <img src="https://skillicons.dev/icons?i=python,fastapi,pytorch,ts,nextjs,nestjs,react,java,spring,postgres,redis,docker,githubactions" alt="Python, FastAPI, PyTorch, TypeScript, Next.js, NestJS, React, Java, Spring Boot, PostgreSQL, Redis, Docker, GitHub Actions" />
</p>

<!-- Contact: thêm khi có link thật, ví dụ:
### 📫 Contact
[LinkedIn](https://www.linkedin.com/in/...) · [Email](mailto:...) · [CV](https://...)
-->
