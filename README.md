# Five-Lens Forecast Model — public dashboard

**Live dashboard: https://genwar-ops.github.io/Prediction-Dashboard/**

**JSON feed (for other front ends): https://genwar-ops.github.io/Prediction-Dashboard/feed/latest.json** (schema five-lens-feed/1: forecasts with ranges, change since the last publish, scenarios, history evidence and weights, data signals, audit status).

This repository holds only the dashboard (`index.html`, with its data built in), served by GitHub Pages from `main`, folder `/ (root)`. It is rebuilt when the model publishes (at most daily after the news review, or sooner if the 3-hourly audit finds a flaw).

Disclosure: Anthropic makes the assistant that built this model; the one Anthropic question is about timing only.
