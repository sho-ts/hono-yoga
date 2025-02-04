# Hono + GraphQL Yogaの検証

## 目的

- Nest.jsがlegacy decoratorに依存している
- ESM系が扱いにくい
- 設計上nullセーフにしにくい（tsconfigのstrictNullCheckがデフォルトfalseなのも、設計上の理由な気がする）

## マイルストーン

- [ ] 基本的なGraphQLサーバー構築
- [ ] Query
- [ ] Mutation
- [ ] ResolveField
- [ ] DataLoader
- [ ] Upload(Custom Scaler)
- [ ] Defer Directive