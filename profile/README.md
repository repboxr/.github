# Repbox

The `repboxr` organisation mainly contains R packages for the *Repbox* project that shall facilitate reproducible research. (Unfornately `repbox` was already taken as an organisation name on Github. Since most of the code is in R, I picked `repboxr`.) The project currently concentrates on economics and social sciences.

Currently, all packages are in a pilot phase and the project needs substantial large scale testing, improvement and documentation. It still a long way to go. While currently almost all contributions are by Sebastian Kranz (Ulm University), the goals is that a stable version will have a wide community including ata editors, authors and researchers performing meta studies.

## Package overview

[repboxRun](https://github.com/repboxr/repboxRun): Functions that help running repbox analysis steps that are implmented in the different packages.

[repboxArt](https://github.com/repboxr/repboxRun): Analyse articles in PDF or HTML versions. Main elements:
  - Convert PDF or HTML to a common representation that stores text information including sections, paragraphs and footnote markers.
  - Extract and store scientific tables.
  - Analyse keywords, like `regression analys` and links to tables or figures in the text.  

