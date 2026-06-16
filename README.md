<div align="center">

<img src="./assets/mesh-banner.svg" alt="MESH — A Token-Efficient, Graph-Native Logic for Repository-Scale Code Agents" width="100%">

<br><br>

<a href="https://try-mesh.com"><img src="https://img.shields.io/badge/web-try--mesh.com-06b6d4?style=for-the-badge&labelColor=0b0b0c" alt="Website"></a>
&nbsp;<img src="https://img.shields.io/badge/paper-working%20draft-22d3ee?style=for-the-badge&labelColor=0b0b0c" alt="Working draft">
&nbsp;<img src="https://img.shields.io/badge/June-2026-3f3f46?style=for-the-badge&labelColor=0b0b0c" alt="June 2026">

<h3>A Token-Efficient, Graph-Native Logic for Repository-Scale Code Agents</h3>

<p><em>Most of a coding agent's token budget goes to <b>finding</b> the right code, not reasoning about it.<br>Mesh is a pre-inference control plane that assembles budgeted, cited evidence before every model turn.</em></p>

</div>

---

## 📄 The paper

> [!NOTE]
> The PDF links below are placeholders — drop your hosted URLs into the **Read** column (replace the `#`).

| Edition | Pages | What's inside | Read |
|---|:--:|---|:--:|
| **Full working draft** | 61 | The complete paper — every section, references, and appendices | [PDF&nbsp;↗](#) |
| **Main text** | 54 | Content only — §1–§18, references &amp; appendices removed | [PDF&nbsp;↗](#) |
| **Condensed edition** | 22 | The ~20-page highlights — core architecture + results | [PDF&nbsp;↗](#) |
| **Outreach summary** | 2 | One-glance teaser + the headline result | [PDF&nbsp;↗](#) |
| **References &amp; appendices** | 8 | Companion volume — bibliography + Appendix&nbsp;A–F | [PDF&nbsp;↗](#) |

<div align="center"><sub>New here? Start with the <b>Outreach summary</b> (2 min) or the <b>Condensed edition</b> (~20 min).</sub></div>

---

## Why Mesh

<table>
<tr>
<td width="33%" valign="top">

### 🎯 Better localization

**Hit@1 79.9%** on a 229-task suite across six external repositories — **2.4×** the strongest single-method retrieval baseline (McNemar&nbsp;p&lt;0.001).

</td>
<td width="33%" valign="top">

### 💸 Fewer tokens

**−69.7%** per query and **−55.5%** over multi-turn sessions versus a competent grep agent — same model, only the scaffold changes.

</td>
<td width="33%" valign="top">

### 🕸️ Graph-native

A deterministic **Repository Intelligence Graph** answers symbol-aware lookup and dependency-impact queries that embeddings and grep structurally can't.

</td>
</tr>
</table>

---

## What's inside

- **Part I — Foundations** · the lost-in-the-middle problem, the *locality unit*, and a constrained-utility model of the agent loop
- **Part II — Architecture** · five env-strippable layers — representation → evidence → context → economics → runtime
- **Part III — Evaluation** · retrieval ablation, needle-in-a-haystack, multi-turn economics, a controlled head-to-head against SOTA retrieval, and a same-model scaffold study
- **Part IV — Discussion** · comparison with alternative architectures, threats to validity, and limitations

---

<div align="center">
<sub><b>Mesh</b> &middot; <a href="https://try-mesh.com">try-mesh.com</a> &middot; Edgar Elmo Baumann &amp; Philipp Nils Horn &middot; June 2026</sub>
</div>
