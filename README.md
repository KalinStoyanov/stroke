# Hybrid Neurovascular Model for Ischemia-Constrained Computation

**Target journal:** JMLR  
This repo contains the paper and code for a stress-sensitive vascular model
coupled to **pretrained, frozen** neural networks. Neuron outputs are modulated
as whole units by local perfusion $\widehat{S}(v,t)$ (vessel size enters through $\widehat{S}$).
**No Hebbian/plasticity terms** are used in this article.

## Layout
- `paper/` — LaTeX source (`NN_stroke_article_14_8_2_JMLR.tex`, `NN_stroke.bib`)
- `src/` — vascular graph + stress-driven dynamics; coupling gate `g(S)`
- `configs/`, `scripts/`, `results/` — experiments and summaries

## Reproduce paper PDF
The repo builds the PDF via GitHub Actions; artifacts appear in the Actions tab.
