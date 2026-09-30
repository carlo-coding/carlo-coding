# Jaan Carlo Rivera

Software engineer in Guadalajara, Mexico. I build forecasting and data systems, and the software that keeps them honest.

## Now: clock

[clock.krafta.pro](https://clock.krafta.pro) · [repository](https://github.com/carlo-coding/clock)

A public forecasting record for European power. Every day, before the day-ahead market closes, it forecasts the next seven days hour by hour for Germany and Luxembourg (wind, solar, load, price) and Spain (wind, solar). The next day it scores every forecast against what actually happened, against the grid operator's own published forecast and against persistence. Every file is timestamped in the Bitcoin blockchain with OpenTimestamps and never edited.

- Scheduled jobs on GitHub Actions, with a watchdog that opens an issue when the series stops
- ENTSO-E API client written from scratch, with 23 and 25 hour days handled explicitly
- The first model is deliberately naive; the dated record is the point, and the headline score stays hidden until 30 days have been scored

## Learning in the open

Electrical power systems: steady state, N-1 security and how prices form on the grid, on an open simulator checked against pandapower and PyPSA. Next: small transformers trained on simulated grids and measured against the exact power-flow solution.

## Before

- **Contract software engineer, medical scheduling platform** (2023 to today). NestJS, Prisma and Next.js on a three-person team. Designed a service that predicts appointment no-shows and cancellations with CatBoost, currently in validation.
- **[Leddeo](https://github.com/carlo-coding/leddeo-backend)** (2023). SaaS that turned videos into editable subtitles in any language: Whisper transcription running on my own server, offline translation with Argos Translate, subtitles burned in with ffmpeg, and wait-time estimates from linear models fitted on logged jobs. Front end, Django back end and admin panel, deployed with Stripe billing.

## Stack

Python · TypeScript · NestJS · Prisma · Next.js · React · CatBoost · GitHub Actions

[LinkedIn](https://www.linkedin.com/in/jaan-carlo) · [X](https://x.com/JaanCarloRT) · jaanc.rt@gmail.com
