# kadai1_janken_1022
JavaScriptを用いた初めてのじゃんけんアプリ

## ①課題内容（どんな作品か）
- 土曜G'sでしょう　じゃんけん国取り物語
  -水曜どうでしょうの名物企画、対決列島　甘い物し国取り物語をじゃんけんゲームにしました！

## ②工夫した点・こだわった点
- 下記のタイミングで音が鳴る様にしました。
  -(音楽1,2は妻がそれぞれ作ってくれました。感謝。)
  1 タイトルロゴ押下；音が鳴り終わってから画面が切り替わる様にしました。
  2 マップ画面；マップに入ると常に音が鳴ります。
  3 じゃんけん選択
  4 結果表示
- 本物っぽい見た目
  本物のフォントは1万円近くするので、似たフリーフォントを探して、本物に寄せました
- じゃんけん処理を一つのHTMLで作成しました。
  文字を順番に表示させるため、一つのHTML内に全ての文字を入れておいて
  JavaScriptの.hide()と.show()で表示/非表示を切り替えました。

## ③難しかった点・次回トライしたいこと(又は機能)
- 難しかったこと
  縦書き;基本縦書きを採用しましたが、やっと慣れてきたflex-boxと挙動が異なり、レイアウトに苦労しました。
  
- 次回トライしたいこと
  本当は指定した県を勝敗で色分けし、獲得した県の面積を足し合わせて最終的な勝敗を決定したかった。
  
## ④質問・疑問・感想、シェアしたいこと等なんでも
- [疑問]　HTMLからHTMLへの数値の持ち越しの仕方が分かりませんでした。
- [感想]　技量が足らず、最終目指した所の７割くらいになってしまったのが悔しい。スキルが付いたら完成させたい。
- [tips]
         -　audioタグで音が鳴らせます。
         -　縦書きCSSは`writing-mode : vertical-rl;`
         -　縦書き時の縦方向中央揃えは`align-items`ではなく、`vertical-align: middle;`です。
- [参考記事]　[縦書き]https://web-camp.io/magazine/archives/103632
