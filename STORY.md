# Day088 Story — Repair Replace Breakpoint

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day088専用にテーマをseed固定して再生成時の見た目を安定化
- productivity用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: repair_replace_decision
- Mechanic: threshold_slider
- Input/Output: cost_factor_rows -> decision_meter
- Audience Promise: 迷いを、見積もり確認・修理予約・買い替え検討の次アクションへ落とせる。
- Publish Hook: 修理額、買い替え額、待ち日数、使えない困り度、愛着メモを入れると、境界線と次の確認先が見える。
- Complexity Tier: small
- Selected components: none
- Complexity hint: Implement the locked brief with one clear hero interaction and keep the main screenshot readable.

## Trade-offs / Known issues
- ローカル保存機能は未実装
- 複雑な入力バリデーションは最小限

## Next ideas
- 履歴保存
- プリセット追加
- エクスポート形式拡張

## Social copy
Day088｜修理買い替え境界線
壊れた物を修理するか買い替えるか、費用・待ち時間・愛着で境界を見るツールです。
