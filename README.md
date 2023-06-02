# llm-tracker
(placeholder name)

A framework for tracking AI large language model (LLM) foundational models, fine tunes, data sets, and evals.

# Existing Projects

## Project Lists
* [lhl's LLM Worksheet](https://docs.google.com/spreadsheets/d/1kT4or6b0Fedd-W_jMwYpb63e1ZR3aePczz3zlbJW-Y4/edit#gid=741531996)
* [CRFM Helm](https://crfm.stanford.edu/helm/)
* [CRFM Ecosystem Graphs](https://crfm.stanford.edu/ecosystem-graphs/)
* [Open LLMs](https://crfm.stanford.edu/ecosystem-graphs/)
* [Viktor Garske's AI / ML / LLM / Transformer Models Timeline and List](https://ai.v-gar.de/ml/transformer/timeline/)

## Evals
* [HuggingFace Open LLM Leaderboard](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard)
* [LMSys Chatbot Arena Leaderboard](https://chat.lmsys.org/?leaderboard)
* [LLM-Leaderboard](https://llm-leaderboard.streamlit.app/)
* [Gotzmann LLM Score v2](https://docs.google.com/spreadsheets/d/1ikqqIaptv2P4_15Ytzro46YysCldKY7Ub2wcX5H1jCQ/edit#gid=0) ([discussion](https://www.reddit.com/r/LocalLLaMA/comments/13wvd0j/llm_score_v2_modern_models_tested_by_human/))
* [Chain-of-Thought Hub](https://github.com/FranxYao/chain-of-thought-hub)


# Roadmap
Single open, comprehensive repository that is a superset of existing lists, and that allows for low friction submissions, updates, collaboration.

## p1
* FastAPI API for queries
* Permissive (CC0?) data set available as YAML, Datasette, etc
* Robust/extensible/historical data model:
  * Entities/Organizations
  * Models (foundational, fine tunes)
  * Versions (sizes, checkpoints, quantizes)
  * Evals (repeatable benchmark, rankings, contributions)
* Allow submissions (rollbacks, updates) via either GH pull requests or just a GH/HF Auth workflow

## p2
* Figure out importing, sourcing evals
* Tracking submissions by date
* Custom views

## Maintenance
* Live w/ CRFM (or LMSys or other long-running org?)
* Should have community Discord
* Be welcoming of all contributors
