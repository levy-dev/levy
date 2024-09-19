# Levy

SQL ツールチェーン

## やること

- sqlc ほぼ互換のコード生成
  - PostgreSQL への対応
  - Go / TypeScript / Python への対応
  - `sqlc.embed` は `levy.embed`
  - `levy compile`
  - `levy generate`
- ブラウザ対応
- VS Code 拡張対応
- 動的な解析と静的な解析の両方に対応
- WebAssembly の利用
- Formatter 内蔵
  - `levy format`
- Linter 内蔵
  - `levy lint`
- Migration 内蔵
  - `levy migrate`

## やらないこと

- MySQL への対応
  - 有償にて対応
