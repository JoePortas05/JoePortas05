# 👋 Hi, I'm Joseph Portas!

I'm a recent Northeastern University graduate with an M.S. in Computer Science and a B.S. in Computer Science with a minor in Mathematics, completed cum laude on an accelerated path.

I've built software across full-stack web development, cloud deployment, systems programming, developer tooling, and machine-learning evaluation. My work includes a production-deployed final exam scheduling platform for Northeastern University's Registrar, Python and PySide6 tools projected to save BAE Systems more than $750,000 annually, and reproducible frameworks for auditing machine-learning and AI evaluations.

I'm especially interested in technical AI safety, frontier-model evaluations, evaluation integrity, deceptive behavior, reward hacking, and independent auditing. My goal is to apply strong software engineering and experimental design to help make increasingly capable AI systems safer, more transparent, and more accountable.

I love combining creativity and technical skill to solve challenging problems with real impact on real people. Outside of coding, I'm usually studying Turkish, climbing, singing, playing the cello, or tutoring students in computer science, math, and test preparation.

---

## 🚀 Technical Skills

* **Languages:** Python, TypeScript, JavaScript, Java, SQL, C++, C, Racket, Bash
* **AI & Machine Learning:** Inspect AI, scikit-learn, NumPy, model evaluation, experimental design
* **Frameworks & Tools:** Next.js, React, Node.js, FastAPI, Express, PySide6, Git, Docker, AWS, GitHub Actions, PostgreSQL, Pytest

---

## 📂 Projects

Some projects are housed in organization repositories or private academic repositories. Code is available upon request when permitted.

### 🛡️ [EvalGuard](https://github.com/JoePortas05/EvalGuard) — AI Evaluation Integrity Framework *(Sep 2026 – Present)*

* Built a Python and Docker audit harness with Inspect AI integration to identify scoring and accounting defects that can inflate reported model performance
* Constructed 52 benchmark variants and corrected a structural shortcut that enabled 87.5% heuristic accuracy, reducing it to 50% and removing a misleading signal from reviewer evaluation
* Implemented resumable audit execution and verified a 36-audit mock pilot with no duplicated calls or results after resumption, preventing completed work from being repeated

### 📅 [Final Exam Scheduling System](https://github.com/KhourySpecialProjects/ExamEngine) *(Sep 2025 – Jan 2026)*

* Collaborated with Northeastern Registrar stakeholders, the Vice Provost, and a seven-person Agile team to replace a paper-based scheduling workflow with a full-stack platform built using Next.js, TypeScript, FastAPI, PostgreSQL, and SQLAlchemy
* Automated timetable creation for more than 15,000 students, 1,500 course sections, and 270 classrooms while enforcing enrollment, department, room, and time constraints
* Implemented a DSATUR graph-coloring engine that generates conflict-free exam schedules in under two minutes
* Developed production deployment workflows using Docker, GitHub Actions, AWS ECS Fargate, RDS, and S3

### 📊 [Breast Cancer Classification Experiment Framework](https://github.com/JoePortas05/Breast_Cancer_Classification_Experiment_Runner) *(May 2025 – Sep 2026)*

* Automated the comparison of 119 model and preprocessing configurations using identical five-fold stratified splits, enabling consistent model selection by validation ROC-AUC
* Reworked the evaluation pipeline to fit preprocessing and feature selection entirely within training folds and select configurations before test evaluation, preventing data leakage and test-driven model ranking
* Implemented custom scikit-learn-compatible versions of Logistic Regression, Ridge Logistic Regression, Gaussian Naive Bayes, and k-NN
* Exported fold-level scores, dataset hashes, split indices, and dependency versions for reproducible, auditable comparisons, with automated regression checks through GitHub Actions

### 💻 [Functional Core Compiler](https://github.com/JoePortas05/Functional-Core-Compiler) *(Mar 2025)*

* Implemented a compiler for an extended functional programming language in Racket, translating parsed AST expressions into executable closures with lexical scoping, first-class functions, conditionals, recursion, mutation, and multi-expression function bodies
* Optimized execution by resolving variable bindings at compile time using de Bruijn-style environment indexes and global-binding inlining, reducing repeated runtime environment traversal
* Extended the runtime with mutable storage, by-reference function calls, recursive definitions, error handling, and semantic tests covering closures, mutation, recursion, shadowing, and invalid programs

### 📂 File System *(Nov 2024 – Dec 2024)*

* Built a FUSE-based file system in C supporting create, read, write, delete, rename, `mkdir`, and `rmdir` operations
* Implemented block allocation, inode metadata, directory traversal, and disk-space management to support reliable storage of files up to 500 KB
* Tested command-line behavior and edge cases, improving correctness across path handling, file updates, and storage limits

---

## 🔗 Let's Connect!

I'm open to opportunities in software engineering, research engineering, AI evaluation, and technical AI safety.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://linkedin.com/in/joseph-portas/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge\&logo=gmail\&logoColor=white)](mailto:joeportas05@gmail.com)
