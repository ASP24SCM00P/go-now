# go-now

Real-time dashboard that notifies you when it’s the perfect time to leave for your commute; powered by Kafka, Tinybird, and live traffic insights.

## Features
- Live ETA tracking between office and home
- Dashboard visualizes traffic trends
- Notifies you when drive time hits your ideal threshold
- Streaming data architecture for minimal latency

## Tech Stack
- Kafka (streaming events)
- Tinybird (real-time data APIs)
- React (frontend dashboard)
- Distance Matrix API 

## How It Works
traffic API → Kafka → Tinybird → Web Dashboard


