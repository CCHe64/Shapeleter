# Shapeleter
**Shapelet Enhancer via Multiview Positional Embedding for Time Series Classification (TSC)**

---

## 1) Paper
**Title**: *Shapeleter: Shapelet Enhancer via Multiview Positional Embedding for Time Series Classification*  
**Venue**: *Knowledge-Based Systems* (Under Review)

---

## 2) What Shapeleter does 
Shapeleter is an interpretable shapelet-based TSC framework that targets both **accuracy** and **interpretability**.  
It (i) selects a compact set of discriminative shapelets using a **hypergraph-aware selection** strategy to capture higher-order relations among candidates, (ii) represents selected shapelets with **multiview position-aware features** using two complementary notions of position to encode global context and ordering-related evolution, and (iii) performs prediction via a lightweight **multiview ensemble** built on simple linear classifiers.

**Interpretability**: The selected shapelets are human-readable subsequences and can be inspected per class as discriminative knowledge units.

---

## Citation

If you use this repository (code, results, figures, or ideas), please cite our manuscript.

### BibTeX
```bibtex
@unpublished{shapeleter_under_review,
  title   = {Shapeleter: Shapelet Enhancer via Multiview Positional Embedding for Time Series Classification},
  note    = {Under review at Knowledge-Based Systems},
  year    = {2026},
  url     = {https://github.com/CCHe64/Shapeleter}
}

