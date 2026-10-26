# 第5回 Webエンジニアリング演習 レポート

## 学籍番号
(あなたの学籍番号)4724202

## TODO配列のコード
```typescript
const todos = [
  { id: 1, title: "型を復習する", completed: true },
  { id: 2, title: "配列を学ぶ", completed: false },
  { id: 3, title: "レポートを書く", completed: false },
  { id: 4, title: "コミットする", completed: false },
];

## TODOを更新した 条件
for (const todo of todos) {
  if (!todo.completed) {
    todo.completed = true;
  }



##完了件数の 更新前後の 実行結果
}更新後: 配列を学ぶ [完了]
更新後: レポートを書く [完了]
更新後: コミットする [完了]
完了件数: 更新前 1件 -> 更新後 4件
