# 盈匣 YingXia

[English](README.md)

![盈匣 Logo](resources/logo_256.png)

本地优先的 A 股 AI 量化研究工作台，在本地完成数据校验、因子研究、回测、风控与信号分发，数据模型不上传云端。

## 功能特性

- **CSV 行情导入与质量校验、不可变 PIT 快照**
- **白名单 DSL 评估因子/特征，同一定义复用于训练与推理**
- **模型版本注册、模型卡、影子输出对比与带审计记录的回滚**
- **事件驱动回测内置 A 股规则（T+1、涨跌停、停牌、100 股整数手、费用与滑点）**
- **策略仅产出信号，所有订单须通过独立 L1–L4 风控闸门**
- **信号导出 CSV/qlib/JSONL，分发支持 HMAC 签名、幂等、重放与撤销**
- **哈希链式审计事件、可归档并离线复核；桌面端与 CLI 共用同一套 Rust 核心 API**

## 发布状态

官方版本尚未发布，敬请关注 GitHub / Gitee 的 Releases 页面获取最新动态。

GitHub: https://github.com/KylinLabAI/YingXia-App
Gitee:  https://gitee.com/KylinLab/YingXia-App

## 简介

盈匣是一个本地优先的 A 股 AI 量化研究工作台，用户在本地完成数据导入与质量校验、PIT 快照、因子研究、模型训练与注册、策略版本治理、回测与风控、信号分发、归档与合规审计，所有数据模型不上传云端。

## 联系方式

kylinlab.tech
