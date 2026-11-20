<div align="center">

# Kuldeep

**Machine Learning Engineer · MLOps**

I build the unglamorous half of machine learning — the parts that decide whether a
model ever survives contact with production. Reproducible pipelines, calibrated
probabilities, typed inference APIs, and monitoring that actually catches drift.

[Python](https://www.python.org/) · [FastAPI](https://fastapi.tiangolo.com/) · [DVC](https://dvc.org/) · [MLflow](https://mlflow.org/) · [Docker](https://www.docker.com/) · [GitHub Actions](https://github.com/features/actions)

</div>

---

## What I do

- **Take models from notebook to production.** Versioned data, parameterized pipelines, and one-command reproduction — no "it worked on my machine."
- **Optimize for the decision, not the metric.** Cost-based thresholds, probability calibration, and business impact over a vanity accuracy number.
- **Make systems legible.** Typed APIs, documented tradeoffs, real tests, and interfaces that explain *why* a prediction was made.
- **Design for failure.** Drift detection, reproducible CI, and quality gates that stop a bad model before it ships.

## Selected work

### [churn-mlops](https://github.com/Kuldeepni/churn-mlops) — end-to-end churn prediction

A full MLOps case study on the IBM Telco dataset: DVC-orchestrated stages, Pandera validation,
model selection (logistic regression vs. tuned LightGBM), isotonic calibration, profit-based
threshold optimization, SHAP explanations, a FastAPI service, and PSI drift monitoring.
The front end is a live consumer of the exported pipeline artifacts — not a mockup.

- **Live site:** [The Churn Ledger](https://kuldeepni.github.io/churn-mlops/) · **API:** [docs](https://kuldeepni-churn-mlops-api.hf.space/docs)
- **Measured:** PR-AUC 0.636 · ROC-AUC 0.846 · 88.8% recall at the deployed 0.18 cutoff · 30 tests / ~70% coverage
- **Stack:** Python, DVC, MLflow, FastAPI, React/Vite, Docker, GitHub Actions, Hugging Face Spaces

### [chrome-agent](https://github.com/Kuldeepni/chrome-agent) — browser automation over CDP

A local MCP server that lets an AI agent drive a real, already-logged-in Chrome browser through
the DevTools Protocol. 25 tools for navigation, tab management, page reading, interaction,
downloads, and opt-in JavaScript — reusing your existing session instead of spinning up a
separate automation browser.

- **Stack:** Python 3.11, `mcp` SDK (stdio), Playwright, Windows + macOS

## Toolbelt

| Area | Tools |
| --- | --- |
| Languages | Python, TypeScript/JavaScript, SQL, Bash/PowerShell |
| ML | scikit-learn, LightGBM, Pandas, NumPy, SHAP, calibration & drift analysis |
| MLOps | DVC, MLflow, Docker, GitHub Actions, Hugging Face Spaces, GitHub Pages |
| Serving | FastAPI, Pydantic, React, Vite |
| Practices | Reproducible pipelines, CI/CD, test matrices, data validation, model monitoring |

## How I work

> A model is only as good as the system around it. I care about the data contract, the
> reproducible run, the honest evaluation, and the interface that lets someone trust the
> output — not just the notebook that produced the number.

- Small, reviewable commits with messages that explain *why*.
- Decisions backed by measured results and explicit tradeoffs.
- Documentation written for the person who inherits the repo.

---

<p align="center">
  <a href="https://github.com/Kuldeepni">GitHub</a> ·
  <a href="https://kuldeepni.github.io/churn-mlops/">Portfolio / Live project</a>
</p>
