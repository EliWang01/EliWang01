# Yu WANG

I work on LLM agents, long-term memory, and AI security. My current research focuses on systems that can reason over evolving information, decide when to act through tools, and remain robust when safety mechanisms face adaptive pressure.

I am an MSc Data Science student at City University of Hong Kong, with a background in statistics and research engineering.

## Research Interests

- Long-term conversational memory and temporal evidence graphs
- LLM agents, tool use, and irreversible action governance
- AI safety, guardrail evaluation, and adaptive robustness
- Retrieval-augmented reasoning, graph-based context assembly, and evaluation methodology

## Selected Work

### Long-Term Conversational Memory

I build memory and retrieval systems for question answering over evolving dialogue histories. The work combines temporal validity, graph-structured evidence, and query-time context assembly to help models reason over facts that may change, expire, or contradict earlier states.

Highlights:

- Modeled conversation histories as multi-granularity evidence structures over events, sessions, and topics.
- Used typed temporal, update, and contradiction links to discount stale evidence during retrieval.
- Built offline-online pipelines for memory construction, graph building, path search, context assembly, and answer generation.
- Evaluated long-conversation QA behavior with ablations over graph evidence, hierarchy, and query-adaptive prompting.

Core stack: `Python`, `NetworkX`, `sentence-transformers`, `OpenAI-compatible APIs`, `LLM-as-a-judge evaluation`

### Irreversible Tool-Use Governance

I study no-retraining governance methods for stateful tool-use agents that must decide whether to commit irreversible actions. The work uses action reversibility, uncertainty estimation, and value-of-information reasoning to decide when an agent should probe, commit, or abstain under deadline pressure.

Highlights:

- Implemented a reversibility gate for tool calls with conservative handling of unknown tools.
- Built uncertainty estimation with self-consistency sampling and posterior smoothing.
- Implemented probe valuation and a deadline-aware controller for irreversible action boundaries.
- Developed an evaluation framework for comparing tool-use governance policies under controlled conditions.

Core stack: `Python`, `Anthropic/OpenAI function-calling APIs`, `tau-bench`, `AppWorld`, `YAML tool metadata`

### Adaptive Evaluation of Agent Guards

I evaluate whether external agent guards remain reliable when attackers know the guard exists and adapt against it. The work treats guards as compression mechanisms over screenshots, activations, or trajectories, then evaluates matched adaptive attacks under a fixed protocol.

Highlights:

- Reproduced visual, activation-level, and trajectory-level guard operating points.
- Built a shared adaptive-evaluation harness with seeded logging, bootstrap confidence intervals, benign FPR measurement, and joint-objective reporting.
- Studied matched attacks across visual, activation-level, and trajectory-level guard signals.
- Tested a lightweight defense against a recency-bias failure mode in trajectory-level guarding.

Core stack: `Python`, `PyTorch`, `Hugging Face Transformers`, `OpenCV`, `Tesseract OCR`, `scikit-learn`

## Toolbox

`Python` | `C` | `C++` | `PyTorch` | `NetworkX` | `Hugging Face Transformers` | `OpenAI/Anthropic APIs` | `OpenCV` | `Tesseract OCR` | `Stata`

## Education Background

- MSc in Data Science, City University of Hong Kong
- BMgt in Accounting, Northwestern Polytechnical University

## Contact

- Email: [wangyu6-c@my.cityu.edu.hk](mailto:wangyu6-c@my.cityu.edu.hk)
- Personal email: [Eliwang2001@Outlook.com](mailto:Eliwang2001@Outlook.com)
