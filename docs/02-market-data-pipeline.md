# Market Data Pipeline

## Data sources
- Exchange APIs / brokers
- WebSocket streams
- Historical backfill

## Normalization
- Timestamps
- Symbol mapping
- Corporate actions (if applicable)

## Storage & replay
- Append-only storage
- Deterministic replay for backtests

## Data quality
- Missing ticks/candles
- Outliers
- Latency and clock drift
