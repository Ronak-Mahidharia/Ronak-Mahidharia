<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img src="assets/banner-light.svg" alt="Ronak Mahidharia. Software Engineer and AI Engineer. RAG, LLM evaluation, serverless AWS, React." width="100%">
</picture>

<p align="center">
  <img src="assets/typing.svg" alt="I get AI features into production. RAG, LLM evaluation, serverless AWS. Python, TypeScript, React.">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ronakmahidharia"><img src="assets/badge-linkedin.svg" alt="LinkedIn: ronakmahidharia" height="32"></a>
  &nbsp;
  <a href="mailto:ronakmahidharia3@gmail.com"><img src="assets/badge-email.svg" alt="Email: ronakmahidharia3@gmail.com" height="32"></a>
</p>

### 👋 About me
- 🏢 **Now:** Software Engineer I at [TermScout](https://www.termscout.com), an AI contract-intelligence platform, working across Python, React, and AWS serverless.
- 🤖 **Before:** AI Engineer at EDISCOVERIST, building an AI-powered Microsoft Word add-in for legal document review.
- 🎓 **Education:** M.S. in Information Systems, Northeastern University.
- 💡 **What I care about:** AI whose accuracy is measured rather than assumed, backends that fail loudly and recover cleanly, and interfaces people can use without a manual.

### 🚗 Featured project: [Car Safety Checker](https://github.com/Ronak-Mahidharia/car-safety-checker)
Describe a car problem in plain English and see the official NHTSA recalls and owner complaints that match it, each linked to NHTSA's record. **[Try it live](https://ronak-mahidharia.github.io/car-safety-checker/)**
- Found 84.6% of the right recalls on 1,000 held-out complaints, against 78.1% for a keyword baseline, using RAG and local LLMs.
- Runs entirely in the browser: the model was shrunk from 78.6 MB to about 1 MB with the same accuracy, so the site needs no server.
- An MCP server lets AI assistants use the same lookups. A tool-use evaluation of two local models led to fixes that took false safety assurances, in the answers that read a planted injection, from 3 of 4 to none.

### 🔐 Featured project: [Control Finder](https://github.com/Ronak-Mahidharia/control-finder)
Ask a security question in plain English and get the NIST SP 800-53 controls that answer it, each one cited, or a plain "not covered".
- Measured on NIST's own mappings: hybrid search over pgvector puts a right control first for 32.6% of held-out CSF 2.0 questions, against 17.4% for keyword search.
- Cited answers come from a local model whose citations can only name the controls it was shown. It said "not covered" for 19 of 20 out-of-scope questions.
- A FastAPI service and an MCP server for AI assistants, both checked against the published rankings, plus a React website.

### 🛠️ Tech I work with
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/skills-dark.svg">
  <img src="assets/skills-light.svg" alt="Python, TypeScript, JavaScript, React, Node.js, Express, Flask, PostgreSQL, MongoDB, Redis, AWS, Docker, GitHub Actions, Git, Tailwind CSS, Vite">
</picture>

**AI & LLM:** OpenAI API · Azure OpenAI · RAG · Azure AI Search · Prompt engineering · LLM evaluation

<details>
<summary><b>📈 Highlights from my work</b> (click to expand)</summary>
<br>

- Saved reviewers 3 to 4 hours per document with an AI-powered Microsoft Word add-in (React, TypeScript, Office.js) that checks provisions, detects the jurisdiction, and scores risk in ESI protocols and protective orders.
- Raised AI accuracy by 30% by grounding LLM output in jurisdiction rules, court templates, and domain-specific clauses through retrieval-augmented generation (RAG) on Azure Cognitive Search, now called Azure AI Search.
- Built a no-login contract analysis funnel in React and Python on AWS Lambda. It runs the core AI pipeline in its own isolated AWS account, returns results that match the main product field for field in about 3 to 4 minutes, and keeps the cost per analysis low.
- Added precision/recall (F1) scoring for multi-select AI answers to our evaluation tooling and validated it in production. It gives the team a much truer read on those answers than the old metric did.
- Cut release and onboarding time by 60% by containerizing the Node.js and Python services with Docker and scripting environment setup.

</details>
