## Repo under construction! Code will be available soon together with pseudo-data that matches the one used for the study.

# Federated Learning Towards the Unknown: A Deep Dive Into Diabetic Retinopathy Prediction from RealWorld EHR Structured Data on Unseen Diabetic Centers
[ECML PKDD 2025][https://ecmlpkdd-storage.s3.eu-central-1.amazonaws.com/preprints/2025/ads/preprint_ecml_pkdd_2025_ads_665.pdf]

## 🎯 Introduction  
We train a federated XGBoost (FL-XGB) model on data from multiple centers, and introduce the **Out-of-Federation Applicability (OFA)** predictor to estimate *before deployment* whether FL-XGB will perform reliably on new, unseen centers.

## Motivation & Background  
Federated Learning enables privacy-preserving model training across sites, but models often fail when confronted with out-of-federation (OOF) data. There is a need for tools that can **predict compatibility** with new centers, rather than simply hoping models generalize.
