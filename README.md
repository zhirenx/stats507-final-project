# STATS 507 Final Project — BERT vs DistilBERT vs RoBERTa on SST-2

Zhiren Xia, University of Michigan

This project compares three transformer models (BERT, DistilBERT, RoBERTa) on the SST-2 sentiment classification task using the Hugging Face ecosystem.

## Files
- `sst2_project.ipynb` — Main notebook with training and evaluation code
- `final_report.pdf` — IEEE format summary report

## Results
| Model | Accuracy | Training Time | Parameters |
|-------|----------|--------------|------------|
| BERT | 93.2% | 169 min | 110M |
| DistilBERT | 90.7% | 73 min | 67M |
| RoBERTa | 93.7% | 806 min | 125M |
