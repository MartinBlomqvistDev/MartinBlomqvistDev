# Martin Blomqvist

AI Engineer in Kristianstad, Sweden. I build agent pipelines and machine learning
systems in Python, usually from scratch: hand-rolled async orchestration in
preference to a framework, unless the framework solves a hard problem better than I
can (see Prasine Index, where LangGraph earns its place).

Data Science degree from EC Utbildning, June 2026. I run the consultancy Katt & Kod,
with two client engagements delivered and invoiced. Open to roles.

## Projects

**[Antumbra](https://github.com/MartinBlomqvistDev/antumbra)** · [antumbraprojektet.se](https://antumbraprojektet.se)

Measures whether Swedish animal welfare inspection is equivalent across counties.
43 freedom-of-information requests, each handled under a protocol written in advance.
The baseline is the European Commission's 4,690 audits of member state control
systems, parsed into a star schema with dbt on BigQuery and a retrieval layer that
answers only in verbatim quotations. 64.1 percent of the inspection reports released
carry a redaction, against 22.9 percent of the injunction decisions. The measure
separates only 39 of 136 county pairs, and that limit is published with the figure.
250 tests.

**[Hazium](https://github.com/MartinBlomqvistDev/hazium)** · [hazium.org](https://hazium.org)

EU pesticide regulatory risk from five public sources, built as a temporal knowledge
graph of 41,917 dated facts, so that a model at a past cutoff sees only what was
knowable then. The first version asked whether a substance had ever been withdrawn,
over a population that was 96 percent never approved, and ranking on approval age
alone matched it. Reformulated as discrete-time survival, the evidence lifts average
precision from 0.102 to 0.242, p = 0.024 on a block permutation. 415 tests.

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
benchmark: 2.7s input-to-first-audio p50, too slow for conversational turn-taking.
189 tests.

## Elsewhere

- [Hugging Face](https://huggingface.co/MartinBlomqvist): models and datasets
- [LinkedIn](https://www.linkedin.com/in/martin-blomqvist/)
- cm.blomqvist@gmail.com
