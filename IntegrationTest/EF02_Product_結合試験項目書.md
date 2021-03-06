# EF02_Product_結合試験項目書

## EF0201-UC01-T01_商品一覧ページ（初期表示）

1. TOPページ→商品一覧
1. TOPページ>商品一覧（ヘッダーのいずれかのカテゴリを選択）へ遷移
1. 登録商品がカテゴリごとに一覧表示される
1. 一覧ページで商品がサムネイル表示される

## EF0201-UC01-T02_商品一覧ページ（ヘッダー側でないカテゴリのリンク押下）

1. TOPページ→商品一覧
1. TOPページ>商品一覧（ヘッダーのいずれかのカテゴリを選択）へ遷移
1. 登録商品がカテゴリごとに一覧表示される
1. ヘッダー側のカテゴリに紐づく子カテゴリをリンクをして表示する。
1. 選択されたカテゴリリンクにカテゴライズされている商品のサムネイルが表示される

## EF0201-UC03-T01_商品一覧ページ（ソート）

1. TOPページ→商品一覧
1. TOPページ>商品一覧（ヘッダーのいずれかのカテゴリを選択）へ遷移
1. 各商品のサムネイルが表示される
1. ソート条件の選択リストを変更する
1. 変更されたソート条件に従い、商品がソートされる

## EF0201-UC04-T01_商品一覧ページ（表示件数）

1. TOPページ→商品一覧
1. TOPページ>商品一覧（ヘッダーのいずれかのカテゴリを選択）へ遷移
1. 各商品のサムネイルが表示される
1. 表示件数の選択リストを変更する
1. 変更された表示件数分が1画面に表示される

## EF0201-UC04-T02_商品一覧ページ（ページング）

1. TOPページ→商品一覧
1. TOPページ>商品一覧（ヘッダーのいずれかのカテゴリを選択）へ遷移
1. 各商品のサムネイルが表示される
1. 絞込検索条件では、検索数が多い場合、「次へ」「前へ」「ページ番号」が表示される
1. 「次へ」「前へ」「ページ番号」リンクをそれぞれ押下する
1. 選択されたリンクに応じてページングされる

## EF0202-UC01-T01_商品詳細（初期表示）
1. 任意の商品の在庫を0にする
1. TOPページ→商品一覧→商品詳細
1. TOPページ>商品一覧>商品詳細へ遷移
1. 「カートに入れる」ボタンが、非活性となり「ただいま品切れ中です」と表示される。

## EF0202-UC01-T02_商品詳細（カテゴリリンク）

1. TOPページ→商品一覧→商品詳細
1. TOPページ>商品一覧>商品詳細へ遷移
1. 商品詳細の関連カテゴリに表示されている、カテゴリリンクを押下する
1. 選択されたカテゴリの商品一覧画面へ遷移する。

## EF0202-UC01-T03_商品詳細（サムネイル画像選択）

1. TOPページ→商品一覧→商品詳細
1. TOPページ>商品一覧>商品詳細へ遷移
1. 小さく表示されている幾つかのサムネイルの中から画像をクリックする。
1. クリックされた画像が大きく表示される。

## EF0202-UC02-T01_商品詳細（カートに入れる・注文数＜販売制限数＜在庫数の注文）※商品に、在庫量/販売制限数を設定

1. TOPページ→商品一覧→商品詳細
1. TOPページ>商品一覧>商品詳細へ遷移
1. 「カートに入れる」ボタンを押下する
1. カート画面に遷移する
1. 入力された個数分が、カート画面の対象商品に追加されている。

## EF0202-UC02-T02_商品詳細（カートに入れる・販売制限数＜注文数＜在庫数の注文）※商品に、在庫量/販売制限数を設定

1. TOPページ→商品一覧→商品詳細
1. TOPページ>商品一覧>商品詳細へ遷移
1. 「カートに入れる」ボタンを押下する
1. カートの数量に販売制限数が設定され、注文数が販売制限数を上回っている旨のメッセージを表示する。
1. カート画面に遷移する

## EF0202-UC02-T03_商品詳細（カートに入れる・販売制限数＜在庫数＜注文数の注文）※商品に、在庫量/販売制限数を設定

1. TOPページ→商品一覧→商品詳細
1. TOPページ>商品一覧>商品詳細へ遷移
1. 「カートに入れる」ボタンを押下する
1. カートの数量に販売制限数が設定され、注文数が販売制限数を上回っている旨のメッセージを表示する。
1. カート画面に遷移する

## EF0202-UC02-T04_商品詳細（カートに入れる・注文数＜販売制限数＜在庫数の注文）※規格に、在庫量/販売制限数を設定

1. TOPページ→商品一覧→商品詳細
1. TOPページ>商品一覧>商品詳細へ遷移
1. 「カートに入れる」ボタンを押下する
1. カート画面に遷移する
1. 入力された個数分が、カート画面の対象商品に追加されている。

## EF0202-UC02-T05_商品詳細（カートに入れる・販売制限数＜注文数＜在庫数の注文）※規格に、在庫量/販売制限数を設定

1. TOPページ→商品一覧→商品詳細
1. TOPページ>商品一覧>商品詳細へ遷移
1. 「カートに入れる」ボタンを押下する
1. カートの数量に販売制限数が設定され、注文数が販売制限数を上回っている旨のメッセージを表示する。
1. カート画面に遷移する

## EF0202-UC02-T06_商品詳細（カートに入れる・販売制限数＜在庫数＜注文数の注文）※規格に、在庫量/販売制限数を設定

1. TOPページ→商品一覧→商品詳細
1. TOPページ>商品一覧>商品詳細へ遷移
1. 「カートに入れる」ボタンを押下する
1. カートの数量に販売制限数が設定され、注文数が販売制限数を上回っている旨のメッセージを表示する。
1. カート画面に遷移する


## EF0202-UC03-T01_商品詳細（在庫切れ）

1. TOPページ→商品一覧→商品詳細
1. TOPページ>商品一覧>商品詳細へ遷移
1. 「カートに入れる」ボタンを押下する
1. カートの数量に在庫数が設定され、在庫が不足している旨のメッセージを表示する。
1. カート画面に遷移する
