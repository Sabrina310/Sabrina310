# Hi, I’m Ruohan Sun 👋

I build reliable, human-in-the-loop AI agent products, backed by a foundation in statistics, applied machine learning, and data systems.

I’m a Statistics graduate from the University of British Columbia. My work focuses on connecting model capabilities with real user workflows—from requirements and agent design to full-stack implementation, evaluation, and safety boundaries.

I’m especially interested in AI systems that are useful in practice: systems that handle uncertainty, expose their reasoning and constraints, require confirmation before consequential actions, and remain reliable when external services fail.

## 🚀 Featured Project

### [Spatiotemporal Planning Agent](https://github.com/Sabrina310/spatiotemporal-planning-agent)

An approval-gated AI planning system that turns natural-language goals into reviewable schedules and writes to the authoritative calendar only after explicit user confirmation.

![Spatiotemporal Planning Agent](https://raw.githubusercontent.com/Sabrina310/spatiotemporal-planning-agent/main/artifacts/calendar-week-desktop.png)

The project is a runnable full-stack product rather than a single-page concept demo. It includes a responsive web application, API services, an agent workflow, database migrations, background jobs, external-service adapters, technical documentation, and automated quality checks.

**Key capabilities**

- Extracts goals, fixed events, deadlines, locations, estimates, and missing information from natural-language input
- Separates structured understanding, schedule candidates, and authoritative calendar data
- Requires explicit confirmation for every calendar create, update, delete, and replan operation
- Supports constraint-aware scheduling, execution feedback, conflict detection, and whole-plan replanning
- Integrates place search, route comparison, travel buffers, and spatial reachability checks
- Models long-term goals, milestones, projects, tasks, dependencies, capacity, and rolling planning horizons
- Generates proactive suggestions without allowing background jobs to modify the calendar autonomously
- Uses idempotency keys, optimistic versions, audit records, encrypted fields, and transactional background workflows

**Technology**

`Next.js` · `React` · `TypeScript` · `FastAPI` · `Python` · `LangGraph` · `PostgreSQL` · `SQLAlchemy` · `Alembic` · `OR-Tools`

**Engineering evidence**

- 158 automated API tests
- ESLint and TypeScript validation
- Ruff and mypy static analysis
- Automated GitHub Actions checks
- Product requirements, acceptance scenarios, and technical design documentation
- Public-repository safety checks for credentials and oversized files

[View the repository →](https://github.com/Sabrina310/spatiotemporal-planning-agent)

## 🛠️ Skills

### AI and Agent Engineering

- Agent workflow and tool design
- Human-in-the-loop approval flows
- Prompt and structured-output design
- Model-provider integration and fallback handling
- Deterministic guardrails and constraint validation
- Agent evaluation and failure analysis

### Product and System Design

- Requirements definition
- User-flow and interaction design
- Product acceptance criteria
- API and data-contract design
- Safety, privacy, and permission boundaries
- Translating user needs into technical specifications

### Software and Data Systems

- Python, SQL, TypeScript, Java, and R
- FastAPI, Next.js, React, and Pydantic
- PostgreSQL, Oracle SQL, and MongoDB
- SQLAlchemy, Alembic, Git, and GitHub Actions
- Jupyter Notebook and R Markdown

### Statistics and Machine Learning

- Statistical learning and regression
- Regularization and model selection
- Bayesian modeling and hierarchical models
- MCMC and variational inference
- Experimental design and hypothesis testing
- Time-series analysis and uncertainty communication

## 📂 Selected Data and Statistical Projects

### 🏠 [Bayesian House Price Modeling](https://github.com/HaoyuYou/Bayesian-Statistics-Project)

Studied uncertainty in house-price modeling using Bayesian Gaussian regression on the Ames Housing dataset. The project compares Hamiltonian Monte Carlo with mean-field variational inference and specifies a hierarchical extension for neighborhood-level variation.

My contributions included developing the hierarchical model, interpreting the inference comparison, and writing the final report.

**Methods and tools:** R, Stan, CmdStanR, MCMC, variational inference, hierarchical modeling, and posterior predictive checks

---

### 🎬 [Movie Ratings Across IMDb, Rotten Tomatoes & the Oscars](https://github.com/Sabrina310/movie-ratings-analysis)

Integrated IMDb, Rotten Tomatoes, and Academy Awards data to examine relationships among audience ratings, critic scores, popularity, genre, and Oscar recognition for films released between 2016 and 2025.

The project demonstrates relational database design, cross-source data matching, SQL queries, MongoDB aggregation pipelines, reproducible analysis, and careful interpretation of observational results.

**Methods and tools:** Python, Oracle SQL, MongoDB, data integration, record matching, aggregation pipelines, and visualization

---

### 👥 [Employee Attrition Prediction](https://github.com/Sabrina310/Stat301-Group26)

Investigated employee attrition patterns and developed predictive models using logistic regression and Lasso regularization. The analysis examined factors including salary tier, tenure, and time spent without an assigned project.

**Methods and tools:** R, logistic regression, Lasso, cross-validation, feature selection, ggplot2, and glmnet

---

### 🩺 [Colorectal Cancer Mortality Analysis](https://github.com/justinyyl/Colorectal_Cancer_Mortality_Canada)

Examined associations between healthcare costs, early detection, and colorectal cancer mortality in a Canadian subset of an international dataset.

The project used logistic regression, AIC-based feature selection, and likelihood-ratio testing while explicitly considering the limitations of observational data and avoiding unsupported causal conclusions.

**Methods and tools:** R, statistical inference, logistic regression, feature selection, hypothesis testing, and data visualization

> The academic projects above were completed collaboratively. Team credits, methodological details, limitations, and available contribution records are included in the linked repositories.

## 🔭 Current Focus

- Building reliable AI agents with explicit permission and confirmation boundaries
- Designing evaluation methods for agent behavior and generated outputs
- Connecting statistical reasoning with AI product decisions
- Improving full-stack implementation across models, APIs, data, and user interfaces
- Exploring practical approaches to long-horizon planning and human–AI collaboration

## 🌱 Interests

- AI agents and agentic workflows
- Human-centered AI product design
- Reliable evaluation of AI system outputs
- Statistical learning and probabilistic reasoning
- Responsible use of data and uncertainty
- Translating technical capabilities into useful product experiences
