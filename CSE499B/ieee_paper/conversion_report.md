# Thesis-to-IEEE Conversion Report

## Selection approach

The paper preserves the thesis's original sentences and shortens primarily by deletion and selection. Section order was changed to match a conventional IEEE research-paper narrative. LaTeX-only changes include citation commands, cross-references, mathematical typesetting, escaped percent signs, and en dashes represented by `--`.

The verified IEEE two-column build is 14 pages including figures, tables, and references. This is the closest coherent result to the approximately 15-page target without padding the paper with project-management or accreditation material.

## Major content removed

- Turnitin cover, integrity overview, letter of transmittal, approval, declaration, acknowledgements, contents, and lists of tables/figures.
- The report-organization subsection.
- Most broad or repeated background and repeated interpretations of the same results.
- Most deployment-interface implementation detail that did not affect the research results.
- Project planning, timeline, and budget chapter; only the directly relevant resource-optimization measures were retained.
- Complex Engineering Problems and Complex Engineering Activities accreditation matrices.
- Repeated conclusion/limitation paragraphs that restated earlier experiments.

## Figures retained

- Proposed lightweight latent diffusion inpainting architecture for Student A02.
- End-to-end deployment workflow for Student A02 and Stable Diffusion 2 comparison.
- Training and validation loss curves for CelebA inpainting variants.
- Performance comparison across FID, parameters, MACs, and validation loss.
- Student A02 training and validation loss curves.
- Student A02 qualitative mask/reconstruction examples.
- Student A02 and Stable Diffusion 2 qualitative comparison.

The Stable Diffusion 2 qualitative comparison is split into two consecutive three-row figures (Parts 1 and 2) so the images remain readable and appear with the comparison discussion rather than after the references.

## Figures removed

- Gantt chart of weekly project planning and development timeline.

## Tables retained

- CIFAR-10 ablation study results.
- Baseline vs depth-reduced comparison.
- Structured evaluation results.
- Inpainting model comparison.
- Student A02 final results.
- Student A02 vs Stable Diffusion 2.
- Software tools table.

## Tables removed
- Project timeline.
- Estimated project budget and resource usage.
- Complex Engineering Problems and Complex Engineering Activities matrices.

## Content not transferred exactly

- Word equation objects were reconstructed as LaTeX equations from the PDF because they were not available as editable paragraph text in the Word extraction. The symbols, constants, and mathematical meaning were preserved.
- Figure references were converted from thesis numbering to LaTeX labels so numbering remains correct after deletion.
- The thesis contains conflicting summary values (including 3 seconds versus 0.637 seconds for Student A02 inference and inconsistent parameter counts in later discussion). The paper keeps the detailed final-results tables and abstract values and deletes the conflicting restatements rather than rewriting them.
