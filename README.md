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
* [awesome-marketing-datascience Open LLM Models List](https://github.com/underlines/awesome-marketing-datascience/blob/master/llm-model-list.md)

## Evals
* [HuggingFace Open LLM Leaderboard](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard)
    * warning, their MMLU results are wrong, throwing off the whole ranking: https://twitter.com/Francis_YAO_/status/1666833311279517696
* [LMSys Chatbot Arena Leaderboard](https://chat.lmsys.org/?leaderboard) - ELO style ranking
* [LLM-Leaderboard](https://llm-leaderboard.streamlit.app/)
* [Gotzmann LLM Score v2](https://docs.google.com/spreadsheets/d/1ikqqIaptv2P4_15Ytzro46YysCldKY7Ub2wcX5H1jCQ/edit#gid=0) ([discussion](https://www.reddit.com/r/LocalLLaMA/comments/13wvd0j/llm_score_v2_modern_models_tested_by_human/))
* [Chain-of-Thought Hub](https://github.com/FranxYao/chain-of-thought-hub)
* [C-Eval Leaderboard](https://cevalbenchmark.com/static/leaderboard.html)
* [llm-humaneval-benchmarks](https://github.com/my-other-github-account/llm-humaneval-benchmarks) - HuggingFace models evald vs HumanEval+
* [CanAiCode Leaderboard](https://huggingface.co/spaces/mike-ravkine/can-ai-code-results) - using [Can AI Code? eval](https://github.com/the-crypt-keeper/can-ai-code)
* [AlpacaEval Leaderboard](https://tatsu-lab.github.io/alpaca_eval/)
* [YearZero's LLM Logic Tests](https://docs.google.com/spreadsheets/d/1NgHDxbVWJFolq8bLvLkuPWKC7i_R6I6W/edit#gid=1278290632)
* [HELM Core Scenarios](https://crfm.stanford.edu/helm/latest/?group=core_scenarios)
* [TextSynth Server](https://bellard.org/ts_server/)
* [airate](https://github.com/catid/supercharger/tree/main/airate) - C++ bug catching test
* [llm-jeopardy](https://github.com/aigoopy/llm-jeopardy) - automated quiz show answering

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
