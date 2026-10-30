## Wongyu Lee

Founding member and engineer at **Fine Ludens** (Fine Play), a football performance-analysis
company in Seoul. I build the measurement side: expected-value models, the scoring engine on
top of them, and the tooling that gets match video turned into numbers.

- Co-designed **xFP**, a player-performance metric driven by xG, EPV and pitch-control models,
  shipped end to end from the video-tagging console to scores in a consumer app
- Deliver live match analytics to **iTOP21 Sports**, a K3 League broadcaster
- Co-inventor on **Korean Patent 10-3012144** — AI-based sports video analysis with
  highlight-segment detection
- BSc Information Systems, Hanyang University (expected Feb 2027)

**Most of my production work belongs to my company and lives in private repositories.** What
is listed here is the work I can show in full: a validation study, a research pipeline, and a
university-industry team project. Where a number appears in a README, the code to
reproduce it is in the same repository.

### Selected work

| Repository | What it is |
|---|---|
| **ldp-utility-privacy** | Monte Carlo study of the utility–privacy trade-off under local differential privacy — the validation experiment for my undergraduate research. Confirms the predicted 1/ε and 1/√n error scaling, and quantifies the regime where the mechanism stops being usable. |
| **ai-highlight** | Highlight-candidate extraction from full-match video: YOLO detection, spatio-temporal feature engineering, and a rule + XGBoost ensemble with per-clip SHAP explanations. |
| **[SWE-ITE/GOYO](https://github.com/SWE-ITE/GOYO)** | An AI-based active noise control system for smart homes: edge models classify appliance noise in real time so a chair with near-ear speakers cancels only the unwanted sources and leaves alarms and voices audible. I built the Flutter control app and its integration with the backend API and the Raspberry Pi hardware. Four-person team project; Excellence Award, LG Electronics × Hanyang University IC-PBL. |

### Working with

`Python` · `TypeScript` · `SQL` · `C++` · `Dart`
`PyTorch` · `XGBoost` · `scikit-learn` · `YOLO / Ultralytics` · `ByteTrack` · `SHAP`
`FastAPI` · `Next.js` · `Flutter` · `PostgreSQL` · `Docker` · `AWS` · `Electron` · `ffmpeg`
`StatsBomb event data` · `xG / EPV / pitch control` · `SPADL`

### Elsewhere

Portfolio: [sport analytics work](https://claude.ai/code/artifact/35ee4023-312e-47ad-a7a9-ee72cb38666d) · dnjsrb5316@gmail.com
