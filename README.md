## Clovers (Mary) Akitoye

Pharmacist (BPharm) completing an MSc in AI for Healthcare at the University of Hull. I build machine learning and language model tools for healthcare and pharmaceutical quality, and I test them the way a pharmacist checks a prescription before it reaches a patient: with controls, honest metrics and a clear reason for every decision.

I am currently a Pharma Technical Quality intern at Roche.

**Portfolio:** [maryclovers.github.io](https://maryclovers.github.io)

## At Roche

I work in Pharma Technical Quality on an AI assistant that helps drug development project teams see which quality and regulatory requirements apply to them, and when, so they are not discovered late. The work combines language model tools with input from quality and operations experts, and a qualified person stays in charge of every GxP decision. The internship was extended to December 2026.

Project details, documents and colleagues are not described here, in line with Roche's confidentiality rules.

## Projects

| Project | What it shows | Result |
|---|---|---|
| [chest-ct-report-generation](https://github.com/maryclovers/chest-ct-report-generation) | MSc dissertation. Vision-language model for 3D chest CT: frozen encoders, a Q-Former-style bridge and BioGPT-Large with LoRA, trained on an A100, tested with blank-input and shuffled-scan controls | Showed that the scores came from the language model, not the scan (all arms 0.09 to 0.12 BLEU-4, blank input included) |
| [tcga-glioma-grading](https://github.com/maryclovers/tcga-glioma-grading) | Leak-free clinical machine learning on 861 TCGA patients, model chosen on missed-cancer risk, with an MHRA and NHS deployment strategy | 64 of 73 glioblastomas caught, sensitivity 0.88, AUC 0.90. Module mark 85% |
| [wbc-breast-cancer-classification](https://github.com/maryclovers/wbc-breast-cancer-classification) | A full clinical ML workflow: imbalance handling, feature selection, SVM, a PyTorch network, cross-validation and threshold tuning | 0.94 cross-validated accuracy, sensitivity 1.0 at a 0.3 threshold |
| [medical-image-processing](https://github.com/maryclovers/medical-image-processing) | Brain MRI case study and CT, MRI, radiography and microscopy labs, every step measured | 41% less white-matter noise, CLAHE preserved structure (SSIM 0.77) |
| [vehicle-damage-cnn](https://github.com/maryclovers/vehicle-damage-cnn) | CNN built from scratch on an imbalanced six-class image dataset | Macro recall 0.69 on 1,440 test images |
| [customer-behaviour-ml](https://github.com/maryclovers/customer-behaviour-ml) | Regression, churn classification and clustering on 5,000 customers | R² 0.886 for spend, 0.99 churn accuracy |
| [census-demographic-analysis](https://github.com/maryclovers/census-demographic-analysis) | Cleaning and statistical testing on messy census data | Distinction |
| [personalised-invite-site](https://github.com/maryclovers/personalised-invite-site) | Full-stack web app: a private link, preview card and RSVP for every guest, with a gift registry and admin dashboard | Next.js, TypeScript, Supabase, Vercel |

## Toolkit

**Machine learning:** Python, scikit-learn, PyTorch, TensorFlow and Keras, Hugging Face Transformers, PEFT and LoRA, MONAI
**Medical imaging:** DICOM, pydicom, nibabel, OpenCV, scikit-image, Hounsfield units, CT reconstruction, MRI preprocessing
**Language model tools:** retrieval-based extraction, prompt pipelines with human review, LoRA fine-tuning, Hugging Face
**Evaluation:** sensitivity and specificity, ROC and AUC, threshold analysis, BLEU, ROUGE, METEOR, BERTScore, control arms, bootstrap intervals
**Infrastructure and web:** Git, Jupyter, Google Colab, Slurm on an HPC cluster, Next.js, TypeScript, Supabase, Vercel
**Healthcare and quality:** GxP, the MHRA software as a medical device pathway, UK GDPR, pharmacovigilance, medication safety

## Contact

[LinkedIn](https://www.linkedin.com/in/cloversakitoye) · cakitoye@gmail.com · Based in Hull, open to relocation
