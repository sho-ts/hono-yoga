# Hono + GraphQL Yogaの検証

## 目的

- 以下を解消したい
  - Nest.jsがlegacy decoratorに依存している
  - Nest.jsでESMが扱いづらい
  - 設計上nullセーフにしづらい（Nest.jsのtsconfigのstrictNullCheckがデフォルトfalseなのも、設計上の理由な気がする）

## マイルストーン

- [ ] 基本的なGraphQLサーバー構築
- [ ] Query
- [ ] Mutation
- [ ] ResolveField
- [ ] DataLoader
- [ ] Upload(Custom Scaler)
- [ ] Defer Directive
