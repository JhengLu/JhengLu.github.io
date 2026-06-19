---
title: "Beyond Domains: Reusing Web Skills via Transferable Interaction Patterns"
excerpt: "Shiqi He, Yue Cui, Feijie Wu, Xinyu Ma, <strong>Jiaheng Lu</strong>, Yaliang Li, Bolin Ding, Mosharaf Chowdhury.
<br>In submission to <em><strong>NeurIPS</strong></em>, 2026
<br>[<a href=''>Paper</a>], [<a href=''>Code</a>]"
collection: publications
---

<h2>Abstract</h2>
Large language model (LLM) web agents are usually deployed as tool callers: each turn, the model reads a fresh page observation and emits one structured tool action. When every action is a low-level primitive, horizons grow quickly and so do policy-facing LLM completions, dominating latency and cost on benchmarks such as Mind2Web and WebArena. Recent systems therefore wrap repeated interaction fragments as web skills: callable tools built from successful trajectories or induced programs, so one call can replace several primitives. However, prior skill libraries are still triggered mainly by instruction similarity or coarse site metadata, which yields low skill reuse on held-out sites and leaves much of the potential step and token reduction on the table.

We present SkillMigrator, an agent that learns reusable web skills and transfers them across sites by matching layout structure rather than specific element references. Each induced skill is stored as a transferable interaction pattern (TIP): the skill paired with a structural sketch of the snapshot at induction time. At test time, SkillMigrator retrieves TIPs by layout similarity and grounds their references on the live page. The rest of the stack is standard: accessibility-snapshot observations with stable references, and fixed tool calling over primitives plus skill invocations. Compared with the state-of-the-art approaches, SkillMigrator reduces the average LLM-action count on successful trajectories by 8–10% across both WebArena and Mind2Web at matched success rate.
