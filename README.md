# Meridian Health LMS project plan

The editable report starts at `main.tex`. Its six numbered parts are in `parts/`;
all WBS, Gantt and risk figures are bundled in `figures/`. The report contains the
complete 54-package WBS dictionary as native LaTeX tables, with no external links
needed to read it.

All report pages use portrait orientation. Wide source grids are presented as
field/detail tables, retaining all fields and keeping each record together.
WBS and Gantt figures are embedded on portrait pages; vector chart details remain
sharp when zoomed.

Compile from this directory with either:

```sh
tectonic main.tex
```

or a standard LaTeX installation:

```sh
pdflatex main.tex
pdflatex main.tex
```

`VERIFICATION.md` records the source-content audit and the exemplar section map.
The complete PDF is `output/pdf/Meridian_Health_Project_Plan.pdf`. The portable
LaTeX archive contains `main.tex`, the six parts, all required figures, this guide,
and the verification record; it can be uploaded directly to Overleaf.

The authoring workspace also retains Drive snapshots and conversion/audit scripts
locally. Those working files are not required to compile or edit the shared report;
the published project contains the complete LaTeX content and required figures.

The historical inconsistency-review tabs are not part of the submission. The
current main plan retains its explicit approval, staffing, funding, effort and
schedule-calculation limits.
