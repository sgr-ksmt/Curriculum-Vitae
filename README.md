# Curriclum Vitae
最終更新 2019/11/08

## Basic

|             |                                                                                 |
| :---------- | :------------------------------------------------------------------------------ |
| Name        | 岸本 卓(Suguru Kishimoto)                                                       |
| Blog        | [https://tech-blog.sgr-ksmt.org/](https://tech-blog.sgr-ksmt.org/)              |
| Qiita       | [@sgr-ksmt(https://qiita.com/sgr-ksmt)](https://qiita.com/sgr-ksmt)             |
| Speakerdeck | [@sgrksmt(https://speakerdeck.com/sgrksmt/) ](https://speakerdeck.com/sgrksmt/) |

## School/Job history

- 履歴書参照。
  - 中途選考等で提示が合った場合にこちらから共有させていただきます。

## Summary

- ソフトウェアエンジニア
- 主軸はiOSアプリ開発、最近はFirebaseを使ったiOS/Webフロント、バックエンド開発がメイン
- 現在3社目。現職はクックパッド株式会社
- 受託、自社サービス開発経験あり
- サービスローンチ/グロースどちらも経験あり
- iOSの開発経験(実務)8年ほど
- OSS活動もしていて、自著OSSの累計star数は800を超えている
- Qiita,技術ブロクにも定期的に投稿している
- 勉強会で時折登壇している
- 本業以外にも副業で開発業務、メンター業務、技術顧問を行っている

## Status
- 副業のみ検討中

詳細は

- [条件](conditions.md)
- [Firebaseの技術顧問でお手伝いできるところ、探しています。](https://note.com/su_k/n/n64b4ef432fc4)

をご覧ください。

## Skills

- **言語**
  - Swift
  - JavaScript / TypeScript
  - Objective-C
  - Java
  - C
  - 日本語
    - ネイティブ
  - 英語
    - 日常会話レベル
    - 海外出張はなんとかなるレベル

- **フレームワーク、XaaS**
  - RxSwift
  - React.js
  - Next.js
  - Firebase
    - ほぼ全ての機能実務経験、導入実績あり
  - AWS
  - Docker

- **ツール、その他**
  - Slack
  - GitHub
  - CI/CD(Jenkins/CircleCI/BitriseCI)
  - Sketch
  - Figma


## Job details

### クックパッド株式会社: 2017/08 ~

iOSエンジニアとして入社し、クックパッドのiOSアプリの改善と、新規事業の立ち上げに従事。  
またFirebase Dev Summit2017、WWDC2018にも出張にて参加。
現在は料理が楽しくなるマルシェアプリ「 Komerco(コメルコ) 」の開発チームリーダー兼エンジニアをしている。

| 期間                         | 内容                                                                                                                                                                                                                                                                                          | 役割/開発チーム規模                |
| :--------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------- |
| 2017/08<br />〜<br />2017/11 | 新規事業のβ版作成と検証を2つのアプリで行った。。<br />iOSアプリのみ、Firebaseを使ったMVPとして作成                                                                                                                                                                            | iOSエンジニア<br /><br /> 8名程度  |
| 2017/10<br />〜<br />2017/12 | レシピアプリ「クックパッド」の機能改善、改修。<br />細かい不具合の修正や、プレミアム献立という機能のUI変更を行った。                                                                                                                                                                          | iOSエンジニア<br /><br /> 20名程度 |
| 2017/10<br />〜<br />現在    | 料理が楽しくなるマルシェアプリ「 Komerco(コメルコ) 」の開発。<br />事業の立ち上げから現在まで開発に従事。Firebaseを用いて、iOS,Web両方の開発を行っている。<br />主にiOSでは認証周りや画面のUI設計を担当。<br />FirebaseではDBの保護をするために必要なセキュリティールールの構築を行っている。<br />現在は同事業のテックリードとしてマネジメントも行なっている。 | iOSエンジニア<br /> 8名程度        |

#### 概要(料理が楽しくなるマルシェアプリ「 Komerco(コメルコ) 」の開発)

社内で新規事業を立ち上げることになり、自ら進んで参加を表明。
(Komercoというサービスです: https://komer.co)
iOSエンジニアとして新規事業の立ち上げに携わる。
当初集まったエンジニアがiOSエンジニアのみで、バックエンド、インフラを担当するエンジニアが不在だったため、Firebaseを使って開発を行っていくことに。
サービスとしては、購入する側のアプリと、出品する側のアプリと2つ別々に開発することになり、2つ同時進行で開発。
サービスのローンチ後は、運用保守に周り、

- ローンチ時に不足していた機能の開発
- 不具合の修正
- ユーザーの行動分析から、改善すべき部分を見つけ改善する

といったことを行った。現在も引き続きiOSアプリの改善及びWebアプリケーションの開発を行いつつ、テックリードとしてメンバーのマネジメントを行ったり、開発の工数管理を行ったりしている。


##### 開発担当

他のエンジニアと、機能ごとに担当領域を分けて開発を行い、自分の担当領域としては以下のとおり。

(共通)
- Firebase Authenticationを使った認証周りの実装
- メールアドレス変更、パスワード変更、リセットの実装
- Push通知の送信機能(FirebaseのCloud Functionと絡めた実装)
- 分析ログを仕込むための仕組みの作成と導入
- Firebase Dynamic Linksを活用した、外部からアプリへの遷移導線の強化
- 商品購入、発送された場合に対象のユーザーにメールを送信する機能

(出品側)
- 出品に必要な情報、振込先口座の登録実装
- 購入された商品の管理(注文管理)実装

(購入側)
- ホーム画面(アプリのメインとなる画面)の実装
- 商品の詳細画面の実装
- 商品をカートに入れてから購入までのフローの構築
- 商品にスキ(Twitterでいういいね)の実装
- A/Bテストを行うための基盤作成(Firebase A/B Testingを活用)

(その他)
- CI環境の定期的なメンテナンス
- 新しく入っていたメンバーがすぐに開発に着手できるように、環境構築がmakeコマンド1つで済むようにセットアップscriptを作成
- SwiftLint,SwiftFormat,Dangerの導入によるコーディングスタイルの統一及びPRの効率上昇
- FirebaseのCloud Firestoreのセキュリティのルールの構築、ルールのテスト記述によるサービスのセキュリティ対策向上
- 内製のPush通知配信の仕組みに、送信後に送信した情報をBigQueryにエクスポートする仕組みを導入
- 日時で未発送になってしまっている商品をSlackに通知し、CSチームが出品者に確認が取れるような仕組みの導入


###### マネジメント
2019年の1月から、いちエンジニアという状況から事業部の開発グループのリーダーとテックリードを兼任することになり、メンバーと定期的な1on1の実施及び評価面談を行うことになった。

#### その他
会社の技術ブログにも投稿したりしている。

- [Cloud Firestoreのrulesをテストする](https://techlife.cookpad.com/entry/2018/08/16/100000)
- [Cloud Firestoreのrulesのテストを全てローカルエミュレータを使うように書き換えた話](https://techlife.cookpad.com/entry/2018/11/05/143000)

また、KomercoのサービスとFirebaseに関してインタビューを受けた。

- [Firebaseでバックエンドエンジニア不在のアプリ開発　クックパッドが体感した、メリットと課題](https://employment.en-japan.com/engineerhub/entry/2018/08/30/110000)

更に、上記のインタビュー記事を受けて、別途執筆依頼があり、下記の記事を寄稿させて頂いた

- [Firebase入門 フリマアプリを作りながら、認証・Firestore・Cloud Functionsの使い方を学ぼう！](https://employment.en-japan.com/engineerhub/entry/2019/06/07/103000)

<br /><br />

-----

<br /><br />

### 株式会社TIMERS: 2016/4 ~ 2017/07

iOSエンジニアとして入社。Famm及びPairyの機能開発、改善に従事。  
既にローンチ済みのサービスであったため、新規開発に携わることは少なかったが、既存のObjective-CのソースコードをSwiftに書き換えるのに尽力し、入社から1年ほどでObjective-C100%の状態から50%弱ほどまで推進させることができた。

| 期間                      | 内容                                                                                                                                                                                                                                                | 環境                                                                   | 役割/規模                                              |
| :------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------- | :----------------------------------------------------- |
| 2016/4<br />〜<br />現在  | Fammの新規機能開発及び機能修正を担当。<br />前職でのSwiftでの開発経験、独学での知見を活かし、<br />チームのSwiftでのコーディング力の向上や、Swift 3対応にもに取り組んだ。<br />CI環境のメンテナンス、ビルド時間の短縮、lintツールの導入等も行った。 | Mac<br />Xcode<br />Swift<br />Objective-C<br />Bitrise CI<br />Github | iOSエンジニア<br /><br />各プロジェクト<br />3~5名程度 |
| 2016/12<br />〜<br />現在 | Pairyの機能修正、ATS対応                                                                                                                                                                                                                            | Mac<br />Xcode<br />Swift<br />Objective-C<br />Bitrise CI<br />Github | iOSエンジニア                                          |

#### 概要
2016年4月に中途入社し、FammのiOSアプリの運用保守に携わる。
入社以前からSwiftを使ったアプリケーション開発をしていた経験を活かし、既存プロジェクトの大部分がObjective-Cで書かれていたものを順次Swiftに置き換える作業をメインで担当。
また、他のメンバーにSwiftでの書き方を相談やコードレビューを通して教え、メンバー全員がSwiftで開発をしていけるように支えた。
また、当時はまだSwiftのビルド時間が長くかかることが多く、Swift化したコードが増えるにつれて開発効率が落ちてきてしまっていたので、
ビルド時間短縮のために地道なコードのリファクタや、CI環境でSwiftで書かれたファイルを1つに結合してビルド時間を大幅に削減するといったtipsを見出し、開発効率の向上を行った。
(参考: https://techblog.timers-inc.com/entry/2016/07/06/183632)

また、その後は、

- アプリ内で祖父、祖母といったユーザーとの家族連携及び招待機能の実装
- A/Bテスト実施による改善
- 写真コラージュ機能の実装
- 写真一覧画面のクラッシュ問題修正


といったことを担当した。
また、一部APIの修正が必要な時に、サーバーサイドエンジニアの手が空いていないときに自らPHPで書かれたコードを修正したりもした。


#### その他
会社の技術ブログ(http://techblog.timers-inc.com/) にて、主にiOSに関する記事を投稿をしていた。  

<br /><br />

-----

<br /><br />

### 株式会社スフィダンテ: 2011/10 ~ 2016/3 : インターン→正社員

| 期間                        | 内容                                                                                                                                                                                                                                                                                                                                                                                         | 環境                                                        | 役割/規模                              |
| :-------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------- | :------------------------------------- |
| 2014/12<br />〜<br />2016/3 | レシピサービスアプリ「レシピブック」の開発<br />初期リリースまでiOS領域での開発業務を全て担当<be /><br />開途中から開発に携わった。<br />サービスローンチに向けて新規機能開発、<br />iPad対応、不具合等の修正を担当。                                                                                                                                                                        | Mac<br />Xcode<br />Objective-C<br />Bitrise CI<br />Github | iOSエンジニア<br /><br />5名程度の規模 |
| 2014/10<br />〜<br />2015/3 | 年賀状アプリ「スマホで写真年賀状」の開発<br />初期リリースまでiOS領域での開発業務を全て担当。<br /><br />アプリの設計、開発、テストまで一貫して担当。<br />画像処理、他社注文システムへの繋ぎ、AWS(S3)を利用した<br />アプリのリソースのダウンロード処理の設計等を行った。<br />2015年3月に一度開発から外れたが、<br />同年11月、2016年度に向けたアプリの新規機能実装、改修も1ヶ月ほど担当。 | Mac<br />Xcode<br />Objective-C<br />Bitrise CI<br />Github | iOSエンジニア<br /><br />3名程度の規模 |

#### 概要
年賀状アプリ「スマホで写真年賀状」の開発を行った。(https://sfidante.co.jp/photoprint)
プロジェクトの開始時から、初期リリースと、運用保守を半年ほど担当。
iOSエンジニアの自分とデザイナー1人、プロジェクトマネージャー1人の3人で開発を進める。

年賀状アプリということで

- ユーザーが選択した画像を、こちらで用意した年賀状のテンプレートに当てはめる
- 当てはめた後、画像を任意の大きさにクロップしたり回転させることができる
- 当てはめた後に、写真の位置を入れ替えたり、新規で画像を選択して入れ替える
- ユーザーが入力した住所情報を文字として描画する
- アプリ上で表現した年賀状のUI(View)を、印刷に必要なサイズ、画質にリサイズして画像化する

といった機能を求められたので、主に画像処理に関してこの頃に知見を深めることが出来た。
年賀状の注文や印刷といった部分は、外部の印刷会社のAPIとの連携だったので、そのつなぎ込みを実装した。

年賀状は11月ごろから徐々に注文が増えてくるため、この時期にリリースをしておかないと収益が見込めなくなるというのもあり、プロジェクト始動した同年9月から2ヶ月ほどでリリースを行うことができた。

当初はアプリ内に年賀状のテンプレートデータを持つようにしていたが、アプリの容量の問題とアプリのアップデートなしにテンプレートを追加変更できるように、自社のAWS S3に上げたデータをダウンロードして保持できるような仕組みに変更する実装も行った。

2015年3月に一度開発から外れ、別のプロジェクトの担当になったが、
同年11月、2016年度に向けたアプリの新規機能実装、改修も1ヶ月ほど担当。  

また、その頃にAndroid版の提供も行いたいということで、業務委託で来ていてAndroidエンジニアに、サービスの設計を説明したり、成果物をデバッグして品質チェックを行ったりもした。

#### その他

受託案件を何件かiOSエンジニアとして開発を担当。Swiftを使った開発も有り。


## 業務外活動

| Date             | Event      | Details      |
| :--------------- | :--------- | :----------- |
| 2019/09/05-07 | iOSDC 2019 | 運営スタッフ |
| 2018/08/30-09/02 | iOSDC 2018 | 当日スタッフ |
| 2017/09/15-17    | iOSDC 2017 | 当日スタッフ |

## 海外出張歴

| Date    | Event                    |
| :------ | :----------------------- |
| 2018/06 | WWDC 2018                |
| 2017/10 | Firebase Dev Summit 2017 |


## 登壇歴(社外)

| Date       | Event                             | Slide                                                                                                              |
| :--------- | :-------------------------------- | :----------------------------------------------------------------------------------------------------------------- |
| 2019/02/02  | GCPUG Fukuoka 「Firebase特集」 | [A use case of Firebase in Komerco.](https://speakerdeck.com/sgrksmt/a-use-case-of-firebase-in-komerco) |
| 2018/10/9  | potato tips #55                   | [Improve Event log using Sourcery in iOS](https://speakerdeck.com/sgrksmt/improve-event-log-using-sourcery-in-ios) |
| 2018/08/7   | Firebase Meetup #5                | [はじめてのCloud Firestore](https://speakerdeck.com/sgrksmt/cloud-firestore-for-biginners)                         |
| 2018/07/19  | Cookpad Tech Kitchen #16          | [Effective Firestore Security](https://speakerdeck.com/sgrksmt/effective-firestore-security)                       |
| 2017/11/21 | Firebase Yebisu #1                | [Try new Firebase AB testing](https://speakerdeck.com/sgrksmt/try-new-firebase-ab-testing)                         |
| 2016-12-21 | Realm meetup 忘年会 + LT大会 2016 | [「それでもぼくはAuto Incrementしたい」](https://speakerdeck.com/sgrksmt/soredemobokuhaauto-incrementsitai)        |


## 執筆歴
- 「ど素人でも今スグできるiPhone無料アプリで稼ぐ方法」 (2013)
  - 藤永 真至氏と共著 (現在は絶版)
- 「Firebase入門 フリマアプリを作りながら、
認証・Firestore・Cloud Functionsの使い方を学ぼう」
  - https://employment.en-japan.com/engineerhub/entry/2019/06/07/103000
