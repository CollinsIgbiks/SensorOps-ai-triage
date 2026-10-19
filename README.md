# SensorOps: AI Alert Triage

> 🚧 **In progress.** Part 2 of [SensorOps](docs/PROJECT_BRIEF.md), an end-to-end IoT monitoring platform.

A self-hosted **n8n** workflow that receives alerts from the [SensorOps Telemetry API](https://github.com/CollinsIgbiks/sensorops-api), uses generative AI to classify each fault and rank its urgency, explains it in plain English, and notifies a person only when it's critical. It also includes a **Python sensor simulator** that generates realistic readings plus a labelled record of injected faults, used to measure the AI's accuracy.

## The problem it solves
Not every alert deserves a person's attention. This workflow sorts faults by urgency and explains them, so engineers spend time only on what matters, and it measures how accurate the AI actually is before anyone relies on it.

## Architecture
See [the architecture diagram in the project brief](docs/PROJECT_BRIEF.md#2-architecture-and-data-flow). A workflow screenshot will be added in Milestone 5.

## Tech
n8n (Docker) · Ollama / LLM API · Python 3.15 · Google Sheets · Telegram / Gmail

## How to run it
_Coming in Milestones 4–5._

## Results
_Pilot results (accuracy %, alerts raised, critical escalations) will be added in Milestone 6 in `docs/PILOT_RESULTS.md`._

## What I'd do next
_To be written._

## Licence
[MIT](LICENSE)
