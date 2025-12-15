# Airbus-Ship-Detection-Challenge-Deeplearning-model
コンペティションに向けたモデルを保存する

現状考えているベースラインは、HRnetv2
セグメンテーションに強いモデルを構築しつつ、追加で対象学習を行えたらと考えている。

代替案
→物体検出モデル＋セグメンテーションの2段構成についても案としてはあり得るかも。

Segformerについても動かしてみた。(超軽量）

方向性について、
Objectness→segmentationの二段階構成で実施したいと考えている。
