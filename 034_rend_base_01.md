## 034_rend_base_01
第34回：レンダリング基礎編（1）
～Houdiniのレンダリングの基礎を学ぼう～

---
### メモ

- FPSについて
  プロジェクトに合わせて都度調整する
- Flipbook
  プレビュー画面をOpenGL上でレンダリングしてくれる
  `$RFSTART or $FSTART` フレーム開始時間
  `$RFEND or $FEND` フレーム終了時間
  フレームのインクリメント設定可能
  startでMPLAYが起動される
  LookUtTableが読み込める
  i : 数値などの情報を見れる
- MPLAY
  Houdiniとは独立して実行される
  mplay.exeで起動可能
  閉じなければレンダリング画像が蓄積されていく
  比較するためのcompareモードがある
- gplay
  Geometry再生・確認用
  シーケンスのものならシュミレーションまで見れる
  煙のキャッシュなど
  シェーダーは適用されない
- 