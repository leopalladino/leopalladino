# Leonardo Victor Palladino

Data scientist working on credit risk and LLM systems at AMPF, a mutual aid association in Argentina. I build the models that decide who gets a loan, and evaluate the LLM chatbots that talk to our members on WhatsApp.

### Selected work

Most of it is private, built for AMPF and for clients.

- **Credit risk (AMPF):** found look-ahead leakage in the legacy credit model (its reported AUC of 0.79 was really 0.75), then built an explainable points scorecard that beats the production score on a sealed holdout (AUC 0.74 vs 0.57).
- **Credit policy (AMPF):** backtested a 95%-approval cut-off that declines loans defaulting at nearly 2x the rate of the current score's cut, with no delegation below the four-fifths fairness rule.
- **LLM evaluation (AMPF):** validated an LLM judge against a labeled set (κ 0.86) and built a replay harness on 250 real takeovers that blocked releases misrouting urgent chats. A fine-tuned 300M encoder beats the GPT-4o-mini intent router (87.7% vs 83.0%) at 9x lower latency.
- **SetterAI:** agentic CRM for Instagram DMs, where each sales chat is a state machine of LLM-gated steps (+25% step conversion) with an LLM-as-judge veto (−40% human handoffs).
- **[ammegtech.com](https://ammegtech.com):** generative AI SaaS that turns garment photos into studio-quality catalog shots, with 68% fewer garment distortions from a background-removal pass before diffusion.

The public repos below are computer vision projects from university.

Python · SQL · Scikit-learn · Gradient Boosting · Scorecards · Statistics · PostgreSQL · Oracle (PL/SQL) · pgvector · OpenAI API · Langfuse · FastAPI

[CV (PDF)](https://github.com/leopalladino/cv/raw/main/CV_Leonardo_Victor_Palladino.pdf) · [LinkedIn](https://www.linkedin.com/in/lvpalladino)
