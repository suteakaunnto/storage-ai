# YACCHO Test Report

## Historical Test Results: v0.3

過去の開発時に以下を確認済み。

- sample.yaccho：成功
- test_suite.yaccho：成功
- test_yaccho.py：18 tests passed

## Test Environment

- OS：Windows 10
- Python：3.10以上
- Command examples：

python yaccho.py sample.yaccho
python yaccho.py test_suite.yaccho
python test_yaccho.py

## Current Verification

この資料を作成した時点では、現在のPC内のファイルを再実行していない。
上記は過去のテスト記録であり、現在の実行結果ではない。

## Future Test Categories

- Lexer tests
- Parser tests
- AST tests
- Semantic analysis tests
- Type checker tests
- Bytecode tests
- VM tests
- Standard library tests
- Integration tests
- Regression tests
- Performance tests
- Memory tests
- Security tests
- Cross-platform tests

## Test Policy

機能を追加したら必ずテストを行う。
成功・失敗・未確認を区別して記録する。
