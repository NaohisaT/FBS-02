AIエージェント操作プロンプト v2（Chromium / リモートブラウザ対応）  
以下の手順を順番どおりに実行すること。  
---

1\. Google Drive にアクセス  
URL：  
 [https://drive.google.com/drive/folders/1\_uobqgrYB75Kj-edaFsF4h4nMQVJx6MX?usp=drive\_link](https://drive.google.com/drive/folders/1_uobqgrYB75Kj-edaFsF4h4nMQVJx6MX?usp=drive_link)  
ログインが必要な場合は以下を入力する：

* ID: recesta1@falco.co.jp  
* PASS: Falco-9999

反応が遅いので、画面遷移が遅くても、20秒は待機。それでもだめならCTRL+R

ログイン後、指定フォルダの画面が表示されるまで待つ。  
---

2\. 「依頼手段 集計報告」フォルダを開く  
フォルダ一覧から、  
 フォルダ名に「依頼手段 集計報告」を含むフォルダ をクリックして開く。  
---

3\. 更新日時を降順に並べ替える  
ファイル一覧の上部にある「更新日時」列ヘッダ（"Date modified"）をクリックする。  
・降順（最新 → 古い） になるまでクリック調整する。  
---

4\. 最も新しい .xlsx を開く  
一覧の一番上（最新）の「.xlsx」ファイルをクリックする。  
Google Sheets として自動で開かれる。  
 ※ プレビュー画面の場合は右上の「Google スプレッドシートで開く」をクリック。  
---

5\. データ範囲をコピーする

1. 2:2(2行目全選択)をクリック  
2. 2行目が選択されたことを確認してから、CTRL \+ SHIFT \+ ↓ を押して最終行まで選択  
3. 選択されたことを核にしてから、CTRL \+ C でコピー

（クリップボード保持を確認する）  
---

6\. 新しいタブを開いて「依頼報告」ブックへアクセス  
Chromium で新規タブを開き、次を開く：  
[https://docs.google.com/spreadsheets/d/1HVXGMKZKP\_GegLlk2mVfTz\_FmzHacRHAJafLuKDFTLI/edit?usp=drive\_link](https://docs.google.com/spreadsheets/d/1HVXGMKZKP_GegLlk2mVfTz_FmzHacRHAJafLuKDFTLI/edit?usp=drive_link)  
スプレッドシートの画面が表示されるまで待つ。  
---

7\. グレーアウトしているシートを表示する  
画面下部の  
 「すべてのシート（All sheets）」ボタン  
 をクリック。  
一覧から 「依頼報告」 および 「依頼報告\_顧客数」 を選び、  
 「表示する（Unhide）」 を選択して両方を表示状態にする。  
---

8\. 「依頼報告\_顧客数」にデータ貼り付け

1. 「依頼報告\_顧客数」タブへ移動

2. A1セル をクリック

3. CTRL \+ ↓ で最終行へ移動

4. さらに1つ下へ（A列の次の空行）

5. CTRL \+ SHIFT \+ V で「値のみ貼り付け」

---

9\. 重複削除（D,E,G 列のみで判定）

1. CTRL \+ A で全選択

2. メニューから  
    　「データ」→「データ クリーンアップ」→「重複を削除」

3. 表示されたダイアログで：  
   　\- 「○○まで拡張」ボタンを必ず押す。  
    　\- 「すべて選択」のチェックを外す  
    　\- D / E / G 列 のみチェック  
    　\- 「重複を削除」→「OK」

---

10\. 「依頼報告」タブへの貼り付け

1. 「依頼報告」タブへ移動

2. 10秒待機（UI描画の遅延を吸収するため）

3. A1セル → CTRL \+ ↓ → 1つ下の空行

4. CTRL \+ SHIFT \+ V で値貼り付け

---

11\. シートを非表示に戻す（画面整理のため）  
画面下部の 「すべてのシート」 を開き：

* 「依頼報告」

* 「依頼報告\_顧客数」

の両方を選び、  
 「非表示（Hide）」 を選択。  
---

🎉 以上で完了。  
