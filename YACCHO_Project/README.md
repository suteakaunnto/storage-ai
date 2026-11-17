# YACCHO

YACCHOは、日本語と英語の両方でプログラムを書けることを目指すプログラミング言語プロジェクトです。

## Project Goals

- 日本語構文と英語構文への対応
- 日本語と英語を混在させたコードへの対応
- 独自Lexer・Parser・ASTの開発
- 独自バイトコードと仮想マシンの開発
- 標準ライブラリの拡充
- GUI・ゲーム・Webアプリケーション開発
- AI開発支援
- 専用統合開発環境YACCHO Studio
- 安全で拡張可能な実行環境

## Current Status

- v0.1〜v0.3：開発済み
- v0.4：未着手
- v0.5：未着手
- v0.6：計画段階
- v1.0.0：長期目標

## Current Implementation

v0.3はPythonを利用したインタプリタ型の試作です。
Python ASTのホワイトリスト方式で式を評価します。
任意のPythonコードを自由に実行する方式ではありません。

## Development Environment

- OS：Windows 10で動作確認済み
- Runtime：Python 3.10以上
- Development：PowerShell、Python

## Important Policy

日本語と英語を正式な対応言語として設計します。
ただし、両言語の構文対応は今後の実装・テストで確認します。

## Documentation

- ROADMAP.md：開発ロードマップ
- SPECIFICATION.md：言語仕様
- CHANGELOG.md：変更履歴
- DEVELOPMENT_STATUS.md：開発状況
- ARCHITECTURE.md：内部設計
- TEST_REPORT.md：テスト結果
- NEXT_TASK.md：次の作業
- docs/：詳細仕様
