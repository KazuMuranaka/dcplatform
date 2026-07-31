このフォルダの中身を GitHub（kazumuranaka/dcplatform, main）に
アップロードして上書きしてください。

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
★ 先に手動で削除するファイルが1つあります
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  projectmap.html

  アップロードでは既存ファイルを消せません。GitHub上で
  projectmap.html を開き、ゴミ箱アイコン → Commit changes
  で削除してから、以下をアップロードしてください。

■ 上書きするファイル（13）
  index / news / marketplace / computeindex / glossary / faq /
  consult / sitecheck / gpu / cooling / power / network / reliability

  - ナビから「プロジェクトMAP」を削除し「開発マニュアル」を追加（7項目）
  - フッターから「プロジェクトMAP」「事業者名鑑（準備中）」を削除、
    「開発マニュアル（申請制）」を追加
  - index.html：サイドカードのプロジェクトMAP、無料コンテンツ一覧の
    2項目、未使用CSSを削除。開発マニュアルの紹介バンドを追加
  - faq.html：Q04の事業者名鑑への言及と関連リンクを差し替え

■ 新規に追加するファイル（2）
  manual.html                       申請制の入口。ナビからリンクされます。
  manual-full-7af670aa1f36e498.html   社内用の全45章。どこからもリンクしません。

■ 上書きするファイル（1）
  sitemap.xml   projectmap.html を削除し manual.html を追加（社内用は未掲載）

■ アップロードしないもの（このフォルダには入れていません）
  manual-rekey.html   パスワード変更ツール
  _運用メモ.txt        パスワードと社内用URLが書いてあります

■ アップロード後の確認
  1. https://dcplatform.jp/manual.html で申請フォームを1件送信し、
     Formspree に届くか確認（初回は迷惑メール扱いを確認）
  2. 同じページでパスワードを入れ、本文が開くか確認
  3. 社内用URLを開き、赤いバナーと全45章が出るか確認
  4. Google Search Console で projectmap.html の削除を送信（任意）
