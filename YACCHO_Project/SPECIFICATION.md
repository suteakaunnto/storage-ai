# YACCHO Language Specification

## 1. Overview

YACCHOは日本語と英語の両方に対応することを目指すプログラミング言語。

## 2. Language Policy

- 日本語構文を正式にサポートする。
- 英語構文を正式にサポートする。
- 同じプログラム内で日本語と英語を混在できる設計とする。
- 両言語の構文は同じ内部表現へ変換する。
- 識別子はUnicodeに対応する方針とする。
- 文字列とコメントもUnicodeに対応する。

※上記は設計方針を含む。実装済みかどうかは機能ごとに確認する。

## 3. Current v0.3 Features

- 変数
- 算術演算
- 真偽値
- 比較演算
- メンバーシップ判定
- リスト
- タプル
- 辞書
- インデックス参照と代入
- if / else
- 固定回数のrepeat
- 条件ループ
- foreach
- break相当の「ぬける」
- continue相当の「つぎへ」
- 関数とreturn
- 組み込み関数

## 4. Built-in Functions

v0.3で実装された関数：

- 表示
- 長さ
- 追加
- 削除
- 範囲
- 型

## 5. Current Runtime

v0.3はPython ASTのホワイトリスト方式による評価を利用する。
独自Lexer、Parser、VMはまだ実装されていない。

## 6. Future Features

- 型注釈と型推論
- クラスと構造体
- 継承とインターフェース
- ジェネリクス
- パターンマッチング
- モジュール
- 例外処理
- 非同期処理
- バイトコード
- JIT
- GUI・ゲーム・Web機能

## 7. Compatibility

既存バージョンのコードを可能な範囲で維持する。
仕様変更時はCHANGELOG.mdに記録する。
