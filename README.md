# 美味しいアイスコーヒーのための温度早見表

> Iced Coffee Temperature Reference — an interactive calculator for the final temperature of iced coffee based on heat balance between hot water and ice.

注ぐお湯と容器の氷の熱バランスから、出来上がるアイスコーヒーの最終温度を計算します。

## 機能 / Features

- 氷の量、お湯の量、お湯の温度をスライダーで操作 / Adjust ice mass, water amount, and water temperature with sliders
- 詳細設定で氷の初期温度も指定可能 (冷凍庫由来の -18 °C など) / Advanced setting for initial ice temperature
- 出来上がり量を横軸にした早見グラフ / Reference chart with total amount on the x-axis
- 計算式と物性値を表示 / Formulas and physical constants shown on the page

## 使い方 / Usage

ブラウザで `index.html` を開くだけです。サーバーは不要です。

Just open `index.html` in any modern browser — no server required.

## デプロイ / Deployment

このリポジトリは GitHub Pages 用に作られています。Settings → Pages から有効化してください。

This repository is set up for GitHub Pages. Enable it in Settings → Pages.

## モデルについて / About the model

水の比熱、氷の比熱、氷の融解熱を使った理想化された熱バランスモデルです。容器の熱容量、空気との熱交換、コーヒー粉が吸う水分は考慮していません。

An idealized heat-balance model using specific heat of water and ice and latent heat of fusion. Container heat capacity, air convection, and water absorbed by coffee grounds are neglected.

## ライセンス / License

MIT
