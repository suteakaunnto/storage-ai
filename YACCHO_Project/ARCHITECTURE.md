# YACCHO Architecture

## Current v0.3 Architecture

- Pythonで実装されたインタプリタ型プロトタイプ
- Python ASTのホワイトリスト方式で式を評価
- 任意のPythonコードを自由実行する設計ではない

## Planned v0.6 Architecture

Source Code
    |
    v
Lexer
    |
    v
Parser
    |
    v
AST
    |
    v
Semantic Analysis
    |
    v
Type Checker
    |
    v
Intermediate Representation (IR)
    |
    v
Optimizer
    |
    v
Bytecode
    |
    v
Virtual Machine

## Planned Modules

compiler/
- lexer
- parser
- ast
- semantic
- type_checker
- ir
- optimizer

runtime/
- vm
- bytecode
- memory
- gc
- scheduler
- jit

stdlib/
- math
- string
- collections
- file
- json
- csv
- network
- database
- graphics
- audio

frameworks/
- gui
- game
- web
- ai

studio/
- editor
- debugger
- designer
- project_manager

tools/
- cli
- formatter
- tester
- profiler
- docs

package_manager/
security/
tests/
samples/
docs/

## Architecture Rules

- CompilerとGUIを独立させる。
- RuntimeはCompiler内部の実装に依存しすぎない。
- 標準ライブラリは公開Runtime APIを利用する。
- GUI・Game・Web・AIは追加機能として分離する。
- 各モジュールにテストを用意する。
- 日本語・英語の構文は共通の内部表現へ変換する。
