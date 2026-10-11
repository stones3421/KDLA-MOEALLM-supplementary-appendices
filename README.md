# Supplementary Appendices for KDLA-MOEALLM

This repository contains the consolidated supplementary material for the manuscript on integrated freight train line planning and timetabling with Virtual Formation Management (VFM). The appendices support the mathematical formulation, exact-solver validation, VFM event records, corridor data, and experimental analysis.

## Repository contents

| File | Description |
|---|---|
| `Appendix.tex` | Consolidated LaTeX source for Appendices A-G. |
| `Appendix.pdf` | Compiled PDF of the consolidated appendices. |
| `README.md` | Repository overview and compilation instructions. |

## Appendix structure

- **Appendix A:** Complete linearization details.
- **Appendix B:** Exact-solver validation data.
- **Appendix C:** VFM event sequence example.
- **Appendix D:** Notation and units.
- **Appendix E:** Corridor data and OD matrix.
- **Appendix F:** VFM event-level evidence.
- **Appendix G:** Supplementary statistical and computational results.

## Requirements

- TeX Live 2024 or later is recommended.
- The following LaTeX packages are required: `geometry`, `amsmath`, `amssymb`, `graphicx`, `booktabs`, `array`, `longtable`, `placeins`, and `hyperref`.
- No bibliography database is required to compile the appendix source.

## Compilation

Run the following commands from this directory:

```bash
pdflatex -interaction=nonstopmode -halt-on-error Appendix.tex
pdflatex -interaction=nonstopmode -halt-on-error Appendix.tex
```

The source is compiled twice so that all table, equation, section, and internal references are stable. The compiled PDF is available as `Appendix.pdf`.

## Data and code availability

This repository publicly provides the consolidated supplementary appendices in `Appendix.tex` and `Appendix.pdf`. The complete machine-readable fleet file, full OD matrix, benchmark instance files, random seeds, and experiment scripts are not included in this repository.

Researchers may request these materials from the corresponding author for legitimate academic and research purposes. Requests should briefly state the intended use, institutional affiliation, and contact information. Materials will be shared subject to institutional data-use restrictions and the data-sharing policy of the journal.

## License

No open-source license is granted unless a separate `LICENSE` file is added. The manuscript, appendices, figures, and tables are provided for academic reading, peer review, and citation.

## Citation

When the manuscript is published, cite the journal article using its final DOI and bibliographic information. A `CITATION.cff` file can be added after the DOI is available.

## Contact

For questions about the repository or the supplementary material, contact the corresponding author listed in the manuscript.
