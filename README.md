# 『コールしよう！！』
## 「コールしよう！！」について
### 概要
楽曲のコールするタイミングに合わせて表示された歌詞を押すことでミクさんに対してコールすることができます。\
また、3Ⅾ空間を移動していろんな角度からライブを楽しむことができます。

### 開発時の思い
3D空間のライブでコールができるリリックアプリを作成しました！！\
世の中では一時的にリアルのライブでコールができない期間が続きました。\
マジカルミライのライブでもコールできず、寂しい思いをして、ライブにおけるコールの大事さを痛感しました。\
今回作成したリリックアプリはライブで「ライブでコールをしたい！」という気持ちを表すために作成しました！\
対象楽曲の中でも特にコールをしていて楽しい曲として「ミュウテイション」を選択させていただきました。\
3D空間のライブを自由に移動しながらミクさんにコールをしつつ楽曲を楽しんでください！！



### 遊び方
1. 楽曲ロード後にスタートボタンを押してください
1. 左下のスティックで左と右と奥行の移動、右下のスティックでカメラの向きを変更して、好きな位置でライブを観ることが可能です
1. 歌詞に合わせてコールする言葉が真ん中に表示されるので、好きなタイミングで押してコールしましょう
1. 曲を途中で止めたい場合はpauseボタンを押してください

### Webページ
- GitHub Pagesにて実際に試すことが可能です。
  -  https://hueno-ttic.github.io/MagicalMiraiContest2023/

### 動作説明動画
https://www.youtube.com/watch?v=fpm2oQxESgA

※ 提出したURLと違いますが、こちらのURLが最新になるので、こちらを参照していただけると幸いです。\
※ 動画撮影の都合上、動画と実際のアプリの動作に差異がある可能性があります。実際の動作を確認する場合は上記のGitHub Pagesにて動作確認をしていただけると幸いです。

### アプリの特徴
- TextAliveAppAPIから取得した楽曲データを使用
  - 歌詞情報を取得してライブ演出に合わせて表示
    - 画面下に全体の歌詞
    - ステージ奥にコール部分を除いた歌詞
    - 歌詞情報からコール部分を抜き取ってコールボタンを作成
      - 押す（もしくはタッチ）することでステージに対して可視化したコールを投げることが可能 
  - サビ情報を取得してライブの演出を変化させる
    - 中央のステージがせりあがる
    - 後ろにあるディスプレイのカメラが寄り気味に変化
  - segments情報を使って曲の構成要素を解析
    - 解析した情報をもとにミクさんの踊りの振付を変化させる
- デスクトップ・モバイルブラウザ向けに作られたHTML5/WebGLゲームエンジンのPlayCanvasを使用
- 採用楽曲である「ミュウテイション」に合わせてステージを構成した
- 左右の仮想スティックを使って視界操作ができる
  - 左スティックを使って中央のステージの後ろ側を含めてぐるっと1周移動することができる
  - 右スティックを使って視界を操作することができる

### 対応楽曲
- ミュウテイション

### 対応環境
- PC Chrome
- iPhone Safari
- iPad Safari
- Android Chrome

※ PCマウスでも操作は可能ですが、タブレット端末のタッチ操作のほうが楽に遊ぶことができます。
※ ある程度スペックの高い端末を使ったほうがスムーズに動作します。

### 注意事項
- スマートフォン・タブレットで遊ぶ場合は本体を横向きにしてください
- スマートフォンのブラウザでURLバーが出てしまう場合は、各スマホに応じてURLバーを非表示にしたほうが見やすくなります
- 動作が不安定になった際にはページの再読み込みをしてください

### モデル情報
3Dモデル「止丸式初音ミク」を使用
詳細は以下のURLのREADME情報を参照してください
https://booth.pm/ja/items/1528156

### ゲームエンジン
- PlayCanvas
  - https://playcanvas.jp/

### 開発者
- すぱりだ @super_reader