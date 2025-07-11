# FlowGridSentience

FlowGridSentience observes streaming data, builds memory of known event patterns, and detects structural anomalies over time. Ideal for pipelines that evolve.

## Features
- Learns normal event flows and sequence order.
- Detects unexpected or out-of-order signals.
- Feedback-based retraining.
- Can operate in “listen-only” or “adaptive” mode.

## Usage
```bash
git clone https://github.com/your-org/FlowGridSentience.git
cd FlowGridSentience
python flowgrid/stream_ingestor.py logs/events.jsonl
