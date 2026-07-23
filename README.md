# Riyad Mehdiyev

### Prediction is usually where the interesting part starts.

If an outcome is likely, I want to know **when the evidence was valid, why the outcome may happen, which action could change it, and how certain we should be**.

I am a data scientist in Stockholm, currently at Kapital Bank. I build research prototypes and production software across causal inference, retrieval, language models, and decision support.

## Four questions I keep working on

<table>
<tr>
<td width="50%" valign="top">

<sub>01 / WHEN</sub>

### Can retrieval respect time?

[TemporalRAG-Lite](https://github.com/RiyadMehdi7/TemporalRAG-Lite) evaluates whether an answer uses evidence that was valid at the date in the question, rather than whatever is newest in the index.

`time-sliced corpora` `leakage metrics` `abstention`

</td>
<td width="50%" valign="top">

<sub>02 / WHY</sub>

### Can prediction lead to intervention?

[CHRONOS](https://github.com/RiyadMehdi7/CHRONOS) connects survival models with treatment-effect estimation and budget-constrained policy learning for employee retention.

`survival analysis` `CATE` `policy learning`

</td>
</tr>
<tr>
<td width="50%" valign="top">

<sub>03 / HOW SURE</sub>

### What is worth verifying?

[CRVerify-P](https://github.com/RiyadMehdi7/CRVerify-P) chooses which reasoning paths to inspect when verification has a cost, then stops when the top candidates are sufficiently separated.

`confidence bounds` `partial paths` `top-m selection`

</td>
<td width="50%" valign="top">

<sub>04 / TOGETHER</sub>

### Can coding agents share a repository safely?

[AgentSync MCP](https://github.com/RiyadMehdi7/agentsync) coordinates concurrent agents through file locks, active-work tracking, conflict detection, and merge assistance.

`MCP` `coordination` `developer tooling`

</td>
</tr>
</table>

## Experimental track

<table>
<tr>
<td width="43%" valign="top">

### [Cognitive LLM](https://github.com/RiyadMehdi7/cognitive-llm)

I added six independently toggleable, neuroscience-inspired modules around a frozen SmolLM-360M backbone and ran controlled ablations.

The useful result was not that every idea helped. **Homeostatic normalization accounted for most of the improvement; the per-layer critic consistently made performance worse.**

The repository contains the implementation, tests, experiment configuration, figures, and paper.

</td>
<td width="57%" valign="middle">

<a href="https://github.com/RiyadMehdi7/cognitive-llm">
  <img src="https://raw.githubusercontent.com/RiyadMehdi7/cognitive-llm/master/paper/figures/phase1_val_loss_ranking.png" alt="Cognitive LLM Phase 1 validation-loss ranking" width="100%" />
</a>

</td>
</tr>
</table>

## Working stack

`Python` · `PyTorch` · `scikit-learn` · `FastAPI` · `PostgreSQL` · `TypeScript` · `React` · `Docker`

I care about reproducible experiments, useful uncertainty estimates, and software that remains understandable after the prototype.

[LinkedIn](https://www.linkedin.com/in/riyad-mehdiyev/) · [Email](mailto:riyadmehdi17@gmail.com)
