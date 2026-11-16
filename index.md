---
title: WorldFoundation Drive Backup
---

# WorldFoundation Drive Backup

WorldFoundation Drive Backupは、個人利用を目的としたGoogleドライブ向けバックアップ補助ツールです。

## 主な機能

Windows環境でPowerShell 7と7-Zipを使用してプロジェクトのバックアップZIPを作成し、rcloneを通じてGoogleドライブへアップロードします。

- バックアップZIPの作成と整合性確認
- Google Drive APIを使用したファイルのアップロード
- アップロード結果の確認
- 過去のバックアップを残す世代管理

Googleドライブとの双方向同期やミラーリングは行わず、保存済みバックアップの自動削除も行いません。

## Googleアカウントへのアクセス

Google OAuth 2.0を使用して、本人の承認に基づきGoogleドライブへアクセスします。

Google Drive APIへのアクセスは、バックアップの保存と確認に使用します。

本ツールは個人専用であり、第三者に提供するサービスではありません。

## プライバシー

Googleユーザーデータの取り扱いについては、[プライバシーポリシー](./privacy.html)をご確認ください。
