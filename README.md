# 物体検知アプリ

## プロジェクト概要

Detector App は、画像内のオブジェクトを検出および分類するための機械学習アプリケーションです。このアプリケーションは、Pythonの軽量ウェブフレームワークであるFlaskを使用して構築されており、画像処理にはOpenCVを、オブジェクト検出にはPyTorchを使用しています。Google Cloud Runで簡単にデプロイできるように設計されており、スケーラビリティと信頼性を確保しています。

## 主な機能

* **ユーザー認証:** Flask-Loginを使用した安全なユーザー登録とログイン。
* **画像アップロード:** ユーザーがオブジェクト検出のために画像をアップロードできます。
* **オブジェクト検出:** アップロードされた画像内のオブジェクトを検出および分類するための事前訓練済みの機械学習モデルを使用。
* **結果表示:** アップロードされた画像内の検出されたオブジェクトをハイライトしてラベル付け。
* **スケーラビリティ:** Google Cloud Runでデプロイされており、アプリケーションが変動する負荷を処理し、適応的にスケールできます。

## 使用技術

* **バックエンド:** Flask, Flask-Login, Flask-WTF
* **画像処理:** OpenCV
* **機械学習:** PyTorch
* **データベース:** SQLAlchemy（ユーザーデータ用）
* **デプロイ:** Docker, Google Cloud Run
