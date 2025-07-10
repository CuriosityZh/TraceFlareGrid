# TraceFlareGrid

TraceFlareGrid listens to live log streams and emits "flares" when abnormal patterns, bursts, or repeating anomalies are detected across multiple services or regions.

## Features
- Buffered event correlation across time windows.
- Pattern-based flare triggering.
- Flare burst visualization with timestamps.
- Ready for integration with Elastic, Kafka, Loki.

## Usage
```bash
git clone https://github.com/your-org/TraceFlareGrid.git
cd TraceFlareGrid
python traceflare/stream_receiver.py
