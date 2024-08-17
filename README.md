This is a modified cellchat package to adapt to shiny apps deployed in shinyapps.io. The changes has not been thoroughly tested.

Key modifications:
1. Deleted header files (*.o and *.so) in src/ to avoid installation issues.
2. Modified data.smooth slot for compatibility.
3. Removed automatic plot titles, including: chord plot, aggregated circle plot, heatmap. Now you need to explicitly specify title.name or signaling.name to display a title.

For documentation, please refer to the original package.

References: 
- [Suoqin Jin et al., CellChat for systematic analysis of cell-cell communication from single-cell and spatially resolved transcriptomics, bioRxiv 2023](https://biorxiv.org/cgi/content/short/2023.11.05.565674v1) [CellChat v2]
- [Suoqin Jin et al., Inference and analysis of cell-cell communication using CellChat, Nature Communications 2021](https://www.nature.com/articles/s41467-021-21246-9) [CellChat v1]





