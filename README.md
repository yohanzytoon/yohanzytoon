# Yohan Zytoon

Applied AI / ML Engineer at Intact Financial, where I build production LLM agent workflows and evaluation systems. I study computer science at Université de Montréal (B.Sc. expected December 2026), with a focus on research engineering and ML systems.

## Current focus

- Production agents: retrieval, tool use, and stateful workflows
- Evaluation: reproducible experiments, structured-output quality, run-to-run stability, and failure analysis
- Research engineering: probabilistic ML, active learning, and optimization under limited compute or query budgets

## Selected projects

### [VeroLoop](https://yohanzytoon.com/projects/veroloop)

A provider-neutral framework for evaluating structured AI tasks across model candidates. It supports typed outputs, correctness and schema metrics, repeated-run stability, latency and cost measurement, asynchronous execution, retries, normalized errors, and MLflow reporting.

### [GFN-AL](https://github.com/yohanzytoon/GFN-AL)

Research on combinatorial search over an approximately 8-billion-state space with a 1,000-query oracle budget. Compares Gaussian Process + UCB active learning, a direct GFlowNet baseline, and a hybrid approach using PyTorch, BoTorch, GPyTorch, and Hydra, with multi-seed evaluation. Across five-seed experiments, classical active learning achieved 3.7× the valid-generation rate of direct GFlowNet training.

### [LOBSimulator](https://github.com/yohanzytoon/LOBSimulater)

A C++17 limit-order-book and matching-engine project with price-time priority, memory pooling, event-driven backtesting, Python bindings, and latency/throughput benchmarks.

## Next systems project

I’m exploring LLM inference and serving for open-weight models: asynchronous scheduling, continuous batching, KV-cache behavior, token streaming, backpressure, and latency/throughput trade-offs.

## Links

[Website](https://yohanzytoon.com) · [LinkedIn](https://linkedin.com/in/yohanzytoon) · [Email](mailto:yohanze@icloud.com) · [CV](https://yohanzytoon.com/files/cv_yohan_zytoon.pdf)
