# Collaborative Perception for V2X – Core Papers

This repository organizes the essential papers for a PhD literature review and proposal on **collaborative perception in vehicle-to-everything (V2X) networks**, with a focus on **communication efficiency, compression, sparse representation, and edge-cloud collaboration**.

## Index by Phase

### Phase 1 – Foundations
- [F-Cooper](#) – SEC 2019 (Recommended)
- [V2VNet](#) – ECCV 2020 (Mandatory)
- [DiscoNet](#) – NeurIPS 2021 (Recommended)
- [V2X-ViT](#) – ECCV 2022 (Mandatory)
- [CoBEVT](#) – ECCV 2022 (Mandatory)

### Phase 2 – Communication Efficiency
- [Where2comm](#) – NeurIPS 2023 (Mandatory)
- [PACP](#) – IEEE TMC 2024 (Recommended)
- [C-MASS / MASS](#) – IEEE T-VT 2024 (Mandatory)
- [SparseComm](#) – Pattern Recognition 2025 (Recommended)

### Phase 3 – Compression
- [CoGMP](#) – CVPR 2025 (Mandatory)
- [SlimComm](#) – ICCV 2025 (Mandatory)
- [Flexible Variable-Rate Image Feature Compression](#) – ICMEW 2023 (Recommended)

### Phase 4 – Sparse Representation
- [Long-SCOPE](#) – CVPR 2026 (Mandatory)
- [DSRC](#) – AAAI 2025 (Recommended)

### Phase 5 – Edge-Cloud & Benchmarks
- [Infrastructure-Side Critical Feature Extraction](#) – IEEE IoT-J 2025 (Mandatory)
- [OPV2V Dataset](#) – ICCV 2021 (Mandatory)
- [V2XSet](#) – ECCV 2022 (Mandatory)

### Phase 6 – Generalization & Robustness
- [DI-V2X](#) – ICCV 2023 (Optional)

## Comparison Table

Comparison of key papers across architectural, fusion, and efficiency dimensions:

| Paper               | Phase | Fusion Type                     | Key Contribution                                                                 | Implementation / Reproducibility |
| ------------------- | ----- | ------------------------------- | -------------------------------------------------------------------------------- | -------------------------------- |
| V2VNet              | 1     | Intermediate Fusion             | Message passing + feature-level collaboration (baseline)                         | Good                             |
| DiscoNet            | 1     | Knowledge Distillation          | Reduced feature transmission cost via distillation                               | Moderate                         |
| CoBEVT              | 1     | BEV Transformer                 | Token-based BEV communication                                                    | Good                             |
| Where2comm          | 2     | Semantic Communication          | Confidence-map-based region selection for transmission                           | Good enough                      |
| PACP                | 2     | Priority Optimization           | Agent prioritization + adaptive autoencoder                                      | Moderate                         |
| SparseComm          | 2     | Lossy Communication             | Packet loss & noisy channel robustness                                           | Limited                          |
| CoGMP               | 3     | Discrete Compression            | Codebook-based compression + index transmission                                  | Good enough                      |
| SlimComm            | 3     | Adaptive Sparse Compression     | Sparse query transmission adaptive to channel conditions                         | Good                             |
| Long-SCOPE          | 4     | Sparse Architecture             | Fully sparse long-range perception                                               | Not yet available                |
| Infrastructure-Side | 5     | Edge-Cloud Collaboration        | Critical feature extraction at edge                                              | Moderate                         |
| OPV2V               | 5     | Dataset & Benchmark             | Main collaborative perception dataset                                            | Excellent                        |

## Notes
- **Mandatory** = essential for proposal justification.
- **Recommended** = strong supporting work.
- **Optional** = useful for specific subsections.
- Status tracking, reading dates, and personal notes are maintained in the original Excel sheet.
