# Martin Blomqvist

AI Engineer in Kristianstad, Sweden. I build agent pipelines and machine learning
systems in Python, usually from scratch: hand-rolled async orchestration in
preference to a framework, unless the framework solves a hard problem better than I
can (see Prasine Index, where LangGraph earns its place).

Finishing a Data Science degree at EC Utbildning in May 2026. Open to roles.

## Projects

**[Maktspråk](https://github.com/MartinBlomqvistDev/maktsprak)** · [maktsprak.se](https://maktsprak.se)

Predicts which Swedish party wrote a parliamentary speech. Fine-tuned KB-BERT at
0.628 accuracy and 0.619 macro-F1, evaluated on 146 speakers held out of training,
served from FastAPI on Cloud Run over a 75,148-speech Riksdag corpus that rebuilds
from source. The site carries a study that turns the classifier into an instrument:
which party do fourteen frontier language models write like?

**[Prasine Index](https://github.com/MartinBlomqvistDev/prasine-index)** · [prasineindex.com](https://prasineindex.com)

Seven-agent pipeline that checks EU corporate sustainability claims against 22 open
datasets and returns a scored evidence chain. Anthropic SDK and LangGraph.

**[GALDR](https://github.com/MartinBlomqvistDev/galdr-engine)**

Async AI orchestration for interactive storytelling, built without LangChain.
Deterministic game logic decides what happens; the LLM only narrates it. Voice
benchmark: 2.0s TTFA p50 over 46 runs, too slow for conversational turn-taking.
182 tests.

**[Site Sentinel](https://github.com/MartinBlomqvistDev/site-sentinel)**

Near-miss prediction for road construction zones. Random Forest at F1 0.927,
benchmarked against XGBoost, LSTM and TCN. Numbered pipeline, 01 to 06.

## Elsewhere

- [Hugging Face](https://huggingface.co/MartinBlomqvist): models and datasets
- [LinkedIn](https://www.linkedin.com/in/martin-blomqvist/)
- cm.blomqvist@gmail.com
