# PRD manuscript

The current manuscript leads with the all-hadronic top-pair plus missing-transverse-momentum analysis. The LZ reference-yield matching and Planck abundance select the physical on-shell grid. Its simplified 15-bin likelihood gives median expected limits below unity at 381 of 470 retained points. These are expected sensitivity estimates under the stated post-fit background approximation.

`main.tex` contains the model, recoil and abundance conditions, top-pair simulation, expected limits, stability tests, and conclusions. The four `figures/fig*_v10.png` files show the primary top-pair results. `appendices.tex` contains the compressed monojet analysis and validation (Appendix A), photon matching and late-state assumptions (B), and off-shell and single-top checks (C). The monojet observed limits remain in Appendix A; no joint collider likelihood is claimed.

The text follows the 26 November 2026 Markdown revision in the [analysis repository](https://github.com/Jim11451/lz_paper), under `ttbar_paper_update_20261126/`. The top-pair and monojet grids retain their separate scan bounds and recoil prescriptions. This update changes the presentation and adds the supplied top-pair results without generating new numerical samples.

In Overleaf, set `main.tex` as the main document and select **pdfLaTeX**. The project uses REVTeX 4.2, AMS math, graphicx, hyperref, and BibTeX. A local TeX Live installation can build it with `latexmk -pdf main.tex`. All referenced figures and `references.bib` are included.

When using Overleaf's GitHub integration, pull changes from this repository into the existing project and recompile. GitHub and Overleaf synchronization is a separate operation from pushing a Git commit.
