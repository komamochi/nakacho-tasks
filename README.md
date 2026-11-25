# なかちょタスク

タブごとに、好きな列を作れるタスク表。

- 上のタブ：「＋」で追加、ダブルクリックで名前変更、ドラッグで並べ替え
- 下の表：列名を押すと種類（テキスト・チェック・選択肢・日付・数値）や並べ替え
- 保存先：Supabase（Web Archive と同じログイン）。表 `task_boards` は web-archive の `supabase/schema.sql` で作成済み

## 手元で動かす

```
npm install
npm run dev
```
