# DeepGuard

DeepGuard is an on-device iOS application for detecting visual deepfakes using a lightweight, multi-model AI pipeline optimized for edge devices.  
The system focuses on real-time analysis, privacy, and explainable results.

---

## Key Features

- On-device deepfake detection
- Multi-model analysis (vision, facial features, compression artifacts)
- Consensus-based decision logic
- Threat level and confidence scoring
- Camera snapshot and live capture support
- Privacy-first (no background recording, no data storage)

---

## Architecture Overview

Camera Input  
→ Snapshot Capture  
→ Parallel AI Analysis  
→ Result Aggregation  
→ Threat Classification

Detection is flagged only when multiple models agree, reducing false positives.

---

## Tech Stack

- iOS / Swift / SwiftUI
- AVFoundation
- Vision Framework
- Swift Concurrency (async/await)

---

## Requirements

- iOS 15+
- Physical iPhone (camera required)

---

## Usage

1. Open project in Xcode
2. Run on a physical device
3. Grant camera permission
4. Capture image or enable live detection

---

## Output

- Deepfake status (Real / Fake)
- Confidence score
- Detected indicators
- Threat level classification

---

## Scope

Designed as a hackathon prototype demonstrating edge-based AI security concepts.  
Extensible to video, audio, and other edge devices.

---

## Author

Harshvardhan Kumar
