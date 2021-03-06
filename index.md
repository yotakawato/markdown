# まず最初に

- ネイティブアプリとWebサイト（ネイティブアプリのWebView実装含む）では実装方法が異なります。ご自身のメディアに合わせた導入方法を選択して下さい。

## ネイティブアプリの場合

- ネイティブアプリへの導入にはSDK実装とJavaScript実装の2つがあります。

### SDKダウンロード

- ネイティブアプリのUIコンポーネントを利用している場合はSDKで実装して下さい。
    - [iOS用SDKダウンロード](https://github.com/mtburn/MTBurn-iOS-SDK-Install-Guide/releases)（Github）
    - [Android用SDKダウンロード](https://github.com/mtburn/MTBurn-Android-SDK-Install-Guide/releases)（Github）
- ネイティブアプリ内のWebViewを利用している場合はJavascriptで実装して下さい。
    - [Web用JavaScript実装マニュアル](https://github.com/mtburn/MTBurn-JavaScript-SDK-Install-Guide/blob/master/Programming_Guide.md)（Github）

### SDK導入マニュアル

- [iOS用SDK導入マニュアル](https://github.com/mtburn/MTBurn-iOS-SDK-Install-Guide/blob/master/Programming_Guide.md)（Github）
- [Android用SDK導入マニュアル](https://github.com/mtburn/MTBurn-Android-SDK-Install-Guide/blob/master/Programming_Guide.md)（Github）
- [Web用JavaScript実装マニュアル](https://github.com/mtburn/MTBurn-JavaScript-SDK-Install-Guide/blob/master/Programming_Guide.md)（Github）


## Webサイトの場合

- Webサイトへの導入は原則JavaScriptのみとなります。
    - [Web用JavaScript実装マニュアル](https://github.com/mtburn/MTBurn-JavaScript-SDK-Install-Guide/blob/master/Programming_Guide.md)


# 媒体社様用 管理画面

- 提携申請頂いたメディア様には広告枠の設定や収益確認のための管理画面を発行させて頂いております。

## ホーム画面

- 管理画面ログイン後に最初に表示されるページです。

### 報酬額確認

- 今日、昨日、今月、先月の報酬金額
- 先月の確定報酬金額：○営業日までには確定致します。
    - こちらの金額の数値がお振込対象金額となります。
    - 報酬金額は税込となります。

### お知らせについて

- M.T.Burn からのお知らせとなります。
- 新機能のリリース、障害報告等、こちらからご連絡させていただいております。

![](./_images/image_0.png)

## メディア画面

- 各メディアの登録、メディア別の報酬金額の確認に関してはこちらから行います。

![](./_images/image_1.png)

## レポート画面

- 配信に紐づく詳細データの抽出が可能となっております。
※ 簡易版のデータ抽出に関しては、各ページからも行えます。

- 配信実績
    - 配信実績タブからは、メディアパートナーアカウント全体の数値抽出が可能です。
    - 抽出したい項目にチェックし、CSV ファイルをダウンロードいただけます。

![](./_images/image_2.png)

- 個別成果データ
    - 個別成果データタブからは、メディア別、広告枠別、広告種別別、配信フォーマット別でクリックデータ抽出が可能です。
    - 抽出したい項目にチェックし、CSV ファイルをダウンロードいただけます。

![](./_images/image_3.png)

## アカウント設定画面

- メディアパートナー様の各種情報を登録いただく画面となっております。
- 入金口座の登録やパスワードの変更が可能です。
    - メディアパートナー
        - 社名、担当者様名、メールアドレスの登録 / 変更が可能です。
        - 登録の際に未記入だった場合、こちらからご登録いただけます。

        ![](./_images/image_4.png)

    - お支払い設定
        - 確定報酬額の入金口座の登録をお願い致します。
        - 設定いただいた口座に規定の支払いサイトに基づき入金致します。

        ![](./_images/image_5.png)

    - パスワード管理
        - メールで自動発行させていただいたパスワードから変更する際には、こちらから変更いただけます。
        ※ 変更いただいたパスワードに関しては、弊社側では管理していない為、大切に保管をお願い致します。

        ![](./_images/image_6.png)

- 広告の許可とブロック画面
    - ブランドセーフの為の広告ブロック設定画面となります。
    - URL / カテゴリー / クリエイティブ単位でのブロックが可能となります。
        - 広告主の URL
            - URL ベースでの配信ブロックが可能となります。
            ![](./_images/image_7.png)

        - カテゴリー
            - 広告主カテゴリーベースでの配信ブロックが可能となります。
            - こちらのリストにないカテゴリーについての指定ブロックはいただけません。

            ![](./_images/image_8.png)

        - 広告レビュー
            - 実際に配信されたクリエイティブ単位での配信ブロックが可能となります。

            ![](./_images/image_9.png)

# 配信開始までの流れについて

- 配信開始するまでには、下記の登録 STEP が必要となっております。
    - 新規メディア登録
    - メディア審査
    - 新規広告枠 ID 登録
    - メディアへのタグ設置
    - 案件紐付け（本番化）
    - 配信開始

## 新規メディア登録

- 管理画面にログインいただき、メディア一覧画面から「メディアの新規登録」のボタンを押していただきます。ボタンを押していただくと、メディア登録画面が表示されます。以下項目を入力していただき、保存ボタンを押していただくことでメディアの登録が完了します。

![](./_images/image_10.png)

![](./_images/image_11.png)

1. メディア名
    - 今回配信いただくメディア名の登録をお願い致します。
2. メディア種別
    - 登録されるメディアの種別に合わせて登録をお願い致します。
        - メディア種別が異なる場合に関しては、メディアを複数登録いただく必要がございます。
        - 区分は  iOS APP / Android APP / Mobile Web / の 3 つとなります。
        - App webView への配信の場合、Mobile Web での登録が必要となります。ご注意下さい。
    - アプリの場合（iOS App / Android App）に関しては、下記ステータスの記載をお願い致します。
        - アプリのリリース状況
        - アプリ識別子

        ![](./_images/image_12.png)

3. カテゴリーの登録
    - 下記カテゴリーより選択ください。

    ![](./_images/image_13.png)

※ **現在、18 禁カテゴリーに関しては、配信 NG とさせていただいております。**

4. 媒体 URL の登録
- サイト TOP ページの URL を登録ください。
    - アプリの場合はストア URL を登録ください。
    - リリース前のアプリの場合に関しては、仮の情報で登録をお願い致します。予定されている「アプリ名 / サイト名」等の必要情報を入力頂くことで申請が可能です。
    - 開発中アプリについては下記 URL で申請頂き、審査通過次第、本番のURL の変更をお願い致します。
        - iOS: [https://itunes.apple.com/](./_images/https://itunes.apple.com/)
        - Android: [https://play.google.com/](./_images/https://play.google.com/)
    - 過去実績の少ないパートナー様の場合、アプリの詳細について質問し審査を行う場合もございます。予めご了承下さい。

5. 画像イメージ（任意）
    - こちらは任意の項目となります。
    - サイトロゴなどを登録ください。
        - 50KB までアップロード可能

6. ステータス
- 有効のまま、保存をお願いします。

## メディア審査について

- 新規メディア登録後、ステータスが「審査中」の状態で管理画面に登録されます。メディア審査完了後、広告枠 ID の発行が可能になりますので、登録後しばらくお待ち下さい。
- メディア登録後、３営業日経過後もステータスに変更がない場合に関しては、お問い合わせください。

![](./_images/image_14.png)

- ステータスに関しては 4 種類ございます。
    - 承認 : メディア審査が完了した状態
    - 審査待ち : メディア審査に取りかかる前の状態
    - 審査中 : メディア審査に取りかかっている状態
    - 非承認 : メディア審査の結果、弊社基準に適合しないメディアと判断された状態


## 新規広告枠 ID 登録について

### web メディア / インフィード広告（メディア種別：Mobile Web / WebView App）

- メディア名をクリックすると、メディア画面に遷移します。広告枠 ID に関しては、 「広告枠の新規登録」ボタンより行います。

![](./_images/image_15.png)

- 「広告枠の新規登録」ボタンを押していただくと、広告枠登録画面が表示されます。
    - 以下項目を入力していただき、保存ボタンを押していただく事で広告枠が登録され、広告枠 ID が発行されます。

![](./_images/image_16.png)

1. 広告枠名
    - 配信に活用する広告枠名となります。
    - 効果検証がしやすいよう、設置箇所などに紐づいたわかりやすい命名規則にしていただく事をオススメさせていただきます。
        - 例）記事詳細ページヘッダー部、TOP ページフィード内 …

2. 広告種別
    - 設置する面に合わせ、発行タグを以下より選択ください。
        - InFeed（114 × 114 , 640 × 200, 640 × 320）

3. 表示案件数
    - 1 ページ、１つのタグで読み込む最大案件数を入力ください。
    ※ この広告枠 ID を使って設置する広告枠が 1 ページ内に 2 つの場合は 2 , 3 つの場合は 3 となります。

4. 表示位置
    - 表示位置に関しては、リストビュー型コンテンツの際に広告が何段目に表示されるかを示しております。段数が確定していない場合、コンマ区切りで表示個数分数字を並べていただければと思います。
    - 広告枠の登録が完了すると、広告枠 ID が生成されます。こちらの枠 ID を導入手順書の ID の箇所に設置いただくと配信が可能になります。
    - 導入手順書については以下 URL をご確認いただければと思います。
        - https://github.com/mtburn/MTBurn-JavaScript-SDK-Install-Guide/blob/master/Programming_Guide.md
        - 導入手順書内の ID 部分を、管理画面から発行した ID に変更いただければと思います。

5. ステータス
    - 有効のまま、保存をお願いします。

### web メディア（メディア種別：Mobile Web / WebView App）

- 設置方法は導入手順書を参照ください。
    - 導入手順書については以下 URL をご確認いただければと思います。
        - https://github.com/mtburn/MTBurn-JavaScript-SDK-Install-Guide/blob/master/Programming_Guide.md
        - 導入手順書内の ID 部分を、管理画面から発行した ID に変更いただければと思います。


#### 案件紐付け（本番化）について

- 広告枠設置完了後、弊社までご連絡いただければと思います。
    - 弊社側で配信案件の設定をし、配信が可能になります。

### App メディア / インフィード広告（メディア種別：iOS App / Android App ）

- メディア名をクリックすると、メディア画面に遷移します。広告枠 ID に関しては、 「広告枠の新規登録」ボタンより行います。
- 「広告枠の新規登録」ボタンを押していただくと、広告枠登録画面が表示されます。
    - 以下項目を入力していただき、保存ボタンを押していただく事で広告枠が発行されます。
        1. 広告枠名
            - 配信に活用する広告枠名となります。
            - 効果検証がしやすいよう、設置箇所などに紐づいたわかりやすい命名規則にしていただく事をオススメさせていただきます。
                - 例）記事詳細ページヘッダー部、TOP ページフィード内 …

        2. 広告種別
            - 設置する面に合わせ、発行タグを以下より選択ください。
                - InFeed（114 × 114 , 640 × 200, 640 × 320）
        3. 表示フォーマット
            - 設置する形式に合わせ、下記フォーマットより選択ください
                - Thumbnail Middle
                - Thumbnail Small
                - Text Only
                - WebView
                - Customize
                    - 柔軟にカスタム対応が可能なためオススメです。

                    ![](./_images/image_17.png)
        4. 表示案件数
            - 1 ページ、１つのタグで読み込む最大案件数を入力ください。
            ※この広告枠 ID を使って設置する広告枠が 1 ページ内に 2 つの場合は 2 , 3 つの場合は 3 となります。
        5. 表示位置
            - 表示位置に関しては、リストビュー型コンテンツの際に広告が何段目に表示されるかを示しております。段数が確定していない場合、コンマ区切りで表示個数分数字を並べていただければと思います。
            - 広告枠の登録が完了すると、広告枠 ID が生成されます。こちらの枠 ID を導入手順書の ID の箇所に設置いただくと配信が可能になります。
                - 導入手順書については以下 URL をご確認いただければと思います。
                    - iOS: https://github.com/mtburn/MTBurn-iOS-SDK-Install-Guide
                    - Android: https://github.com/mtburn/MTBurn-Android-SDK-Install-Guide
                - 導入手順書内の ID 部分を、管理画面から発行した ID に変更いただければと思います。

### Appメディア / インタースティシャル広告（メディア種別：iOS APP/Android APP）

- メディア名をクリックすると、メディア画面に遷移します。広告枠 ID に関しては、 「広告枠の新規登録」ボタンより行います。
- 「広告枠の新規登録」ボタンを押していただくと、広告枠登録画面が表示されます。
    - 以下項目を入力していただき、保存ボタンを押していただく事で広告枠が発行されます。

    ![](./_images/image_18.png)

1. 広告枠名
    - 配信に活用する広告枠名となります。
    - 効果検証がしやすいよう、設置箇所などに紐づいたわかりやすい命名規則にしていただく事をオススメさせていただきます。
        - 例）記事詳細ページヘッダー部、TOP ページフィード内 …

2. 広告種別
    - 設置する面に合わせ、発行タグを以下 4 種類より選択ください。
        - インタースティシャル（Phone / Tablet）、InFeed（114 × 114 , 640 × 200, 640 × 320）
        - インタースティシャル(Phone)/ (Tablet)を選択
        ※ SPアプリの場合 Phone のみでも問題ありません。
        ※ Tablet も実装した場合、タブレット用に入稿された広告素材がある場合は、それが配信されます。

3. 表示頻度
    - スキップ回数（回） と 間隔時間（秒）で制御可能です。
    - いずれかを選択し、 「程度」へ制御したい数値を⼊⼒してください。

4. 程度

5. 表示頻度（初回）
    - 起動後、初回の広告表示のタイミングについては別途制御可能です。

6. 程度（初回）
    - 表示頻度設定は任意となり、いつでも変更可能です。

7. ステータス
    - 有効のまま、保存をお願いします。

### App メディア（メディア種別：iOS App / Android App ）

- 設置方法は導入手順書を参照ください。
    - 導入手順書については下記 URL をご確認いただければと思います。
        - iOS: https://github.com/mtburn/MTBurn-iOS-SDK-Install-Guide
        - Android: https://github.com/mtburn/MTBurn-Android-SDK-Install-Guide

#### 案件紐付け（本番化）について

- 設置完了後、弊社までご連絡いただければと思います。
    - 弊社側で本番用配信案件の設定をし、配信が可能になります。

# 配信開始後の流れについて

## ブランドセーフ機能

- ブランドセーフ機能として、広告の許可・ブロック機能がございます。
    - 許可・ブロック機能に関しては、大きく分けて以下 3 つの方式がございます。
        - URL ベースでのブロック
        - カテゴリー単位での許可・ブロック
        - クリエイティブ単位での許可・ブロック

## URL 単位でのブロックについて

- URL 単位での広告ブロック機能について
    - 特定の URL ベースで広告主のブロックをする事が可能となっております。
    - 広告レビューの画面にて、実際に配信されたクリエイティブと遷移先 URL を確認する事が可能となっており、配信実績から特定広告主の配信を停止する事も可能です。
    ※ パフォーマンス調整の為に停止してしまうと、最適化機能が効かなくなり、収益性の低下が発生する可能性がございます。

    ![](./_images/image_19.png)

- URL 単位でのブロックルールについて
    - 指定する URL の記述により、ブロックされる範囲が変化致します。
        - 「mtburn.jp」 で指定
            - mtburn.jp → 停止
            - www.mtburn.jp → 停止
            - sample.mtburn.jp → 停止
        - 「www.mtburn.jp」で指定
            - mtburn.jp → 配信
            - www.mtburn.jp → 停止
            - www.mtburn.jp/test → 停止
            - sample.mtburn.jp → 配信
        - 「www.mtburn.jp/test」で指定
            - mtburn.jp → 配信
            - www.mtburn.jp → 配信
            - www.mtburn.jp/test → 停止
            - sample.mtburn.jp → 配信

## カテゴリー単位でのブロックについて

- 広告主カテゴリー単位でのブロックも可能となっております。
    - 配信 NG のカテゴリーを選択いただき、ブロック指定を致します。
    - 対象カテゴリーに属している広告主の現在配信されている割合を確認する事も可能です。
    - 関連するすべての広告主を防止する事は保証されません。その為、NG カテゴリーに含まれる広告主の配信が確認されましたら URL 単位でのブロックをお願い致します。

    ![](./_images/image_20.png)

    - 現状設定可能なカテゴリーは以下の通りです。
    ※ テスト期間につき、ブロック対象カテゴリー・名称が変化する可能性はございます。

    ![](./_images/image_21.png)

## 広告レビュー（クリエイティブ単位でのブロック）について

- 実際に配信されたクリエイティブを確認し、ブロックが可能となります。
- ブランドセーフの観点で特定のクリエイティブをブロックしたい場合に関しては、こちらから停止ください。
※ パフォーマンスの為に停止してしまうと、最適化機能が効かなくなり、収益性の低下が発生する可能性がございます。

![](./_images/image_22.png)

## タグ発行広告テンプレート機能について

- タグの記述を変更する際に、タグの張り替えが必要ありません。
    - タグの張り替えが必要ないので、色やフォントなどを管理画面上から変化させる事が可能です。
    - それにより工数を削減出来るだけでなく、A/Bテストなどの検証が実施しやすくなります。

- 管理 UI から広告テンプレートを入稿します。
    - 挿入予定箇所のフィード１個分の HTML を抜き出し、左箇所にコピーアンドペーストして、導入手順書同様、各要素をマクロに変更いただきます（※ 対応出来ないケースもございます）。
    - 例えば下記のように「タイトル」に置き換えたい項目である「M.T.Burn の AppDavis！」という箇所をドラッグしていただき、 「← 挿入」ボタンを押すと該当箇所が```{{title}}``` という記述に変わり、その部分が広告素材（タイトル文）に置き換えられ、広告として表示されます。
    - 他要素（例の場合は```{{description}}```、```{{main_image_url}}```、）も同様にマクロに変換いただきます。
    - 完了したら「保存」ボタンをクリックいただきます。作成完了後、「タグ発行」ボタンをクリックいただきます。タグ発行ボタンより、設置するタグが発行いただけます。

### Title / description の長さの調整について

- 最大文字数の項目に 20 文字であれば 「20」と記述をお願い致します。
- 広告を表示したい箇所にそのままコピーアンドペーストで貼付けて頂くと広告の表示が出ます。

- タグ発行後、再度タグの編集をしたい場合は、編集からメディアのタグを張り替えること無く、ボックスのHTMLを編集するだけで広告の表示を変えることが可能です。

## レポート機能について

- 配信に紐づく詳細データの抽出が可能となっております。
    - 簡易版のデータ抽出に関しては、各ページからも行えます。
    - レポートは csv データで抽出されます。
- 配信実績
    - 配信実績タブからは、パブリッシャーアカウント全体の数値抽出が可能です。
    - 表示軸や表示項目を選択いただく事により、抽出されるデータが変化致します。
        - 表示軸
            - メディア：メディア名がレポート csv に加わります。
            - 広告種別：広告主別がレポート csv に加わります。
            - 表示フォーマット：表示フォーマットがレポート csv に加わります。（アプリのみ）
            - 広告枠：広告枠 ID の表記と広告枠名がレポート csv に加わります。
        - 表示項目
            - デフォルト設定は全てにチェックが入っております。

            ![](./_images/image_23.png)

- 個別成果データ
    - 個別のメディア
    - 個別の広告枠
    - 個別の広告種別
    - 配信フォーマット別
    でクリックデータ抽出が可能です。

    ![](./_images/image_24.png)
