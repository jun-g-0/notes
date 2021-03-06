# TeamGeek 
本書は、職場のエンジニアが話題に挙げていた。  
そのチームは本書の良いチームを体現しており、すこぶる尊敬できた。  
自分もその精神を持ちたく、覚書を書いた。
なお、フォーマットの策定に当たっては、以下の記事を利用させて頂いた。  
[新人エンジニアにレポートを書かせて技術書の読み方を伝える。](https://ledsun.hatenablog.com/entry/2013/01/21/165013)  

## 概要（著作、著者、著者経歴）
[Brian W. Fitzpatrick](https://www.oreilly.com/pub/au/1802) / [Ben Collins-Sussman](https://www.oreilly.com/pub/au/1801):   
両名ともに、2005年までSubversionの開発を行っており、プロジェクトにおける協力の重要性に関する知見を得る。  
2005年にGoogleのシカゴオフィスに移り、各所における講演が本書へつながる。  
他の著作には、Subversionに関するもの等が存在する(リンク先参照)。

[角 征典](https://kdmsnr.com/):   
ご本人様のWebページより引用
> 主な訳書に『リーダブルコード』『Running Lean』『Team Geek』（オライリー・ジャパン）、『エクストリームプログラミング』『アジャイルレトロスペクティブズ』（オーム社）、『図解リーン・スタートアップ成長戦略』（日経BP社）、『Clean Coder』（KADOKAWA）など。

## 要約
チームの状態は個人の生産性や幸福に直接影響する。  
良いチームを作り、機能させるためには良い行動(本書に記載)が必要だが、その根底は、コントロールできる自分から、HRTの原則に基づいて行動することから始まる。
- Humility 謙虚:
    - 自分は全知全能ではない!(天才でもない。)
- Respect 尊敬:
    - 相手を1人の人間(大人)として扱い、評価しよう。
- Trust 信頼:
    - 相手は有能であり、正しいことをすると信じよう。


## 面白かった章とその理由
「2章 素晴しいチーム文化を作る」と「4章 有害な人に対処する」が有意義と感じた。  
生き残れる強い文化の作り方と、それを外的要因から守る具体的な方策が記載されている。  
どのような目的なプロジェクト・集団であれ、効率よく、幸福な結果を得ようとするならば、役に立つだろう。

## 理解できなかった章とその理由
全ての章で納得が行くことが記載されていたが、強いて言えば、チームを子供として扱うアンチパターン例での、設備を扱うための言伝がなかったケースについては違和感があった。  
細部が省略されているだけだと思うが、単に施設担当者が伝え忘れただけではないかな…  
また、マネージャーをリーダーに置き換えないことにも若干違和感があった。  
人間関係の問題やユーザビリティに関する知識については、他にも参照すべきだろう。

## 仕事に活かせそうな知識、活かせそうな状況と活かし方
この書籍では最後にどう行動すればよいか、まとめてくれているので、それを引用しよう。  
> 物事はシンプルに考えよう。他のことは忘れても、HRT(謙虚・尊敬・信頼)だけは覚えて欲しい。  
> …(中略)…HRTはあらゆる影響「範囲」に適用可能だ。

## その他
- さぼりがちな自分への戒めとしては、信頼しても自分の責任を放棄してはならないことを記載しておく。
  - 依頼した仕事は、コストをかけてチェックする。チームで動いているのだから。
  - 改めて欲しい事があれば、尊敬を込めて伝える。それは難しく、訓練が必要なことだ、時間をかけよう。
- 記載内容のテーマが散らばっている場合、要約するのが難しい。
- 覚書として書く場合、あまりフォーマットにこだわり過ぎないほうがよいかもしれない。以下に自分が後で参照したい情報をメモとして書いておく。
- 本書では、そもそも「優秀な」エンジニアを前提に話を進めている。つまり、いま優秀ではない自分は、そもそも実践する機会さえ、得られていないということだ。
  - とはいえ、全ての人は等しい時間の中にいるのだから、いつまでも蚊帳の外にいるわけでもない。精進せよ。

## キーワードメモ
- 1章 天才プログラマの神話
  - HRT
  - バス係数
  - 戦いを避けるために、エゴ(固執)をなくす
  - 君は君の書いたコードじゃない
  - ポストモーテム
  - 学習のための時間
  - 忍耐
- 2章 素晴しいチーム文化を作る
  - 文化は自己選択的
  - 文化を作れるのはチームメンバー
  - 優秀な人を集めるには、合意ベースのマネジメントが必要
  - コミュニケーションの原則は、非同期コミュニケーションを増やすこと
  - ミッションステートメント(目指すこと、目指さないこと)
  - アジェンダが終わったら終了するミーティング
  - 設計文書を適切に書く。一人がオーナーで、二人がレビュアー。
  - 検索可能な議論の場
  - 課題管理ツール
  - コメント・プロジェクトレベルのAuthorリスト・レビュー・自動テストとデプロイ
- 3章 船にはキャプテン(リーダー)が必要
  - リーダーは自然発生する
  - @Deprecatedマネージャー!@Deprecatedマネージャー!
  - リーダーはベビーシッターではない!チームメンバーはベビーではない!(ベビーを入れてはいけない??初心者であっても、ベビーになってはいけない)
  - リーダーの仕事はエンジニアの仕事と違う成果を生む
  - 無能なマネージャーは無能なプレイヤーではなかった。有能だったから、階層がそうさせたのだ。(階層的な組織や、昇進という仕組みが、概ねの場合、効率的ではないのでは)
  - サーバントリーダー
  - アンチパターン: 言いなりを採用・低パフォーマンスに対する無視・人間問題の無視・リーダーではなく友達になる・採用を妥協する・ベビーとして扱う
  - 成功パターン: エゴをなくす(再度!)・平静を保つ・人を繋ぐ・メンターになる・目標を明確にする(チームの範囲内で)・正直になる・チームで幸せを求める・「何か必要なものはある?」
  - 成功パターン(Tips): 半移譲する・自分自身を置き換える・必要なときに事を荒立てる・カオスからチームを守る・上層部の今を伝える・良い所もフィードバックする・やり直しが簡単に効くなら「いいよ」という
  - 人によって必要なサポートは違う。方向性/モチベーション
- 4章 有害な人(ではなく振る舞い!)に対応する
  - 「有害」の定義は、文化的に、ネガティブな「振る舞い」(善悪ではない)
  - 個人的に賛同する例: 他人の時間(唯一無二のリソース)を尊重しない・異なる意見に耳を傾けない・貢献無しに権限を求める・言語を上手く使おうとしない・プロダクトに対する完璧主義
  - いかに文化を守るのか: 完璧の対象を変える・餌を与えない・平静を保つ(再び)・真実を掬い出す・HRTを心に諦める
  - 悪意に見えるそれが、悪意であることは少ない
- 5章 組織的操作の技法
  - 目に見える仕事には一定の時間を割り当てよう
  - 高い能力を持っていれば、自分自身の将来をコントロールできる
- 6章 ユーザーも人間
  - 一般的な人にどう見られるか、管理する
  - 第一印象に拘る
  - 小さく約束・大きく届ける
  - 観客を選ぶ
  - 速いことは、いいことだ
  - 少ないことも、いいことだ
  - 複雑であることをひけらかす必要はない
  - プロダクトは、ユーザーを豊かにするためにある