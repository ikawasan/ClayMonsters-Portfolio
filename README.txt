ClayMonsters 就職活動用ポートフォリオ
====================================

場所
----
C:\Users\pon\Desktop\ClayMonsters_Portfolio\

開き方
------
index.html をダブルクリック（ブラウザで開く）

構成
----
index.html          … ポートフォリオ本体
assets\             … ロゴ・アプリアイコン
assets\screens\     … スクリーンショット差し込み用（下記ファイル名）

スクリーンショットの入れ方
--------------------------
ゲーム内またはビルドからキャプチャし、次の名前で保存してください。

  assets\screens\01_title.png
  assets\screens\02_edit.png
  assets\screens\03_training.png
  assets\screens\04_battle.png
  assets\screens\05_pvp.png
  assets\screens\06_pet.png

保存後、ページを再読み込みすると自動で表示されます。

プロフィール（氏名・連絡先）の書き換え
--------------------------------------
index.html をエディタで開き、ページ下部の script 内コメント
「プロフィールをここで書き換える」の下に例を追記するか、
HTML 内の「（氏名を記入）」などの文言を直接置き換えてください。

面接で話すと刺さりやすいポイント
--------------------------------
1. ボクセル粘土 → メッシュ → リギング → glTF → Workshop の内製パイプライン
2. 間合い・コスト・部位破壊を持つリアルタイム戦闘ドメイン
3. Auth / Lobby / Relay / Netcode によるオンラインPvP
4. Launcher / 本編 / Desktop Pet の Steam 出荷設計
5. VContainer + MVP + UniTask/R3 と、実行時UI生成を避ける保守方針

補足
----
ストアURL・GitHub・デモ動画があれば、index.html の CTA やプロフィール欄にリンクを追加すると効果的です。
