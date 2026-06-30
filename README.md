# G-Locked Panorama Stabilization — Paper

LaTeX source for the IEEE Transactions manuscript
*"G-Locked Panorama Stabilization: A Streaming IMU-Locked Algorithm for Real-Time
Cylindrical Panorama Stabilization and FPGA-Oriented Deployment."*

## Building

- **Overleaf:** import this repository (Menu → Git) or upload its contents. The main
  document is `g_locked_panorama_stabilization.tex` (IEEEtran journal class).
- **Local:** `pdflatex` → `bibtex` → `pdflatex` → `pdflatex` on
  `g_locked_panorama_stabilization.tex`.

## Layout

- `g_locked_panorama_stabilization.tex` — manuscript (IEEEtran journal class).
- `g_locked_panorama_stabilization.bib` — bibliography.
- `figures/` — result images. The four schematic figures (problem geometry, pipeline,
  RowRun scheduling, memory dataflow) are drawn as native TikZ inside the `.tex`.

Build artifacts (`.aux`, `.bbl`, `.log`, the compiled `.pdf`, etc.) are git-ignored.

Authors: Muhammad Awais, Youngbae Hwang (Chungbuk National University).
