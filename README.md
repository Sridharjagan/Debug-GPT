DebugGPT 🔍
A syntax-tolerant AI debugging framework for Python that combines static analysis with large language model reasoning.

Research paper submitted for publication — 2026


What it does
Most LLM-based debugging tools fail on broken or incomplete code because they require valid syntax as input. DebugGPT is built differently.
It uses a two-stage pipeline:

Static analysis stage — An AST-based parser pre-processes the code, tolerating syntax errors and incomplete structures that would crash standard parsers.
LLM reasoning stage — The pre-processed representation is passed to a large language model, which generates a natural-language explanation of the error with contextual accuracy.

The result: intelligent debugging that works even on the messy, broken code you actually encounter in real development.

Key features

Syntax-tolerant parsing — Handles malformed, incomplete, or partially erroneous Python code
NLP-driven intent classification — Interprets ambiguous or informal debugging queries before routing them to the appropriate strategy
LLM-augmented explanations — Generates human-readable, contextually accurate error explanations
Authenticated encrypted storage — Session debugging reports are stored with AES-based authenticated encryption, ensuring data confidentiality and tamper-evident retrieval

Tech stack
LayerTechnologyCore languagePythonStatic analysisAbstract Syntax Tree (AST)NLPIntent detection, query classificationLLM integrationLarge Language Model APIEncryptionAES (authenticated encryption)CloudIBM CloudDevelopmentJupyter Notebook, Git

Research
This project is the basis of a research paper currently under review for publication (2026):
"DebugGPT: A Syntax-Tolerant Static and LLM-Augmented Debugging Framework for Python with Authenticated Encrypted Report Storage"
Key research contributions:

Syntax-tolerant code parsing for real-world debugging scenarios
NLP-driven intent classification for debugging query interpretation
Authenticated encrypted report storage for session auditability
Novel two-stage hybrid architecture combining rule-based and generative AI approaches


About the author
Sridhar J — B.Tech AI & Data Science, Dr. MGR Educational and Research Institute, Chennai

📧 sridharjagan1906@gmail.com
🔗 LinkedIn


Status
🔬 Research paper under review | 🛠️ Active development

If you're working on AI-assisted developer tooling, code intelligence, or LLM applications — feel free to reach out.
