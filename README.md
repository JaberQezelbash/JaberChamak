# JaberChamak

Industry-facing portfolio website for **Jaber Chamak** — Healthcare Data Scientist / ML/AI Engineer.

This repository is designed to power a GitHub Pages portfolio that highlights:
- selected public machine learning and AI projects,
- code repositories and publication links,
- a concise professional profile for industry applications,
- and a downloadable CV.

## Intended live URL

Once GitHub Pages is enabled for this repository, the site should publish at:

`https://jaberqezelbash.github.io/JaberChamak/`

## Positioning of this portfolio

This version of the site is intentionally different from a full academic homepage.

It is built to support **industry job applications**, especially for roles in:
- healthcare data science,
- machine learning engineering,
- applied AI / LLM engineering,
- clinical analytics,
- and healthcare-focused data / ML platform work.

The page emphasizes:
1. end-to-end healthcare ML workflows,
2. public code repositories,
3. project-level business / industry relevance,
4. selected peer-reviewed publications,
5. and practical tools such as Python, SQL, Spark, Azure, AWS, Databricks, and modern deep learning / LLM tooling.

## Featured public projects in this portfolio

- **Finetune Qwen2.5-1.5B-Instruct for Medical Q&A**  
  CPU-only LoRA fine-tuning of an instruction-tuned LLM on a medical Q&A dataset.

- **KANBalance**  
  A class-imbalance mitigation framework combining Kolmogorov-Arnold Networks and Focal Loss.

- **DEQ-KAN**  
  A medical imaging classification framework that combines Deep Equilibrium Models with KAN-based representations.

- **NoPropBalance**  
  A memory-friendly, class-imbalance mitigation pipeline based on no-propagation learning, minority-class reconstruction, and GAN refinement.

## Other selected publications highlighted on the page

- Longitudinal fetal heart rate analysis for identifying neonates with metabolic acidemia requiring therapeutic hypothermia.
- Hybrid learnable fusion of ConvNeXt and Swin Transformer for optimized image classification.
- Survey of machine learning in kidney disease diagnosis.

## Main files you should keep updated

- `_config.yml`  
  Sidebar profile, contact links, site title, GitHub Pages base URL, and CV link.

- `_layouts/default.html`  
  Overall page layout and sidebar / footer behavior.

- `index.md`  
  Main portfolio content shown on the live site.

- `ASSETS_TO_UPLOAD.md`  
  Checklist of images / files to upload manually.

- `pdf/Jaber_Chamak_CV.pdf`  
  Your downloadable CV.

## Manual steps after copying these files into your repo

1. Overwrite the template headshot at `images/logo.png` with your real profile photo.
2. Upload the project figures listed in `ASSETS_TO_UPLOAD.md`.
3. Upload your CV PDF to `pdf/Jaber_Chamak_CV.pdf`.
4. Delete template leftovers that are no longer needed:
   - `images/demo.gif`
   - `images/dummy_thumbnail.jpg`
   - `pdf/sample_presentation.pdf`
5. Enable GitHub Pages from the repository **root** on the default branch.
6. Review the wording in `index.md` and personalize anything you want to tighten further.

## Suggested repo cleanup

You can keep the original `LICENSE` file from the template if you want, but if you prefer a different license for your own portfolio content, update it accordingly.

You can also safely delete `sample_page.md` if you do not want an extra page. A replacement version is included here so the repo does not contain placeholder lorem ipsum content.

## Credits

This portfolio structure is adapted from the quick-portfolio template and the Minimal GitHub Pages theme, but the content here is rewritten for Jaber Chamak’s project portfolio and industry-facing presentation.
