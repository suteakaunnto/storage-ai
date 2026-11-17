# YACCHO Design Decisions

## Decision 001: Japanese and English

Status：採用方針

日本語と英語を両方とも正式な対応言語とする。
一方を単なる翻訳版として扱わない。

## Decision 002: Shared Internal Representation

Status：計画

日本語構文と英語構文を同じAST・IRへ変換する。

## Decision 003: Independent Runtime

Status：v0.6で実装予定

Python AST評価方式から独自バイトコード・VM方式へ段階的に移行する。

## Decision 004: Optional Frameworks

Status：計画

GUI、ゲーム、Web、AI機能は言語本体と分離し、必要に応じて導入できる構成を目指す。

## Decision 005: Compatibility

Status：継続検討

既存バージョンのコードを可能な限り維持する。
仕様変更はCHANGELOGに記録する。

## Decision 006: Development Process

Status：採用方針

各機能を小さく実装し、テストを通してから次へ進む。
未実装機能を完成済みとして扱わない。
