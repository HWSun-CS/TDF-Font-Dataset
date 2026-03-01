# ComplexGlyph-Flow: Dynamic Manifold Dataset & Generation Tools

This repository contains the dynamic flow field dataset and temporal sequence generation tools for the paper: **"TDF-Font: Continuous Geometric Evolution for Few-shot Font Generation via Trajectory-based Diffeomorphic Flow"**.

## Overview
Designed to address the challenges of structurally complex glyphs with intricate topologies, this toolkit provides a deterministic and continuous geometric evaluation testbed. Key features include:

- **Diffeomorphic Registration:** Log-Domain Diffeomorphic Demons scripts for rigorous, topology-preserving font alignment (preventing stroke breakage and structural hallucinations).
- **Temporal Sequence Construction:** Tools for continuous font manifold sampling, generating physical and dynamic ground-truth trajectories for Flow Matching supervision.
- **Data Pipeline:** Comprehensive preprocessing, augmentation, and normalization scripts tailored for high-frequency Chinese characters and other topology-sensitive scripts.

⚠️ **Status:** The dataset, complete generation scripts, and detailed usage instructions are currently being organized. They will be officially open-sourced and released alongside the main TDF-Font model code.
