# Operational JSON examples

The canonical examples are in
[RittgerLabGroup/spires-batch](https://github.com/RittgerLabGroup/spires-batch/tree/main/examples).
Use `workflow.json` and its `workflow.md` walkthrough for the complete five-tile
historical-to-NRT sequence, or the R0, historical-processing and interpolation
JSON templates with their accompanying Markdown walkthroughs.

`historical.json` runs matched reflectance/cloud preparation, spectral
unmixing, canopy adjustment and daily albedo. Date selection handles both short
pilots and full WYs; there is no separate raw-inversion tutorial. The batch
controller invokes this package's inversion API; this package does not directly
consume those JSON files.

The former Sentinel-2, optimizer, legacy-inversion and tree-inpainting notebooks
and their duplicate copies are no longer operations examples. They remain
recoverable from Git history. Scientific APIs and supported sensors are unchanged.
