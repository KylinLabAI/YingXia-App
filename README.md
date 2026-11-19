# YingXia (盈匣)

[中文](README.zh.md)

![YingXia Logo](resources/logo_256.png)

A local-first A-share AI quant research workbench turning raw data into audited, reproducible signals without cloud upload.

## Features

- **CSV bar import, quality validation and immutable point-in-time (PIT) snapshots**
- **Factor/feature evaluation in a whitelisted DSL reused for training and inference**
- **Model version registration with model cards, shadow-output comparison and audited rollback**
- **Event-driven backtests with built-in A-share rules (T+1, price limits, suspensions, 100-share lots, fees, slippage)**
- **Strategies emit signals only — every order passes an independent L1–L4 risk gate**
- **Signal export (CSV/qlib/JSONL) and dispatch with HMAC signing, idempotency, replay and revoke**
- **Hash-chained audit events and offline archive/re-verification; desktop and CLI share one Rust core API**

## Release Status

The official release has not yet been published. Please watch the GitHub / Gitee Releases page for updates.

GitHub: https://github.com/KylinLabAI/YingXia-App
Gitee:  https://gitee.com/KylinLab/YingXia-App

## About

YingXia is a local-first A-share AI quant research workbench: data import and validation, PIT snapshots, factor research, model training and registration, backtests, L1–L4 risk control and signal distribution all run locally, with no cloud upload.

## Contact

kylinlab.tech
