Changelog
=========

##version 1.3
  * ツリーのクローズボタンを廃止

##version 1.2.1 (2013-03-12)
  * [#98 Firefox 22+ のnsISupportsArray削除対応](https://github.com/teramako/Pano/issues/98)

##version 1.2 (2012-12-29)
  * [#71 パネルのサイズを可能にして欲しい](https://github.com/teramako/Pano/issues/71)
  * [#78 ツリー空白部分もドラッグ＆ドロップ可能に](https://github.com/teramako/Pano/issues/78)
  * [#79 セッションのエクスポート/インポート機能](https://github.com/teramako/Pano/issues/79)
  * [#80 ツリーのインデント幅を明示](https://github.com/teramako/Pano/issues/80)
  * [#87 パネルボタンのマウスオーバーでポップアップする機能](https://github.com/teramako/Pano/issues/87)
  * [#88 パネルのテーマをPersonasのテーマに合うように](https://github.com/teramako/Pano/issues/88)
  * [#89 サイドバーにPersoasのテーマを適用](https://github.com/teramako/Pano/issues/89)

##version 1.1 (2012-05-29)
  * [#74 ツリーの空白部分をダブルクリックで新規グループを作成できるように](https://github.com/teramako/Pano/issues/74)
  * [#75 新規タブを開いた時、URLバーにフォーカス](https://github.com/teramako/Pano/issues/75)
  * [#76 タブグループの閉じるメニューは危険だ](https://github.com/teramako/Pano/issues/76)
    * 要望とは異なるが、確認ダイアログを出すように修正
  * [#77 現在グループ以外を自動で閉じる機能が欲しい](https://github.com/teramako/Pano/issues/77)
  * BugFix
    * [#72 フィルターを解除後、ツリーのツリーのアイテム数がおかしくなる](https://github.com/teramako/Pano/issues/72)

##version 1.0 (2012-02-29)
  * [#69 並び替えたグループの順番を再起動後も維持したい](https://github.com/teramako/Pano/issues/69)
  * CSS エディタからアイコンの変更を可能に
  * [#70 現在のタブを選択するようにして欲しい](https://github.com/teramako/Pano/issues/70)
    * `extensions.pano.select_currenttab` オプションの追加(default: true)  
      タブ選択が切り替わった時、そのタブの行が自動で選択された状態になります

##version 0.12.1 (2012-02-02)
  * 「Firefox起動直後のツリー構築速度を改善」関連コミットをリバート

##version 0.12 (2012-01-28)
  * Firefox起動直後のツリー構築速度を改善
  * [#60 ツールバーのタブ選択履歴で任意のタブを選択できるように](https://github.com/teramako/Pano/issues/60)
    * タブ履歴のボタンにメニューを追加しました
  * [#64 「スタイルエディタ」という名前は Firefox 11 のと同じ名前になってしまう](https://github.com/teramako/Pano/issues/64)
    * 「CSSエディタ」に変更
  * [#65 暗いテーマの場合にPanoのボタンが見え難い](https://github.com/teramako/Pano/issues/65)
  * [#68 ブランクグループを削除するボタンを追加](https://github.com/teramako/Pano/issues/68)

##version 0.11 (2011-11-29)
 * [#50 タブの状態に応じた更なるスタイリング (提案)](https://github.com/teramako/Pano/issues/50)
   * スタイルエディタを実装
   * タブが読み込み中の時に`loading`プロパティを追加 (デフォルトでは読み込み中のアイコンになる)
   * タブのタイトルが変わったことを示す`titlechanged`プロパティを追加 (デフォルトではラベルが斜体になる)
 * [#58 アクティブなタブが変更された時、ツリーをスクロールさせてそのタブアイテムが表示されるようにしました](https://github.com/teramako/Pano/pull/58)
   * 貢献者として mooz さんを追加
 * [#59 起動時にサイドバー内のタブが見えているように](https://github.com/teramako/Pano/pull/59)
 * BugFix
   * [#57 起動直後のサイドバーで開いているグループ内のタブが表示されない](https://github.com/teramako/Pano/issues/57)

##version 0.10 (2011-10-30)
 * 諸事情により、サポート対象を Firefox 7.0 からに変更
 * [#36 コンテキストメニューに再読込をするメニューを追加](https://github.com/teramako/Pano/issues/36)
 * [#37 コンテキストニューにグループ内の全タブをブックマークするメニューを追加](https://github.com/teramako/Pano/issues/37)
 * [#44 各ボックスのツールバー化](https://github.com/teramako/Pano/issues/44)
   * 「フィルター」や「タブバーを隠す」ボックスをツールバー化して表示/非表示を切り替えられるようにした
   * 「フィルター」アイテムのラベルを廃止し、プレイスホルダーに変更した
 * [#34 miscs](https://github.com/teramako/Pano/issues/34)
   * タブ番号を付加するオプションを追加
   * ツールチップのタイトルとサムネイルを表示/非表示を可能にした
 * [#35 miscs](https://github.com/teramako/Pano/issues/35)
   * 「タブバーを隠す」チェックボックスをボタンにしてアイコンを追加
   * タブの選択履歴を戻る/進むボタンの実装
   * ツリーのグループ全てを展開/折り畳むボタンの実装
 * FixBug
   * [#40 空白の行ができる](https://github.com/teramako/Pano/issues/40)
   * [#41 アクティブでないグループのタブを閉じる](https://github.com/teramako/Pano/issues/41)
   * [#42 url や title が 非常に長いときに tooltip の サムネイル画像の 拡大について](https://github.com/teramako/Pano/issues/42)
     * ツールチップの幅を固定にした
   * [#45 GI.getOrphanedTabs is not a function](https://github.com/teramako/Pano/issues/45)
   * [#46 コンテキストメニューとサムネイル画像が重なって表示される](https://github.com/teramako/Pano/issues/46)
   * [#47, #48 閉じたタブの復元をした時、ツリーのリストが更新されないことがある](https://github.com/teramako/Pano/issues/47)
   * [#51 サブ・コンテンツが非表示状態に戻ってしまう](https://github.com/teramako/Pano/issues/51)

##version 0.9 (2011-09-29)
 * LessChrome HD と「タブバーを隠す」設定の互換性を向上
 * ツリーに閉じるボタンを追加
   * about:config `extensions.pano.showCloseButton` で設定可
 * `extensions.pano.swichTabBySingleClick` のタイポ修正
   -> `extensions.pano.switchTabBySingleClick`
 * オプションダイアログの追加
 * [#26 ページ内リンク等をツリー上にD&Dして開く機能](https://github.com/teramako/Pano/issues/26)
   * ブックマークやブックマークフォルダ、ページ内のリンクをツリーにドロップできるようにした
   * アクティブなグループ内へドロップした場合、バックグランドで開かれるかどうかは`browser.tabs.loadInBackground`に依存
   * アクティブでないグループ内へのドロップではバックグラウンドで開く
   * 複数を開く場合、数が`browser.tabs.maxOpenBeforeWarn`以上である場合、プロンプトがポップアップするようにした
   * バックグラウンドで開かれるタブはロードせず、アクティブになった時にロードされるようにした
   * パネルの挙動を変更し、メニューが開かれるときは閉じないようにした
 * [#29 Panoパネルからタブを切り替えた時にパネルを自動的に閉じる機能](https://github.com/teramako/Pano/issues/29)
   * about:config の値 `extensions.pano.panel.autoCloseByTabSelect` を追加した
 * BugFix: [#27 アクティブなアブを含む複数のタブをドロップした時、コンテンツのロードが発生する](https://github.com/teramako/Pano/issues/27)
   * アクティブなタブは他を移動し終わった後に移動するように変更
 * BugFix: [#31 閉じるボタンがスクロールバーに隠れる](https://github.com/teramako/Pano/issues/31)

##version 0.8 (2011-08-28)

 * Firefox 9.0a1 をサポート対象に追加
 * [#19: タブバーを隠す機能を追加](https://github.com/teramako/Pano/issues/19)
   * サイドバーが開いているときのみ
   * サイドバー下部のチェックボックスから設定可能
 * [#21: ダブルクリックではなく1クリックでタブにスイッチ](https://github.com/teramako/Pano/issues/21)
   * about:config の `extensions.pano.swichTabBySingleClick` を `true` に設定すると可能
 * [#22: 中ボタンクリックでタブを閉じる機能](https://github.com/teramako/Pano/issues/22)
 * BugFix: [#24: Panoパネル・ボタンによるトグル開閉](https://github.com/teramako/Pano/issues/24)
   * Panoパネルのボタンをクリックした時、既に開いている時は閉じるように修正
 * BugFix: [#25: アクティブグループの最後のタブを閉じた時の挙動](https://github.com/teramako/Pano/issues/25)
   * Panoramaのビューが開いたとき、Panoパネルが開いていたら閉じるように修正

##version 0.7 (2011-07-29)

 * バグ修正
   * [#13: Can't drop tabs to the AppTabsGroup](https://github.com/teramako/Pano/issues/13)
   * [#15: 非アクティブグループのタブを閉じた後の不整合](https://github.com/teramako/Pano/issues/15)
   * [#17: Auroraで動作しなかった不具合](https://github.com/teramako/Pano/issues/17)
   * [#18: 「他のパソコンで開いていたタブ」項目が増殖する](https://github.com/teramako/Pano/issues/18)
 * コンテキストメニュー
   * [#14: "Close all selected" in the context menu](https://github.com/teramako/Pano/issues/14)
   * [#16: 「新しいタブを開く」メニューの追加](https://github.com/teramako/Pano/issues/16)

##version 0.6 (2011-07-07)

 * 主にバグ修正 [#7](https://github.com/teramako/Pano/issues/7) [#8](https://github.com/teramako/Pano/issues/8)
   [#9](https://github.com/teramako/Pano/issues/9) etc...
 * [Firefox 8.0a1 対応](https://github.com/teramako/Pano/issues?state=closed&page=1&milestone=3)

##version 0.5

 * サイドバーとパネルタブにフィルタ機能(検索ボックス)を追加
   * `*` がワイルドカード
   * `|` が OR 検索
   * なお、フィルタリング中はドラッグ＆ドロップできません
 * ポップアップパネルでツリー表示をするボタンを追加
   * ボタンは「ツールバーのカスタマイズ」にある
   * アクセスキーは Alt + p

##version 0.4

 * グループが閉じられた時、サイドバーのツリーからグループを削除するようにした
 * サイドバーのキーボードナビゲーション
   * _ENTER_: タブの選択
   * _F2_: グループの編集
 * サイドバーにコンテキストメニューを追加
   * 新しいグループ
   * タブやタブグループを閉じる
   * サイドバーを閉じる
 * Panoボタンをメニューボタンに変更
   * メニューにタブグループを表示
 * サイドバーのDrag&Dropを改良
   * 複数のタブをDrag可能に（グループは不可）
   * 1グループをDrag可能に
 * [サイドバーのツリーの開閉状態を保存するようにした](https://github.com/teramako/Pano/issues/2)
 * Bug fix
   * https://github.com/teramako/Pano/issues/1
 
##version 0.3

 * サイドバーの開閉をするボタンを追加（ツールバーのカスタマイズから追加可能）
 * サイドバーの開閉するショートカットを追加
   * Windows, Linux: Ctrl + Alt + p
   * Mac OS X: Cmd + Option + p
 * サイドバーのツリーでグループの開閉をできるようにした

##version 0.2

 * タブ一覧メニューに他グループのタブを選択できるようなメニューを追加
 * アドオンアイコン追加

##version 0.1

 * 新規リリース（α版）

