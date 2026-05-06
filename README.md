# The Deepfakes We Missed

**We Built Detectors for a Threat That Didn't Arrive**

[Shaina Raza](https://scholar.google.com/citations?user=chcz7RMAAAAJ&hl=en) · 
<!-- [Paper](#) · [arXiv](#) · [Slides](#) · [Project Page](https://shainarazavi.github.io/deepfakes-we-missed/) -->

---

## Overview

This position paper argues that the dominant bottleneck on real-world deepfake defense is no longer model capability but a **misalignment** between the threat model the field organized around (public-figure face-swap video, circa 2017–2019) and the harms that actually materialized at scale: peer-generated non-consensual intimate imagery (NCII), voice-clone scam calls, and emotional-manipulation fraud.

## Key Findings

| | Finding |
|---|---|
| **71%** | of 438 classified papers (2017–2025) target T1 public-figure video |
| **260×** | growth in AI-CSAM videos, 2024 → 2025 |
| **0 / 13** | major benchmarks cover T2 (NCII), T4 (real-time), or T5 (messaging-layer) |
| **~2.5 OoM** | gap between T1 research effort and observed harm indicators |

## Threat Taxonomy

| ID | Category | Corpus Share |
|----|----------|-------------|
| T1 | Public-figure face-swap & talking-head video | 71.0% |
| T3 | Audio / voice-clone | 28.5% |
| T2 | Peer-generated NCII | ~0% (1 paper) |
| T5 | Messaging-layer / peer-distributed | ~0% (1 paper) |
| T4 | Real-time / live-stream | 0% |

## Contributions

1. A **438-paper classification** of detection research (2017–2025) across a five-category threat taxonomy (T1–T5)
2. A **harm distribution** synthesized from IC3, IWF, AIID, StopNCII.org, and victim surveys
3. A **structural diagnosis** of why the misalignment persists: benchmark inheritance, dataset-ethics asymmetry, and salience-driven attention allocation
4. **Three concrete research agendas** for under-defended harm categories

## Proposed Research Agendas

**I. Real-Time Voice-Clone Detection for Telecommunications**
Streaming synthesis-probability estimation under telephony codecs with sub-second latency, channel-robust evaluation, and speaker-conditional verification.

**II. On-Device Privacy-Preserving NCII Detection**
Low-reference few-shot verification within victim trust boundaries, federated/on-device inference where candidate images never leave the device, and workflow integration with StopNCII.org and platform trust-and-safety APIs.

**III. Messaging-Layer Defenses for Peer-Distributed Content**
Tiny on-device detectors operating pre-encryption, re-encoding-robust provenance signals, and graph-based distribution-pattern detection under privacy-preserving constraints.

## Citation

```bibtex
@inproceedings{raza2026deepfakeswemissed,
  title   = {The Deepfakes We Missed: We Built Detectors
             for a Threat That Didn't Arrive},
  author  = {Raza, Shaina},
  year    = {2026}
}
```

