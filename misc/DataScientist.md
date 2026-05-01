---
title: データサイエンティストの気づき!「勉強して仕事に役立てない人。大嫌い!!」『それ自分かも?』ってなった!!! 統計(36)
tags: Qiita10th_過去 データサイエンティスト 統計 CountdownCalendar2022 DoCAP
author: kaizen_nagoya
---
### The Qiita article cannot be updated due to system issues. Please refer to GitHub for the latest version.
通りすがりのデータサイエンティスト、技術士（情報工学）・工学博士です。2021年9月11日（執筆当時の今日)まで、「俺はデータサイエンティストの経験が長い」ことを自慢していました。二十代の頃、いろんな論文公募で通らずに、データ解析したら二席をいただいたことに始まるかもしれません。

@kazuo_reveさんのあるところでの、ある書き込みに、意見を書こうと思いました。筋書きを立てていたら次々気がついたことが３つありました。気づき１「現場経験」、気づき２「隠蔽、改竄」、気づき３「10年」。

# 目次
目次
・気づき1. 現場経験
・気づき2. 隠蔽・改竄
・気づき3. この１０年、社会に貢献できるようなプログラミングをしていなかった
10周年記念イベント「10年前の自分に伝えたい、勉強しておきたかった技術」
・1. 確率・統計
・2. プログラミング言語
・3. 機械学習
・4. docker
・5. git(Github, Gitlab and Bitbucket)
・6. data format(markdown. json)
あなた本当にデータサイエンティストですか？」
・1. データが集まらない
・2. 現場になったから分析できない
・3. 分析屋はプログラム書かなくていいんだ。
・・日鉄ソリューションズ参考資料
まとめに代えて「三方よし」
付録 1. データサイエンティスのプログラミング言語, R, Python, JavaScript, Ruby and Fortran
・R
・Python
・JavaSxript
・Ruby
・Fortran
付録 2. 心を入れ替え努力。まだここ止まり。
・なんでも統計相談室(1)分母の値が０になる場合
・なんでも統計相談室(2)評価関数の作り方(1）高速道路スマートインタ
・なんでも統計相談室(3) 時刻表の見方：単位と誤差。鉄道(11)
・お客様が困られないように資格を取るという視点
・Qiitaに企業登録して、勤務外で記事を書くときの指針案
・Reference on Reference on "What are the most important statistical ideas of the past 50 years? " Andrew Gelman, Aki Vehtari
付録 3. 現場の問題を解決しろ。データはそこにある。
・採用、教育・訓練事業
・労働管理、業務記録、事故・事件記録
・出荷・稼動開始、問い合わせ、応対
・為替、株価・地価・金利
付録４　一覧
・V/G 小さい順
・Views大きい順
・Goods大きい順
参考記事(reference)
・新人(new face)
・自己参照(self reference)
・謝辞(Special Thanks)
文書履歴(document history)

## 気づき 1. 現場経験
気づき１は、自分がデータ分析でなぜ簡単に賞が取れたか、約30年後に気がついたという話。

現場経験が４年あり、その後管理部門に行った。
現場経験のうち２年は外回り、２年は苦情処理的ななにか。
ありとあらゆるデータの個々の具体的な中身がわかっていた。
生データを見ていれば、何があるかがわかる。
その上で統計データを見れば、あたかも統計データから何が問題かの統計解析を記述するのは容易だったんだ。
https://bookmeter.com/books/4143479 
https://booklog.jp/item/1/B000J78BZA
https://www.amazon.co.jp/dp/product/4794102755/

「人生で影響を受けた本100冊」に28冊足す計画（14冊）
https://qiita.com/kaizen_nagoya/items/3ae6633725df77261df8

107 自主研究実践ハンドブック―地方自治体活性化のために (1984年)
https://bookmeter.com/books/2545234

>自治体でも改善していた記録。 現場での改善するきっかけになるかも。改善を阻害する要因が何かを考えることもできる。企業が自治体の仕事を取ることにより、現場での改善活動が消えていくこともあるかも。

今まで書いてよかった技術書を紹介しよう！
https://qiita.com/kaizen_nagoya/items/d31b7c158541d345a7ef

## 気づき 2. 隠蔽・改竄
統計の嘘　

逆も真かもしれない。２−３年、統計データを解析しつづけて、
２−３年、現場に出れば、なんだあのデータの変化は、こういう事象と関係あるかもとか。
こんな事象は、こういう対応すれば、統計には現れないように処理できるとか、
いろいろ手が思い浮かぶ。
やばいかもしれないのは、統計データを見ていて、現場の生データに出会う経験だと、隠蔽工作に手練れとして重宝されるかもしれない。統計データにどういう影響を与えなければ、問題にならないかを知っている。生データをどう操作すればいいかを知っている。現場には喜ばれるが、会社にも、社会にも有益にならないかもしれない。

現場から管理、管理から現場、どちらの順番でも、隠蔽、改竄の専門家になる可能性があるかもしれない。現場から管理部門に行って、現場に、こうすれば問題にならないという助言をしたらオワ。

技術って諸刃の剣。相手も自分も傷つけるかも。

統計の嘘。仮説（127）
https://qiita.com/kaizen_nagoya/items/63b48ecf258a3471c51b

人生で影響を受けた本100冊。
https://qiita.com/kaizen_nagoya/items/16af53acbb147a94172e

55. 初等統計解析 
佐和隆光
https://bookmeter.com/books/672554
https://booklog.jp/item/1/4788502240
https://www.amazon.co.jp/dp/4788502240/

>大学の統計学の教科書として、本書の初版を利用した記憶があります。
「たしか、統計は嘘をつくための道具だという話があったと思う。
すでに、手元にないので確かめようがありません。」
と書いてから、１月探したら出てきました。
「しばしば統計は、他人をだますための方便ともなる。
統計の悪用と誤用は、日常茶飯のごとくみうけられる。
数字の氾濫するこの世の中において、「統計のウソ」に対する抵抗力をそなえておくことは、将来どういう仕事にたずさわる人にとっても必要不可欠なはずである。」
ちょっと長いですが引用させていただきました。
１０年ほど前に、名古屋に講演に来ていただいたことがあります。
大学で佐和隆光先生の書籍を統計学の教科書として利用させていただいたことをお話しました。

仕様を自然言語で書くのやめませんか。「言葉にすれば」「嘘に染まる」水谷啓二・ダンシングオールナイト　もんたよしのり
https://qiita.com/kaizen_nagoya/items/dd6ee74818f1a1a1c918

プログラマにも読んでほしい「QC検定にも役立つ！QCべからず集」
https://qiita.com/kaizen_nagoya/items/d8ada7b7fceafe2e5f0e

半分ちかくのべからずが、逆も真。

## 気づき 3. この１０年、社会に貢献できるようなプログラミングをしていなかった
データサイエンティストとして勉強はしていたり、個別の問題解決のプログラミングはしていた。それぞれの領域全体または社会に貢献できるようなプログラミングをしていなかったことに、はたと気がついた。

IT系勉強会をすべて当たりにする方法。仮説（124）
https://qiita.com/kaizen_nagoya/items/9f001a79ab4162220406

そんなことを思う日々、あれ？最近、自分で何してたっけ。
いろいろ整理してはっと気がついた。

『勉強だけして仕事に役立てない人。大嫌い』
それ自分だったっていう。

１５年前、２５年前、３５年前は、それなりに100人か10,000人かは別として、他の人の役立つソフトはそれなりに書いていたはずなのに。

構造屋(architect)としての成功２失敗６
https://qiita.com/kaizen_nagoya/items/117c7a1b6dad97470ae9

開発環境を豊かにする開発事例　過去・現在・未来
https://qiita.com/kaizen_nagoya/items/d9bf0c2c671fe7f1c749

優秀賞 をいただきました。ありがとうございます。

Qiita エンジニアフェスタ 2021 プレゼント企画結果発表
https://blog.qiita.com/engineer-festa-presents-winners-2021/

40年(60年）でソフトウェア開発の景色はどのぐらい変わったのか？仮説（165）
https://qiita.com/kaizen_nagoya/items/54c17cf751894eef56f8

@kazuo_reve ほどかっこよくないけど。

「@kazuo_reve  自分のコーディングでユーザーに喜びの声いただいたこと」
https://qiita.com/kazuo_reve/items/b1a4ee2fc421422c6b9a

自組織のシステム管理者はしていませんでした。何もしていなかったわけではありません。
訪問先の臨時ネットワークを構築したり、ネットワーク故障を解決しtり、インフラ屋としては活動していました。

「何もしていないのに壊れた」インフラエンジニアの対応例
https://qiita.com/kaizen_nagoya/items/49c58fa6f4278717d061

「ITエンジニアとしてのPC初期環境構築 [macOS編] 」に付記したいこと
https://qiita.com/kaizen_nagoya/items/08c9f7e4b968472961fd

2020年3月までは、TOPPERSプロジェクトの理事として、コンテスト、開発者会議に参加してきました。

TOPPERSまとめ　名古屋のIoTは名古屋のOSで
https://qiita.com/kaizen_nagoya/items/9026c049cb0309b9d451

# Qiita 10周年記念イベント 
「10年前の自分に伝えたい、勉強しておきたかった技術」
https://qiita.com/official-events/1e99fc384200c38548fd

参加記事です。

-> 勉強ばかりしてるんじゃなくてみんなのためになるプログラム組めよって話。 

10年前の自分に伝えたい、「勉強しておきたかった技術」というよりは勉強してるだけじゃなくて、ちゃんとしたプログラム組んで、社会に貢献しなきゃ駄目だったという話。

勉強だけして仕事に役立てない人大嫌い。

IT系の勉強会にしょっちゅう出てきていて、なにかと喋ったり、なにかと発表したり、なにかとネットに書き込みをする。仕事の話をすると、勉強したこと、何も仕事に役立てていないことがある。仕事場で、勉強会の講師をしているらしいということで拝見させていただいたことがある。

「日本は駄目だ。こんなこともやってない、あんなこともやってない。」

日本が駄目なんじゃなくて、日本を駄目だと思う状態だとしたら、それはあなたの責任であって、日本の責任じゃないってわからないのだろうか。

どんな技術だって、誰か一人で突き抜けていることがある。
僕ら、凡人は、その穴を広げる手伝いはしているが、それを役立てていると言えるかどうかは、分からない。

日本のプログラマが世界で戦える16分野・事例。仮説（53）
https://qiita.com/kaizen_nagoya/items/a7e634a996cdd02bc53b

時間外は子育て。「 10年後のために今勉強しておきたい技術」は勤務時間内だけで。
https://qiita.com/kaizen_nagoya/items/0ad5c118a5be4d36b4d8

「駄目だ、もう何もできない」と思った時にするかもしれないこと
https://qiita.com/kaizen_nagoya/items/d672e461a75728dd5e74


1. 確率・統計
2. プログラミング言語
3. 機械学習
4.  docker
5.  git
6. data format(markdown, json)

凡人は天才、秀才と違うことをして生きていく
https://qiita.com/kaizen_nagoya/items/0502aebb7610fef584f5

凡人の生き残り戦略 〜 凡人網のつくりかた 〜
https://qiita.com/kaizen_nagoya/items/c8e2af61f344761c41be

## 1. 確率・統計
個々の計算はしてきた。経済学部経済学科と工学部電気工学科で二度「確率・統計」は単位をとっている。
工学部電気工学科編入の際に、卒業できないといけないので、いろいろな単位は認定してもらえて、その代わり、工業数学系の補習を受けることが条件だった。社会科学での確率・統計と、工学での確率・統計は違うということと、どちらも専門科目だったので認定してもらえなかった。
それじゃと、社会科学の確率・統計の使い方と、自然科学での確率・統計の使い方の違いを意地になって勉強してきた。

主な違いは、時定数と確率分布の形と受動測定か能動測定かの違いをあげることができる。
量子力学などでは、能動測定しかできない現象であれば、社会科学と似た構造があるなど、分野が決まれば、確率・統計の扱いが決まるわけではない。
経済学にはマクロ理論という統計を扱う理論と、ミクロ理論という個々の行動原理を扱う理論がある。ぶっちゃけ、統計物理・熱力学と、量子力学のような感じというと怒られるかもしれない。

確率・統計のソフトウェア開発はさぼっていた。ごめんなさい。

データサイエンティストへの５つの門。あなたはいくつの門をくぐりましたか？統計と確率(8)
https://qiita.com/kaizen_nagoya/items/ee5fa7b2a7f7c2b450d4

で紹介させていただいている、

「DNAと遺伝情報の物理」伏見譲。統計と確率(20)
https://qiita.com/kaizen_nagoya/items/150646f72c55a36f8c39

伏見譲さんのお父様の伏見康治さんが書かれた、「確率論及等経論」のTEXでの引用の許諾を得て、実施しています。その成果は、JAXA/IPA主催のソフトウェアシステムクリティカルソフトウェアワークショップで発表しています。

確率論及統計論輪講。仮説(95) 統計と確率(9)
https://qiita.com/kaizen_nagoya/items/89d0a91a56d33529e85c

少し前ですが、伏見譲さんの話題も出てくる、本の復刊が実現しています。

折り紙の幾何学, 伏見満枝, 伏見康治
https://qiita.com/kaizen_nagoya/items/a894d35774b112b84229

 56. 折り紙の幾何学
[伏見 康治](https://ja.wikipedia.org/wiki/伏見康治), 伏見 満枝
<img width="200" alt="ダウンロード (4).jpeg" src="https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/51423/d9ae9f72-8b39-250f-e18b-aa8a58c5c823.jpeg">

https://www.amazon.co.jp/4535781397/
https://bookmeter.com/books/442354
https://booklog.jp/item/1/4535781397

>子供のうちから与えたい幾何学の本
折り紙という子供向きの題材と幾何学という科学的題材が、共存しており、子供から大人まで、長く楽しめる書籍である。 著者も、家族で作ったというところも、内容の暖かさを感じさせることができる。
難しい幾何学を、ひょっとしたら、好きにさせることができるかもしれない。また、２次元の紙を、３次元の折り紙にすることにより、３次元認識と３次元幾何学を取り持つことができる要素が含まれている。 子供のうちからこの書を与えることにより、将来、科学者、技術者になったり、設計者（デザイナ）、芸術家になるための下地を作るかもしれない。
そんな雰囲気が漂う良書である。
ps. 伏見 満枝さんのご葬儀の際に，本書を知りました。絶版だったので復刊comに登録しました。数ヶ月で復刊が決まりました。

折り紙の幾何学, 伏見満枝, 伏見康治 
https://qiita.com/kaizen_nagoya/items/a894d35774b112b84229

人間の視覚をはじめとする感覚器官と反応も、統計と確率を用いて、多様性に対応するのがよいということを記録させていただきました。

プログラマが知っているとよい色使い(JIS安全色)
https://qiita.com/kaizen_nagoya/items/cb7eb3199b0b98904a35

IT業界でやめるとよいかもしれない３つの習慣（学歴（大学名）・理系文系・年齢）
https://qiita.com/kaizen_nagoya/items/f0d252d1e70ccea18efc#comment-da0f2fb4493caa2cb00e

「@spaces 平成のうちにやめたかった『ITの7つの無意味な習慣』」に付け加えたかったこと。仮説（169）
https://qiita.com/kaizen_nagoya/items/e6f9c2e0afbf8ab4181c

## 2. プログラミング言語
最初に覚えるプログラミング言語は何がいいですか？
https://qiita.com/kaizen_nagoya/items/590704e76e287707637b

プログラムは音楽だ (A program is a music.) 仮説（54）
https://qiita.com/kaizen_nagoya/items/33c9f33581e6886f8ad8

アセンブラへの道
https://qiita.com/kaizen_nagoya/items/46f2333c2647b0e692b2

VZエディタ移植に当たって実施したことと成果。仮説(115)
https://qiita.com/kaizen_nagoya/items/5551be98dcbed8f41949

言語規格、コーディング標準の使い方
https://qiita.com/kaizen_nagoya/items/01256365b82666e101aa

プログラマの英語（C言語編）最初の80単語（例）
https://qiita.com/kaizen_nagoya/items/701af188ef62a5b254cd

50歳からのプログラミング言語入門。docker(152)
https://qiita.com/kaizen_nagoya/items/5c7cec79cb3b15237076

50歳から毎年１言語習得を目標にしてきた。
実際に役立ったのは、verilog-HDL, Pythonくらいかも。
どっちもどちらかというとcode reviewで改善提案をする程度。

10年前から真剣に始めておけばよかったと思っているのはcoq

「coq入門」の入門
https://qiita.com/kaizen_nagoya/items/13566f0b2083ea8d4998

今井宜洋　@yoshihiro503　さんから教わった

2010年くらいかもしれない。

最初の頃は、１年くらい、システムがうまく動かなかった。OCAMLの導入は簡単だった。

「OCAML入門」入門
https://qiita.com/kaizen_nagoya/items/456bedf9f68b512663da

何を書けばいいか思いつかない日々が過ぎて行った。

ある日、４色問題を ssreflectで Microsoftが解いたことを知った。

４色問題が計算機で説かれた1975年、失意のうちに、人生の彷徨い人になった。なんで自分はもっと早く計算機に興味を持たなかったのだろうかと。

四色問題
https://qiita.com/kaizen_nagoya/items/bde57da01c210402939f

59. 四色問題 
新潮文庫, 2013/11, [Robin Wilson/ロビン ウィルソン](https://en.wikipedia.org/wiki/Robin_Wilson_(mathematician))
<img width="200" alt="51j2tVmZMEL._SX349_BO1,204,203,200_.jpg" src="https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/51423/d409d320-c89a-efda-efda-d6157c302ccc.jpeg">

https://www.amazon.co.jp/dp/4102184619/
https://bookmeter.com/books/7667829
https://booklog.jp/item/1/4102184619

>近代に説かれた数学の未解決問題の解決に関連する成果として、ヨシオ　シマモトという人が、シマモトの馬蹄形という問題を提起し、Ｄ可約性を課題とする環の大きさが１４の配置に関する課題があったということを知りました。
また、コンピュータを使って証明されたことが、検証の妥当性に疑問や懐疑を投げかけられたということを、この本で初めて知りました。
「コンピュータは疲れを知らない」反面、電磁的な不具合があった際に、検出可能であることが証明されていない場合があるかもしれません。
いずれにしても、四色問題という数学的にしか価値がないような問題を、一部の数学者による批評では美しい数学的手法ではない方法で解決されたということが、数学のおもしろさと、コンピュータのおもしろさを知るきっかけになるかもしれない。

40年後に、Microsoftの技術者が、coq でffreflectの拡張をして証明したことは著名。
https://github.com/math-comp/fourcolor/tree/master/theories

プログラミング言語教育のXYZ。Youtube(1) 仮説（52）
https://qiita.com/kaizen_nagoya/items/1950c5810fb5c0b07be4

６５歳からのプログラミング入門。docker(126)転職(16)
https://qiita.com/kaizen_nagoya/items/1561f910c275b22d7c9f

プログラマで「飛び抜けた人が少ない」仮説（38）
https://qiita.com/kaizen_nagoya/items/f0d22e20f6d2c58f2c1b

C/C++, 理解,溶解,爽快。仮説（173）
https://qiita.com/kaizen_nagoya/items/3f3992c9722c1cee2e3a

QiitaでもCOBOL
https://qiita.com/kaizen_nagoya/items/60596bad631956127cf8

COBOLを40年ぶりにうごかしてみた:dockerでcobol。docker(81)プログラムちょい替え（4）
https://qiita.com/kaizen_nagoya/items/9d9a216ce1b7b05dbb43

## 3. 機械学習
1986年、研究所に入所した時に、染色業界からの要請で講演したのが人工知能
2019年、研究所を退所する際に、塗装業界からの要請で講演したのが機械学習。

製造業における機械学習
https://qiita.com/kaizen_nagoya/items/fbe846de16f74bea1d6f

「直感Deep Learning」Antonio Gulli, Sujit Pal著 dockerで機械学習(3) with anaconda(3)
https://qiita.com/kaizen_nagoya/items/483ae708c71c88419c32

うち、色についてはずっと研究対象にしてきた。
中小企業大学校のデザイナ指導者養成研修も受講した。
中小企業大学校は、中小企業診断士の養成なども行う機関で、
中小企業診断士の方を含む、いろいろな方々を支援する組織で、
公的試験研究機関という都道府県の研究所・指導所などの職員が受講するものです。
都道府県の公的試験研究機関に、デザイン部があります。繊維試験場、窯業試験場などの分野特定の組織の場合もあり、工業デザインを指導しています。
残念ながら、名古屋市にはデザインセンターはありますが、職員の指導者は配置しておらず、名古屋市工業研究所の職員が別途対応している状態でした。

人工知能、機械学習は、同僚の手伝いをしただけ。ごめんなさい。

「ゼロから作るDeep Learning ２自然言語処理編」読書会に参加する前に読んで置くとよい資料とプログラム
https://qiita.com/kaizen_nagoya/items/537b1810265bbbc70e73

プログラマが知っているとよい色使い(JIS安全色)
https://qiita.com/kaizen_nagoya/items/cb7eb3199b0b98904a35

自己記事、いいね(lgtm)が最高。

手伝いをしていて、脱落しそうになった方の半数がWindowsにPythonを入れる方法がわからなかったという話。

人間が計算機に勝てる３つのこと。忘れる、あきらめる、やめる
https://qiita.com/kaizen_nagoya/items/49dc709d289d22846044

M.S.WindowsにPython3 (Anaconda3) を導入する（7つの罠）
https://qiita.com/kaizen_nagoya/items/7bfd7ecdc4e8edcbd679

自己記事viewsが最高。

なぜdockerでpython/Rを使って機械学習するか 書籍・ソース一覧作成中 (目標100) docker(18)
https://qiita.com/kaizen_nagoya/items/ddd12477544bf5ba85e2

## 4. docker

少しでも書き換えたものはdocker hubに記録する。

あなたもdocker, 私もdocker。docker(130)
https://qiita.com/kaizen_nagoya/items/8f2746f10f30b575d0a8

優秀賞 をいただきました。ありがとうございます。

Qiita エンジニアフェスタ 2021 プレゼント企画結果発表
https://blog.qiita.com/engineer-festa-presents-winners-2021/

## 5. Github, Gitlab and Bitbucket

dockerで構築している大事な資料はGithubにあげるようにしている。
案件によっては、Gitlab と Bitbucketも使っている。

公開算譜は機敏だ(An Open Source Project is Agile) GitHub with Docker。Youtube(2) 仮説（51）
https://qiita.com/kaizen_nagoya/items/5dd49a046b5991af3a5e

公開算譜は機敏だ：尻尾
https://www.youtube.com/watch?v=gGnfRVxXmSQ&t=10s

[![公開算譜は機敏だ：尻尾](http://img.youtube.com/vi/gGnfRVxXmSQ/0.jpg)](https://www.youtube.com/watch?v=gGnfRVxXmSQ)

Microsoftとの歴史　Cコンパイラを中心に
https://qiita.com/kaizen_nagoya/items/d7c0cc257e99de0573cf

Githubで開発環境構築から教育環境構築、教材作成へ
https://qiita.com/kaizen_nagoya/items/493bdd22c7d318402fe2

## 6. data format(markdown. json)
データサイエンティストとしては、ここが一番外せないとこ。
Oracle, DB2などのRDBが流行った頃は、メインフレーマという大型計算機製造業が、別々のDataBaseを売っていて、問い合わせ言語も標準的なものが見当たらなかった。

SQLの標準かと、Oracle, DB2などのRDBが流行が同期して、RDBじゃなきゃDBじゃないというような風潮もあった。

Wikipdediaへの書き込み、jsonの処理の取り組みが後手後手にまわっている。反省。

Python3: URLをコマンドライン引数で(wikipedia) docker(90)。プログラムちょい替え（2）
https://qiita.com/kaizen_nagoya/items/fc095b0c580a35001ea7

なぜ１０歳でプログラマを目指すとよいか「小学生だった僕がプログラミングを覚えるまでにやったこと」への賛歌。仮説（18）
https://qiita.com/kaizen_nagoya/items/75b0e6882b1e9c9e58db

５さいじがわかるcyber security（サイバセキュリティ）
https://qiita.com/kaizen_nagoya/items/105173527a8e54502bb7

10歳児がサイバセキュリティの専門家になるには
https://qiita.com/kaizen_nagoya/items/0aa201b09187bbe39ff3

データ形式の昨日、今日、明日。
https://qiita.com/kaizen_nagoya/items/15a77a879dcd34c458f3

# 「あなた本当にデータサイエンティストですか？」
 疑問がふつふつと沸き起こる。

## 1. データが集まらない
「データが集まらない」という人がいるらしい。

現代では、データは集めるものではなく、そこにあるもの。

Githubで開発していれば、毎日膨大なデータがそこにある。統計処理によって、手を差し伸べるといい箇所が、ほぼ自動で明確になる。

あなたが役にたつことをしていないから、あなたに膨大なデータを見せないだけ。

仕事で信用されていなくても、オープンソースで活躍することはできる。

ソフトウェアを投入したり、ソフトウェアを書いたり、試験したり、Reviewしたりする人には、データが目の前にいっぱいある。

プログラムを書いていない人には、そこにあるものがわからないんだろうか。

『勉強だけして仕事に役立てない人。大嫌い』

それ自分かもってなった。

社内が相手にしてくれないなら、Open Sourceで成果を出せば、社内からもいっぱい応援妖精が来るのに。

公開算譜は機敏だ(An Open Source Project is Agile)GitHub with Docker。Youtube(2) 仮説（51）
https://qiita.com/kaizen_nagoya/items/5dd49a046b5991af3a5e

Githubで開発環境構築から教育環境構築、教材作成へ
https://qiita.com/kaizen_nagoya/items/493bdd22c7d318402fe2

問題発見、問題解決、再発防止はGithubとDockerで。docker(143)
https://qiita.com/kaizen_nagoya/items/7855011710074c3b8e3d

設計はgit, dockerで。docker(13)
https://qiita.com/kaizen_nagoya/items/5e85a825709f7f5f56ee

## 2. 現場になったから分析できない
経営工学科などを卒業して、現場に就職した人の場合。ちょうど、「２−３年、統計データを解析しつづけて、２−３年、現場に出れば、なんだあのデータの変化は、こういう事象と関係あるかもとか。」に該当する。

開口一番「経営部門に配属にならなかったので分析ができません。」という元学生がいた。あなたは、大学で何を習ってきたのだろう。分析手法を学んだのなら、一番よい分析対象がある部署に配属になったのに、経営部門でないと分析ができないと思い込んでいる。

ちょうど、経営部門にいて、「データがない」と言っている人と状況は真逆だが、姿勢は同じ。問題を解決する気がない。

『勉強だけして仕事に役立てない人。大嫌い』

それ自分かもってなった。

## 3. 分析屋はプログラム書かなくていいんだ。
たしかに。
DataRobotという、機械学習を並列で計算させるソフトウェアを使えば、分析屋はプログラム書かなくてもいいかもしれない。

日本製鐵がDaraRobotを使って、圧延工程の制御をそれまでより効率的にしたときには、DataRobotでは標準で装備していないプログラムを追加して比較しているようにお聞きした気がする。

そこにライブラリがなければ、書けばいいだけ。書かなくていいという選択肢は、身の回りに書いてくれる人がいる人の手抜きか、人頼み根性か、他人のふんどしで相撲を取るのが好きか。

じゃ、自分、そういえば、最近何プログラム組んだか、思い出そうとした。

『勉強だけして仕事に役立てない人。大嫌い』

それ自分かもってなった。

## 日鉄ソリューションズ参考資料
@t_nakayama0714「Qiitaのいろいろランキング2019」への感謝と提案：Qiita(42)
https://qiita.com/kaizen_nagoya/items/40b8557a20e8d75d62b5

日本製鐵はすごい。Miningのご本家。データマイニングでも頭角を表わし、DataRobot社より上をいったんだね。

権威あるデータ分析の大会「KDD Cup」で堂々の世界第2位！
https://www.nssol.nipponsteel.com/future/stories/kdd-cup-2015.html

データ分析世界大会 “Kaggle”にて第2位、第5位に入賞
https://www.nssol.nipponsteel.com/press/2021/20210825_110000.html

日本のプログラマが世界で戦える16分野・事例。仮説（53）統計と確率(25)
https://qiita.com/kaizen_nagoya/items/a7e634a996cdd02bc53b

# まとめに代えて「三方よし」
この記事は、組み込みLinuxのNISTのPOSIX TEST SUITEを使った検証の共同研究をしている時に、「近江商人の三方よし」を教えてもらったことに始まる。組み込みLinuxのNISTのPOSIX Test Suiteによる試験結果とISO/IEC Squareによる分類の成果は、ドイツで2005年に開催された第三回世界ソフトウェア品質会議で発表している。

Testing and Verification for Embedded Linux
https://www.juse.or.jp/upload/files/3wcsq.pdf

Posix Test Suite docker downloads, tar, install。docker(110)
https://qiita.com/kaizen_nagoya/items/f1e24be04a2405ede00f

近江商人学入門―CSRの源流「三方よし」 (淡海文庫 (31))末永国紀 サンライズ出版  2004
![5133S8PJXDL._SX331_BO1,204,203,200_.jpg](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/51423/01ec8578-b522-6fb0-484c-e1b6691dba0c.jpeg)
https://www.amazon.co.jp/dp/4883251462
>買い手良し、世間良し、売り手良しの三方良しが商売を長く続ける秘訣だと思います。 
どれか一つだけでは、均衡を崩し、長期の商売にならないと思われます。 
うまく読み取れる人が、商売人になれると思います。

なぜ経済学徒を辞め、計算機屋になったか（経済学部入学前・入学後・卒業後対応） 転職(1)
https://qiita.com/kaizen_nagoya/items/06335a1d24c099733f64

Posix Test Suite 解凍方法(Windows power shell版）
https://qiita.com/kaizen_nagoya/items/57ee061892bc9afcf860

Open POSIX Test Suiteの使い方を調べはじめました
https://qiita.com/kaizen_nagoya/items/644d5e407f5faf96e6dc

データサイエンティストのための分析：Qiita自己記事まとめ2020：Qiita(98) 統計と確率(23)
https://qiita.com/kaizen_nagoya/items/ff51b03848908d38d7b3

データサイエンティストのための分析：Qiita自己記事まとめ2020 （演習）：Qiita(97)
https://qiita.com/kaizen_nagoya/items/31a7d9ad7dc514ad72cc

Testing and Verification for Embedded Linux
Akihiro Yamana, kiyoshi Kiriyama, Kiyoshi Ogawa
https://www.juse.or.jp/upload/files/3wcsq.pdf

，2005年9月27日からドイツ・ミュンヘンで開催されているソフトウエアの品質に関する国際会議「3rd World Congress for Software Quality 2005（3WCSQ）」
https://xtech.nikkei.com/dm/article/NEWS/20051003/109147/?i_cid=nbpnxt_reco_atype

2005年9月27日からドイツ・ミュンヘンで開催された世界ソフトウエア品質会議「3rd World Congress for Software Quality 2005（3WCSQ）」
https://xtech.nikkei.com/dm/article/NEWS/20051003/109161/

書き直せば書き直すほど、「役立つ」意味の隔たりに呆然とする日々。いろいろな立場の方を想定はしているが共感はしていない、自分に対する自分を含めて。

# 付録 1. データサイエンティスのプログラミング言語,  R, Python, JavaScript, Ruby, Fortran
そいで、この２週間、プログラム書いたのかっていう突っ込みをいただき、
まず、プログラム書く環境の確認から。
インストール段階から、いろいろ未整備だったことを思い出した。
ちょっと手を抜いているとこれだ。毎日プログラミングしてないと、いざプログラム組もうと思ったときに、駄目駄目。

## R
dockerでR 難関いくつ？ docker(125) dockerで機械学習(104) 環境構築(4)
https://qiita.com/kaizen_nagoya/items/5fb44773bc38574bcf1c

## Python
Pythonは、科学技術系のソフトウェアの自動化用のスクリプト言語として同梱していることがある。明示的にPythonって書いてなくても、Pythonのプログラム動かすと動くことがある。

play with docker

www.play-with-docker.com

説明はこちら。

６５歳からのプログラミング入門。docker(126)転職(16)
https://qiita.com/kaizen_nagoya/items/1561f910c275b22d7c9f

言語処理100本ノックをdockerで。python覚えるのに最適。docker(19) python(1)
https://qiita.com/kaizen_nagoya/items/7e7eb7c543e0c18438c4

## JavaScript

```macOS:bash
$ docker run -it node /bin/bash
```

docker 上で

```ubuntu:bash
# apt update; apt -y upgrade
```

## Ruby
技術書「Rubyソースコード完全解説」 と 「docker で ruby」構築。docker(148)
https://qiita.com/kaizen_nagoya/items/a00fec16fb43e6e9071d
## Fortran
Fortran 多次元配列のアクセス順序による計算時間の違い。docker(96)プログラムちょい替え(11)
https://qiita.com/kaizen_nagoya/items/3d657649d74fdd753bad

# 付録 2. 心を入れ替え努力。まだここ止まり。
確率・統計、Qiita、資格などで、三方良しを実現するための記事を少しづつ書き始めた。プログラムは一行も書いてない。月末までには３行は書きたい。

なんでも統計相談室(1)分母の値が０になる場合
https://qiita.com/kaizen_nagoya/items/80746d82c11a0ef810d1

なんでも統計相談室(2)評価関数の作り方(1）高速道路スマートインタ
https://qiita.com/kaizen_nagoya/items/830088de8b8f24a8d253

なんでも統計相談室(3) 時刻表の見方：単位と誤差。鉄道(11)
https://qiita.com/kaizen_nagoya/items/ce06604f3a0843440bbd

お客様が困られないように資格を取るという視点
https://qiita.com/kaizen_nagoya/items/b096e09cc06b475212f5

Qiitaに企業登録して、勤務外で記事を書くときの指針案
https://qiita.com/kaizen_nagoya/items/690ad7df7febb5369a3d

データ形式の昨日、今日、明日。
https://qiita.com/kaizen_nagoya/items/15a77a879dcd34c458f3 

Reference on Reference on "What are the most important statistical ideas of the past 50 years? " Andrew Gelman, Aki Vehtari
https://qiita.com/kaizen_nagoya/items/a8eac9afbf16d2188901

# 付録 3. 現場の問題を解決しろ。データはそこにある。
データを扱うには、データの単元がどのように振る舞うかを知っていることと、
総体の合計がどのような振る舞いを行うかは、必ずしも整合性があるとは限らない。

どちらかが原因で、どちらかが結果であると言えるかもしれないし、言えないかもしれない。

一方の立場で、いろいろ評論することは、個人の自由で、欲求不満の解消には役立つかもしれない。

両方の接続面の境界条件を確認するのは、日々変化して境界条件を確認する行為に価値はないかもしれない。

日々、どちらの立場から見えるものの違いを確認し、どちらにどう働きかけるかを選択するのは結構しんどい。

成功体験は語っても、成功体験に頼らないために。清水吉男・田中伸明・柏原一雄・佐々木 眞一。仮説（153）
https://qiita.com/kaizen_nagoya/items/d32adfaf7b2568bfd9d2

現場の問題を解決すれば、それが一件の与件(data)。

分業なり、兼業なりをしていれば、一つの問題には、数多くの関連事業が関わっていて、
小さな案件でも１０から２０の事業のデータの一面が見えるかもしれない。

あるソフトウェア開発事業の関連事業を具体的に見てみよう。

## 採用事業(recruiting)、教育・訓練(education and training)
そこで働いている人は、なんらかの形で採用されたか、自ら事業を興したか。
事業主に誘われて、なんの手続きもせず、翌日から働いていたとしても、れっきとした採用だろう。
健康保険、雇用保険などの適用があれば、なんらかのデータはある。

転職の面談で答えたこと。転職(19)
https://qiita.com/kaizen_nagoya/items/437aacaf8f386b88274d

転職の場合は、初出社の、その日から実務に入り、教育・訓練の時間がないかもしれない。

そうはいっても、なんらかの規定をもらったり、仕事の仕方はネットのここらへんにあるよって言われたら、それは教育・訓練のデータはある。

新人(学生)を指導するよりも新人(学生)に指導してもらった方が効率的。仮説（139）
https://qiita.com/kaizen_nagoya/items/db993b1536055029f7c8

情報処理技術者試験　ネットワークスペシャリストに合格
https://qiita.com/kaizen_nagoya/items/407857392ca5c5677ee4

10代、20代にお勧めの資格
https://qiita.com/kaizen_nagoya/items/4e0eb6e5d30c0237469d

## 労働管理（workforce management） 業務記録(work record) 事故・事件(accident and happening)

出勤、退勤の管理か、日報などによる実績の記録か、あるいはPCにloginからlogoutまでの記録か。

ずっとloginしっぱなしのシステムだったら、そのIDで、入力とか、出力とか、通信とかの記録を日報として認識することは可能だろう。

いずれにしても、労働管理のデータはある。

「会議は30分未満」小耳にはさんだ話。臨機応変。
https://qiita.com/kaizen_nagoya/items/55ab43e7f50434156ff4

労働管理とほぼ同義だと思うかもしないが、人間がloginしてなくても、作ったプログラムが動いて、仕事をしていれば、それが業務記録であり、データは山のようにある。

プログラマの「日報、週報、月報、年報」考。仮説(73)
https://qiita.com/kaizen_nagoya/items/97ad8ac9217c12c3bb69

「雑用」という名の用はない
https://qiita.com/kaizen_nagoya/items/4fda5ba89d35d24a3a78

質問の仕方の前に検索。「@shojimotio その発想はなかった！新しい質問のしかたとチーム環境作り」仮説（182）
https://qiita.com/kaizen_nagoya/items/d36e87972e6cd5f665f9

 事故・事件(accident and happening)は、会社によって呼び方が違うかもしれない。
通常動作と、それ以外に区分したときのそれ以外。

件数をかぞえるだけで、量、密度によって対応しない場合もあるかもしれない。

特に、危険が近い可能性のある警告のたぐいは、どういう頻度になったら、
他のプログラムが稼動し対応するとか、人が介入するとか決まっているかもしれない。

いずれにしても、警告、対応、介入があればデータである。

## 出荷・稼動開始(shipping and start running)問い合わせ、応対(inquiry)
ある計画(program)を作っていて、出荷したり、稼動開始になれば、それは大切なデータだ。

契約、請求などの関連する活動の一つの区切りとなるデータが生まれるかもしれない。

顧客からの問い合わせ、応答、その後の推移は、大切なデータだ。

自分の頭で考えるようになるには
https://qiita.com/kaizen_nagoya/items/121a5372e3d67fc3af35

## 外国為替（foreign exchange）株価・地価・金利(stock price, land price and interest rate)

円以外の取引もしていれば、為替の変動はとても大事なデータだ。
売り上げ、仕入れが変動し、原価が変わる時に、どう仕事の仕方を変えるかなど、対応をしたかどうかの記録もデータだ。

株式会社などの所有権の取引をしている場合の株価。
大規模な土地を所有している場合の地価。
現金預金や、借入金、貸付金などがある場合の金利。
これらもすばらしいデータだ。

# 付録４　一覧　
この記事で参照した自己記事の一覧を作成中です。

## v/g(views/goods)の小さい順
viewsをいいねで割った値(v/g)が２桁の記事は良記事という経験則。
200くらいまでの記事でお読みになられていないものがあれば、ぜひ、お手にとってください。プログラム組んでなかったり、エラーがなかったり、設定を示していないのは読み飛ばしていただいて結構です。
この記事のg/vが200を超えてしまっています。もし、お差し支えなければ、いいねを押してくださるようにお願い申し上げます。　

|No. |Title URL|Views|Goods|Stocks|G/V|
|:----|:----|:----|:----|:----|:----|
|1|６５歳からのプログラミング入門。docker(126)転職(16)  https://qiita.com/kaizen_nagoya/items/1561f910c275b22d7c9f|44962|743|564|60.51|
|2|プログラマが知っているとよい色使い(JIS安全色) https://qiita.com/kaizen_nagoya/items/cb7eb3199b0b98904a35|99651|1642|1641|60.68|
|3|40年(60年）でソフトウェア開発の景色はどのぐらい変わったのか？仮説（165） https://qiita.com/kaizen_nagoya/items/54c17cf751894eef56f8|15810|248|182|63.75|
|4|プログラマで「飛び抜けた人が少ない」仮説（38）　https://qiita.com/kaizen_nagoya/items/f0d22e20f6d2c58f2c1b|21434|260|224|82.43|
|5|プログラムは音楽だ (A program is a music.) 仮説（54）https://qiita.com/kaizen_nagoya/items/33c9f33581e6886f8ad8|36441|361|357|100.94|
|6|プログラマにも読んでほしい「QC検定にも役立つ！QCべからず集」 https://qiita.com/kaizen_nagoya/items/d8ada7b7fceafe2e5f0e|17941|172|183|104.3|
|7|アセンブラへの道 https://qiita.com/kaizen_nagoya/items/46f2333c2647b0e692b2|36061|339|365|106.37|
|8|時間外は子育て。「 10年後のために今勉強しておきたい技術」は勤務時間内だけで。　https://qiita.com/kaizen_nagoya/items/0ad5c118a5be4d36b4d8|10429|86|68|121.26|
|9|10代、20代にお勧めの資格　https://qiita.com/kaizen_nagoya/items/4e0eb6e5d30c0237469d|2892|20|16|144.6|
|10|人間が計算機に勝てる３つのこと。忘れる、あきらめる、やめる　https://qiita.com/kaizen_nagoya/items/49dc709d289d22846044|7425|51|25|145.58|
|11|IT系勉強会をすべて当たりにする方法。仮説（124） https://qiita.com/kaizen_nagoya/items/9f001a79ab4162220406|5212|35|22|148.91|
|12|「@spaces 平成のうちにやめたかった『ITの7つの無意味な習慣』」に付け加えたかったこと。仮説（169）https://qiita.com/kaizen_nagoya/items/e6f9c2e0afbf8ab4181c|43187|271|222|159.36|
|13|製造業における機械学習　https://qiita.com/kaizen_nagoya/items/fbe846de16f74bea1d6f|34919|210|248|166.28|
|14|Githubで開発環境構築から教育環境構築、教材作成へhttps://qiita.com/kaizen_nagoya/items/493bdd22c7d318402fe2|1184|7|4|169.14|
|15|C/C++, 理解,溶解,爽快。仮説（173） https://qiita.com/kaizen_nagoya/items/3f3992c9722c1cee2e3a|11424|63|65|181.33|
|16|凡人の生き残り戦略 〜 凡人網のつくりかた 〜 https://qiita.com/kaizen_nagoya/items/c8e2af61f344761c41be|3808|21|13|181.33|
|17|「ゼロから作るDeep Learning ２自然言語処理編」読書会に参加する前に読んで置くとよい資料とプログラム https://qiita.com/kaizen_nagoya/items/537b1810265bbbc70e73|32931|175|189|188.17|
|18|人生で影響を受けた本100冊。https://qiita.com/kaizen_nagoya/items/16af53acbb147a94172e|31720|168|175|188.8|
|19|「ITエンジニアとしてのPC初期環境構築 [macOS編] 」に付記したいこと　https://qiita.com/kaizen_nagoya/items/08c9f7e4b968472961fd|3063|16|16|191.43|
|20|データサイエンティストの気づき!「勉強だけして仕事に役立てない人。大嫌い!!」『それ自分かも!!! 』ってなった!!!! https://qiita.com/kaizen_nagoya/items/d85830d58d8dd7f71d07|18198|90|108|202.2|
|21|50歳からのプログラミング言語入門。docker(152)https://qiita.com/kaizen_nagoya/items/5c7cec79cb3b15237076|2676|13|6|205.84|
|22|データサイエンティストへの５つの門。あなたはいくつの門をくぐりましたか？統計と確率(8) https://qiita.com/kaizen_nagoya/items/ee5fa7b2a7f7c2b450d4|2717|13|14|209|
|23|「会議は30分未満」小耳にはさんだ話。臨機応変。　https://qiita.com/kaizen_nagoya/items/55ab43e7f50434156ff4|16055|76|44|211.25|
|24|プログラマの英語（C言語編）最初の80単語（例） https://qiita.com/kaizen_nagoya/items/701af188ef62a5b254cd|10832|45|37|240.71|
|25|言語規格、コーディング標準の使い方 https://qiita.com/kaizen_nagoya/items/01256365b82666e101aa|4906|20|17|245.3|
|26|あなたもdocker, 私もdocker。docker(130) https://qiita.com/kaizen_nagoya/items/8f2746f10f30b575d0a8|14972|60|73|249.53|
|27|折り紙の幾何学, 伏見満枝, 伏見康治　https://qiita.com/kaizen_nagoya/items/a894d35774b112b84229|775|3|0|258.33|
|28|統計の嘘。仮説（127） https://qiita.com/kaizen_nagoya/items/63b48ecf258a3471c51b|1043|4|2|260.75|
|29|質問の仕方の前に検索。「@shojimotio その発想はなかった！新しい質問のしかたとチーム環境作り」仮説（182）　https://qiita.com/kaizen_nagoya/items/d36e87972e6cd5f665f9|5787|22|17|263.04|
|30|「駄目だ、もう何もできない」と思った時にするかもしれないこと　https://qiita.com/kaizen_nagoya/items/d672e461a75728dd5e74|14218|54|30|263.29|
|31|表示画像の大きさ調整(Display Image Size Arrange)。Qiita(28)。　https://qiita.com/kaizen_nagoya/items/cef6ae1fcbdbec9e7be2|18903|71|34|266.23|
|32|QiitaでもCOBOL https://qiita.com/kaizen_nagoya/items/60596bad631956127cf8|5714|21|14|272.09|
|33|「coq入門」の入門 https://qiita.com/kaizen_nagoya/items/13566f0b2083ea8d4998|9976|36|30|277.11|
|34|なぜdockerでpython/Rを使って機械学習するか 書籍・ソース一覧作成中 (目標100) docker(18) https://qiita.com/kaizen_nagoya/items/ddd12477544bf5ba85e2|13587|48|61|283.06|
|35|なぜ経済学徒を辞め、計算機屋になったか（経済学部入学前・入学後・卒業後対応） 転職(1)https://qiita.com/kaizen_nagoya/items/06335a1d24c099733f64|5137|18|10|285.38|
|36|情報処理技術者試験　ネットワークスペシャリストに合格 https://qiita.com/kaizen_nagoya/items/407857392ca5c5677ee4|8448|29|22|291.31|
|37|10歳児がサイバセキュリティの専門家になるには https://qiita.com/kaizen_nagoya/items/0aa201b09187bbe39ff3|6189|21|23|294.71|
|38|５さいじがわかるcyber security（サイバセキュリティ） https://qiita.com/kaizen_nagoya/items/105173527a8e54502bb7|6713|22|10|305.13|
|39|「DNAと遺伝情報の物理」伏見譲。統計と確率(20) https://qiita.com/kaizen_nagoya/items/150646f72c55a36f8c39|7043|23|20|306.21|
|40|Microsoftとの歴史　Cコンパイラを中心に https://qiita.com/kaizen_nagoya/items/d7c0cc257e99de0573cf|6375|20|12|318.75|
|41|仕様を自然言語で書くのやめませんか。「言葉にすれば」「嘘に染まる」水谷啓二・ダンシングオールナイト　もんたよしのり　https://qiita.com/kaizen_nagoya/items/dd6ee74818f1a1a1c918|6098|18|16|338.77|
|42|今まで書いてよかった技術書を紹介しよう！　https://qiita.com/kaizen_nagoya/items/d31b7c158541d345a7ef|4210|12|5|350.83|
|43|「OCAML入門」入門　https://qiita.com/kaizen_nagoya/items/456bedf9f68b512663da|5437|15|19|362.46|
|44|日本のプログラマが世界で戦える16分野・事例。仮説（53）https://qiita.com/kaizen_nagoya/items/a7e634a996cdd02bc53b|4876|13|16|375.07|
|45|VZエディタ移植に当たって実施したことと成果。仮説(115) https://qiita.com/kaizen_nagoya/items/5551be98dcbed8f41949|12168|31|18|392.51|
|46|TOPPERSまとめ　名古屋のIoTは名古屋のOSで　https://qiita.com/kaizen_nagoya/items/9026c049cb0309b9d451|7862|20|21|393.1|
|47|なぜ１０歳でプログラマを目指すとよいか「小学生だった僕がプログラミングを覚えるまでにやったこと」への賛歌。仮説（18）https://qiita.com/kaizen_nagoya/items/75b0e6882b1e9c9e58db|1736|4|1|434|
|48|最初に覚えるプログラミング言語は何がいいですか？ https://qiita.com/kaizen_nagoya/items/590704e76e287707637b|29535|66|58|447.5|
|49|構造屋(architect)としての成功２失敗６  https://qiita.com/kaizen_nagoya/items/117c7a1b6dad97470ae9|902|2|3|451|
|50|自分の頭で考えるようになるには　https://qiita.com/kaizen_nagoya/items/121a5372e3d67fc3af35|11952|26|30|459.69|
|51|「雑用」という名の用はない　https://qiita.com/kaizen_nagoya/items/4fda5ba89d35d24a3a78|8086|17|5|475.64|
|52|開発環境を豊かにする開発事例　過去・現在・未来 https://qiita.com/kaizen_nagoya/items/d9bf0c2c671fe7f1c749|6736|14|12|481.14|
|53|四色問題 https://qiita.com/kaizen_nagoya/items/bde57da01c210402939f|998|2|0|499|
|54|確率論及統計論輪講。仮説(95) 統計と確率(9) https://qiita.com/kaizen_nagoya/items/89d0a91a56d33529e85c|2041|4|1|510.25|
|55|公開算譜は機敏だ(An Open Source Project is Agile) GitHub with Docker。Youtube(2) 仮説（51） https://qiita.com/kaizen_nagoya/items/5dd49a046b5991af3a5e|3731|7|2|533|
|56|凡人は天才、秀才と違うことをして生きていくhttps://qiita.com/kaizen_nagoya/items/0502aebb7610fef584f5|7129|13|13|548.38|
|57|「何もしていないのに壊れた」インフラエンジニアの対応例　https://qiita.com/kaizen_nagoya/items/49c58fa6f4278717d061|12572|21|18|598.66|
|58|設計はgit, dockerで。docker(13)https://qiita.com/kaizen_nagoya/items/5e85a825709f7f5f56ee|1855|3|2|618.33|
|59|IT業界でやめるとよいかもしれない３つの習慣（学歴（大学名）・理系文系・年齢） https://qiita.com/kaizen_nagoya/items/f0d252d1e70ccea18efc#comment-da0f2fb4493caa2cb00e|6198|10|8|619.8|
|60|効率的なHAZOPの進め方。仮説（187） https://qiita.com/kaizen_nagoya/items/2b8eae196945b7976446|15339|24|26|639.12|
|61|「人生で影響を受けた本100冊」に28冊足す計画（14冊） https://qiita.com/kaizen_nagoya/items/3ae6633725df77261df8|801|1|1|801|
|62|プログラミング言語教育のXYZ。Youtube(1) 仮説（52）　　https://qiita.com/kaizen_nagoya/items/1950c5810fb5c0b07be4|6222|7|14|888.85|
|63|Python3: URLをコマンドライン引数で(wikipedia) docker(90)。プログラムちょい替え（2）https://qiita.com/kaizen_nagoya/items/fc095b0c580a35001ea7|2834|3|1|944.66|
|64|「直感Deep Learning」Antonio Gulli, Sujit Pal著 dockerで機械学習(3) with anaconda(3) https://qiita.com/kaizen_nagoya/items/483ae708c71c88419c32|36088|32|55|1127.75|
|65|問題発見、問題解決、再発防止はGithubとDockerで。docker(143) https://qiita.com/kaizen_nagoya/items/7855011710074c3b8e3d|1160|1|0|1160|
|66|M.S.WindowsにPython3 (Anaconda3) を導入する（7つの罠）　https://qiita.com/kaizen_nagoya/items/7bfd7ecdc4e8edcbd679|169784|130|170|1306.03|
|67|Posix Test Suite docker downloads, tar, install。docker(110) https://qiita.com/kaizen_nagoya/items/f1e24be04a2405ede00f|1035|0|0|#DIV/0!|
|68|データ形式の昨日、今日、明日。https://qiita.com/kaizen_nagoya/items/15a77a879dcd34c458f3|569|0|0|#DIV/0!|
| |合計|1008712|6093|5678|165.55|

合計１００万viewsになる。ありがとうございます。

## Views順　

１０万以上が人気記事。３万以上が良（量）記事。１万以上は、すでにお手にとっていただいているかも。５０００以上の記事を、ぜひ、ご覧いただけると幸いです。
|No. |Title URL|Views|Goods|Stocks|G/V|
|:----|:----|:----|:----|:----|:----|
|1|M.S.WindowsにPython3 (Anaconda3) を導入する（7つの罠）　https://qiita.com/kaizen_nagoya/items/7bfd7ecdc4e8edcbd679|169784|130|170|1306.03|
|2|プログラマが知っているとよい色使い(JIS安全色) https://qiita.com/kaizen_nagoya/items/cb7eb3199b0b98904a35|99651|1642|1641|60.68|
|3|６５歳からのプログラミング入門。docker(126)転職(16)  https://qiita.com/kaizen_nagoya/items/1561f910c275b22d7c9f|44962|743|564|60.51|
|4|「@spaces 平成のうちにやめたかった『ITの7つの無意味な習慣』」に付け加えたかったこと。仮説（169）https://qiita.com/kaizen_nagoya/items/e6f9c2e0afbf8ab4181c|43187|271|222|159.36|
|5|プログラムは音楽だ (A program is a music.) 仮説（54）https://qiita.com/kaizen_nagoya/items/33c9f33581e6886f8ad8|36441|361|357|100.94|
|6|「直感Deep Learning」Antonio Gulli, Sujit Pal著 dockerで機械学習(3) with anaconda(3) https://qiita.com/kaizen_nagoya/items/483ae708c71c88419c32|36088|32|55|1127.75|
|7|アセンブラへの道 https://qiita.com/kaizen_nagoya/items/46f2333c2647b0e692b2|36061|339|365|106.37|
|8|製造業における機械学習　https://qiita.com/kaizen_nagoya/items/fbe846de16f74bea1d6f|34919|210|248|166.28|
|9|「ゼロから作るDeep Learning ２自然言語処理編」読書会に参加する前に読んで置くとよい資料とプログラム https://qiita.com/kaizen_nagoya/items/537b1810265bbbc70e73|32931|175|189|188.17|
|10|人生で影響を受けた本100冊。https://qiita.com/kaizen_nagoya/items/16af53acbb147a94172e|31720|168|175|188.8|
|11|最初に覚えるプログラミング言語は何がいいですか？ https://qiita.com/kaizen_nagoya/items/590704e76e287707637b|29535|66|58|447.5|
|12|プログラマで「飛び抜けた人が少ない」仮説（38）　https://qiita.com/kaizen_nagoya/items/f0d22e20f6d2c58f2c1b|21434|260|224|82.43|
|13|表示画像の大きさ調整(Display Image Size Arrange)。Qiita(28)。　https://qiita.com/kaizen_nagoya/items/cef6ae1fcbdbec9e7be2|18903|71|34|266.23|
|14|データサイエンティストの気づき!「勉強だけして仕事に役立てない人。大嫌い!!」『それ自分かも!!! 』ってなった!!!! https://qiita.com/kaizen_nagoya/items/d85830d58d8dd7f71d07|18198|90|108|202.2|
|15|プログラマにも読んでほしい「QC検定にも役立つ！QCべからず集」 https://qiita.com/kaizen_nagoya/items/d8ada7b7fceafe2e5f0e|17941|172|183|104.3|
|16|「会議は30分未満」小耳にはさんだ話。臨機応変。　https://qiita.com/kaizen_nagoya/items/55ab43e7f50434156ff4|16055|76|44|211.25|
|17|40年(60年）でソフトウェア開発の景色はどのぐらい変わったのか？仮説（165） https://qiita.com/kaizen_nagoya/items/54c17cf751894eef56f8|15810|248|182|63.75|
|18|効率的なHAZOPの進め方。仮説（187） https://qiita.com/kaizen_nagoya/items/2b8eae196945b7976446|15339|24|26|639.12|
|19|あなたもdocker, 私もdocker。docker(130) https://qiita.com/kaizen_nagoya/items/8f2746f10f30b575d0a8|14972|60|73|249.53|
|20|「駄目だ、もう何もできない」と思った時にするかもしれないこと　https://qiita.com/kaizen_nagoya/items/d672e461a75728dd5e74|14218|54|30|263.29|
|21|なぜdockerでpython/Rを使って機械学習するか 書籍・ソース一覧作成中 (目標100) docker(18) https://qiita.com/kaizen_nagoya/items/ddd12477544bf5ba85e2|13587|48|61|283.06|
|22|「何もしていないのに壊れた」インフラエンジニアの対応例　https://qiita.com/kaizen_nagoya/items/49c58fa6f4278717d061|12572|21|18|598.66|
|23|VZエディタ移植に当たって実施したことと成果。仮説(115) https://qiita.com/kaizen_nagoya/items/5551be98dcbed8f41949|12168|31|18|392.51|
|24|自分の頭で考えるようになるには　https://qiita.com/kaizen_nagoya/items/121a5372e3d67fc3af35|11952|26|30|459.69|
|25|C/C++, 理解,溶解,爽快。仮説（173） https://qiita.com/kaizen_nagoya/items/3f3992c9722c1cee2e3a|11424|63|65|181.33|
|26|プログラマの英語（C言語編）最初の80単語（例） https://qiita.com/kaizen_nagoya/items/701af188ef62a5b254cd|10832|45|37|240.71|
|27|時間外は子育て。「 10年後のために今勉強しておきたい技術」は勤務時間内だけで。　https://qiita.com/kaizen_nagoya/items/0ad5c118a5be4d36b4d8|10429|86|68|121.26|
|28|「coq入門」の入門 https://qiita.com/kaizen_nagoya/items/13566f0b2083ea8d4998|9976|36|30|277.11|
|29|情報処理技術者試験　ネットワークスペシャリストに合格 https://qiita.com/kaizen_nagoya/items/407857392ca5c5677ee4|8448|29|22|291.31|
|30|「雑用」という名の用はない　https://qiita.com/kaizen_nagoya/items/4fda5ba89d35d24a3a78|8086|17|5|475.64|
|31|TOPPERSまとめ　名古屋のIoTは名古屋のOSで　https://qiita.com/kaizen_nagoya/items/9026c049cb0309b9d451|7862|20|21|393.1|
|32|人間が計算機に勝てる３つのこと。忘れる、あきらめる、やめる　https://qiita.com/kaizen_nagoya/items/49dc709d289d22846044|7425|51|25|145.58|
|33|凡人は天才、秀才と違うことをして生きていくhttps://qiita.com/kaizen_nagoya/items/0502aebb7610fef584f5|7129|13|13|548.38|
|34|「DNAと遺伝情報の物理」伏見譲。統計と確率(20) https://qiita.com/kaizen_nagoya/items/150646f72c55a36f8c39|7043|23|20|306.21|
|35|開発環境を豊かにする開発事例　過去・現在・未来 https://qiita.com/kaizen_nagoya/items/d9bf0c2c671fe7f1c749|6736|14|12|481.14|
|36|５さいじがわかるcyber security（サイバセキュリティ） https://qiita.com/kaizen_nagoya/items/105173527a8e54502bb7|6713|22|10|305.13|
|37|Microsoftとの歴史　Cコンパイラを中心に https://qiita.com/kaizen_nagoya/items/d7c0cc257e99de0573cf|6375|20|12|318.75|
|38|プログラミング言語教育のXYZ。Youtube(1) 仮説（52）　　https://qiita.com/kaizen_nagoya/items/1950c5810fb5c0b07be4|6222|7|14|888.85|
|39|IT業界でやめるとよいかもしれない３つの習慣（学歴（大学名）・理系文系・年齢） https://qiita.com/kaizen_nagoya/items/f0d252d1e70ccea18efc#comment-da0f2fb4493caa2cb00e|6198|10|8|619.8|
|40|10歳児がサイバセキュリティの専門家になるには https://qiita.com/kaizen_nagoya/items/0aa201b09187bbe39ff3|6189|21|23|294.71|
|41|仕様を自然言語で書くのやめませんか。「言葉にすれば」「嘘に染まる」水谷啓二・ダンシングオールナイト　もんたよしのり　https://qiita.com/kaizen_nagoya/items/dd6ee74818f1a1a1c918|6098|18|16|338.77|
|42|質問の仕方の前に検索。「@shojimotio その発想はなかった！新しい質問のしかたとチーム環境作り」仮説（182）　https://qiita.com/kaizen_nagoya/items/d36e87972e6cd5f665f9|5787|22|17|263.04|
|43|QiitaでもCOBOL https://qiita.com/kaizen_nagoya/items/60596bad631956127cf8|5714|21|14|272.09|
|44|「OCAML入門」入門　https://qiita.com/kaizen_nagoya/items/456bedf9f68b512663da|5437|15|19|362.46|
|45|IT系勉強会をすべて当たりにする方法。仮説（124） https://qiita.com/kaizen_nagoya/items/9f001a79ab4162220406|5212|35|22|148.91|
|46|なぜ経済学徒を辞め、計算機屋になったか（経済学部入学前・入学後・卒業後対応） 転職(1)https://qiita.com/kaizen_nagoya/items/06335a1d24c099733f64|5137|18|10|285.38|
|47|言語規格、コーディング標準の使い方 https://qiita.com/kaizen_nagoya/items/01256365b82666e101aa|4906|20|17|245.3|
|48|日本のプログラマが世界で戦える16分野・事例。仮説（53）https://qiita.com/kaizen_nagoya/items/a7e634a996cdd02bc53b|4876|13|16|375.07|
|49|今まで書いてよかった技術書を紹介しよう！　https://qiita.com/kaizen_nagoya/items/d31b7c158541d345a7ef|4210|12|5|350.83|
|50|凡人の生き残り戦略 〜 凡人網のつくりかた 〜 https://qiita.com/kaizen_nagoya/items/c8e2af61f344761c41be|3808|21|13|181.33|
|51|公開算譜は機敏だ(An Open Source Project is Agile) GitHub with Docker。Youtube(2) 仮説（51） https://qiita.com/kaizen_nagoya/items/5dd49a046b5991af3a5e|3731|7|2|533|
|52|「ITエンジニアとしてのPC初期環境構築 [macOS編] 」に付記したいこと　https://qiita.com/kaizen_nagoya/items/08c9f7e4b968472961fd|3063|16|16|191.43|
|53|10代、20代にお勧めの資格　https://qiita.com/kaizen_nagoya/items/4e0eb6e5d30c0237469d|2892|20|16|144.6|
|54|Python3: URLをコマンドライン引数で(wikipedia) docker(90)。プログラムちょい替え（2）https://qiita.com/kaizen_nagoya/items/fc095b0c580a35001ea7|2834|3|1|944.66|
|55|データサイエンティストへの５つの門。あなたはいくつの門をくぐりましたか？統計と確率(8) https://qiita.com/kaizen_nagoya/items/ee5fa7b2a7f7c2b450d4|2717|13|14|209|
|56|50歳からのプログラミング言語入門。docker(152)https://qiita.com/kaizen_nagoya/items/5c7cec79cb3b15237076|2676|13|6|205.84|
|57|確率論及統計論輪講。仮説(95) 統計と確率(9) https://qiita.com/kaizen_nagoya/items/89d0a91a56d33529e85c|2041|4|1|510.25|
|58|設計はgit, dockerで。docker(13)https://qiita.com/kaizen_nagoya/items/5e85a825709f7f5f56ee|1855|3|2|618.33|
|59|なぜ１０歳でプログラマを目指すとよいか「小学生だった僕がプログラミングを覚えるまでにやったこと」への賛歌。仮説（18）https://qiita.com/kaizen_nagoya/items/75b0e6882b1e9c9e58db|1736|4|1|434|
|60|Githubで開発環境構築から教育環境構築、教材作成へhttps://qiita.com/kaizen_nagoya/items/493bdd22c7d318402fe2|1184|7|4|169.14|
|61|問題発見、問題解決、再発防止はGithubとDockerで。docker(143) https://qiita.com/kaizen_nagoya/items/7855011710074c3b8e3d|1160|1|0|1160|
|62|統計の嘘。仮説（127） https://qiita.com/kaizen_nagoya/items/63b48ecf258a3471c51b|1043|4|2|260.75|
|63|Posix Test Suite docker downloads, tar, install。docker(110) https://qiita.com/kaizen_nagoya/items/f1e24be04a2405ede00f|1035|0|0|#DIV/0!|
|64|四色問題 https://qiita.com/kaizen_nagoya/items/bde57da01c210402939f|998|2|0|499|
|65|構造屋(architect)としての成功２失敗６  https://qiita.com/kaizen_nagoya/items/117c7a1b6dad97470ae9|902|2|3|451|
|66|「人生で影響を受けた本100冊」に28冊足す計画（14冊） https://qiita.com/kaizen_nagoya/items/3ae6633725df77261df8|801|1|1|801|
|67|折り紙の幾何学, 伏見満枝, 伏見康治　https://qiita.com/kaizen_nagoya/items/a894d35774b112b84229|775|3|0|258.33|
|68|データ形式の昨日、今日、明日。https://qiita.com/kaizen_nagoya/items/15a77a879dcd34c458f3|569|0|0|#DIV/0!|
| |合計|1008712|6093|5678|165.55|

## goods順　

1,000以上が人気記事。300以上が良（量）記事。100以上は、すでにお手にとっていただいているかも。50以上の記事を、ぜひ、ご覧いただけると幸いです。

|No.|Title URL|Views|Goods|Stocks|G/V|
|:----|:----|:----|:----|:----|:----|
|1|プログラマが知っているとよい色使い(JIS安全色) https://qiita.com/kaizen_nagoya/items/cb7eb3199b0b98904a35|99651|1642|1641|60.68|
|2|６５歳からのプログラミング入門。docker(126)転職(16)  https://qiita.com/kaizen_nagoya/items/1561f910c275b22d7c9f|44962|743|564|60.51|
|3|プログラムは音楽だ (A program is a music.) 仮説（54）https://qiita.com/kaizen_nagoya/items/33c9f33581e6886f8ad8|36441|361|357|100.94|
|4|アセンブラへの道 https://qiita.com/kaizen_nagoya/items/46f2333c2647b0e692b2|36061|339|365|106.37|
|5|「@spaces 平成のうちにやめたかった『ITの7つの無意味な習慣』」に付け加えたかったこと。仮説（169）https://qiita.com/kaizen_nagoya/items/e6f9c2e0afbf8ab4181c|43187|271|222|159.36|
|6|プログラマで「飛び抜けた人が少ない」仮説（38）　https://qiita.com/kaizen_nagoya/items/f0d22e20f6d2c58f2c1b|21434|260|224|82.43|
|7|40年(60年）でソフトウェア開発の景色はどのぐらい変わったのか？仮説（165） https://qiita.com/kaizen_nagoya/items/54c17cf751894eef56f8|15810|248|182|63.75|
|8|製造業における機械学習　https://qiita.com/kaizen_nagoya/items/fbe846de16f74bea1d6f|34919|210|248|166.28|
|9|「ゼロから作るDeep Learning ２自然言語処理編」読書会に参加する前に読んで置くとよい資料とプログラム https://qiita.com/kaizen_nagoya/items/537b1810265bbbc70e73|32931|175|189|188.17|
|10|プログラマにも読んでほしい「QC検定にも役立つ！QCべからず集」 https://qiita.com/kaizen_nagoya/items/d8ada7b7fceafe2e5f0e|17941|172|183|104.3|
|11|人生で影響を受けた本100冊。https://qiita.com/kaizen_nagoya/items/16af53acbb147a94172e|31720|168|175|188.8|
|12|M.S.WindowsにPython3 (Anaconda3) を導入する（7つの罠）　https://qiita.com/kaizen_nagoya/items/7bfd7ecdc4e8edcbd679|169784|130|170|1306.03|
|13|データサイエンティストの気づき!「勉強だけして仕事に役立てない人。大嫌い!!」『それ自分かも!!! 』ってなった!!!! https://qiita.com/kaizen_nagoya/items/d85830d58d8dd7f71d07|18198|90|108|202.2|
|14|時間外は子育て。「 10年後のために今勉強しておきたい技術」は勤務時間内だけで。　https://qiita.com/kaizen_nagoya/items/0ad5c118a5be4d36b4d8|10429|86|68|121.26|
|15|「会議は30分未満」小耳にはさんだ話。臨機応変。　https://qiita.com/kaizen_nagoya/items/55ab43e7f50434156ff4|16055|76|44|211.25|
|16|表示画像の大きさ調整(Display Image Size Arrange)。Qiita(28)。　https://qiita.com/kaizen_nagoya/items/cef6ae1fcbdbec9e7be2|18903|71|34|266.23|
|17|最初に覚えるプログラミング言語は何がいいですか？ https://qiita.com/kaizen_nagoya/items/590704e76e287707637b|29535|66|58|447.5|
|18|C/C++, 理解,溶解,爽快。仮説（173） https://qiita.com/kaizen_nagoya/items/3f3992c9722c1cee2e3a|11424|63|65|181.33|
|19|あなたもdocker, 私もdocker。docker(130) https://qiita.com/kaizen_nagoya/items/8f2746f10f30b575d0a8|14972|60|73|249.53|
|20|「駄目だ、もう何もできない」と思った時にするかもしれないこと　https://qiita.com/kaizen_nagoya/items/d672e461a75728dd5e74|14218|54|30|263.29|
|21|人間が計算機に勝てる３つのこと。忘れる、あきらめる、やめる　https://qiita.com/kaizen_nagoya/items/49dc709d289d22846044|7425|51|25|145.58|
|22|なぜdockerでpython/Rを使って機械学習するか 書籍・ソース一覧作成中 (目標100) docker(18) https://qiita.com/kaizen_nagoya/items/ddd12477544bf5ba85e2|13587|48|61|283.06|
|23|プログラマの英語（C言語編）最初の80単語（例） https://qiita.com/kaizen_nagoya/items/701af188ef62a5b254cd|10832|45|37|240.71|
|24|「coq入門」の入門 https://qiita.com/kaizen_nagoya/items/13566f0b2083ea8d4998|9976|36|30|277.11|
|25|IT系勉強会をすべて当たりにする方法。仮説（124） https://qiita.com/kaizen_nagoya/items/9f001a79ab4162220406|5212|35|22|148.91|
|26|「直感Deep Learning」Antonio Gulli, Sujit Pal著 dockerで機械学習(3) with anaconda(3) https://qiita.com/kaizen_nagoya/items/483ae708c71c88419c32|36088|32|55|1127.75|
|27|VZエディタ移植に当たって実施したことと成果。仮説(115) https://qiita.com/kaizen_nagoya/items/5551be98dcbed8f41949|12168|31|18|392.51|
|28|情報処理技術者試験　ネットワークスペシャリストに合格 https://qiita.com/kaizen_nagoya/items/407857392ca5c5677ee4|8448|29|22|291.31|
|29|自分の頭で考えるようになるには　https://qiita.com/kaizen_nagoya/items/121a5372e3d67fc3af35|11952|26|30|459.69|
|30|効率的なHAZOPの進め方。仮説（187） https://qiita.com/kaizen_nagoya/items/2b8eae196945b7976446|15339|24|26|639.12|
|31|「DNAと遺伝情報の物理」伏見譲。統計と確率(20) https://qiita.com/kaizen_nagoya/items/150646f72c55a36f8c39|7043|23|20|306.21|
|32|５さいじがわかるcyber security（サイバセキュリティ） https://qiita.com/kaizen_nagoya/items/105173527a8e54502bb7|6713|22|10|305.13|
|33|質問の仕方の前に検索。「@shojimotio その発想はなかった！新しい質問のしかたとチーム環境作り」仮説（182）　https://qiita.com/kaizen_nagoya/items/d36e87972e6cd5f665f9|5787|22|17|263.04|
|34|「何もしていないのに壊れた」インフラエンジニアの対応例　https://qiita.com/kaizen_nagoya/items/49c58fa6f4278717d061|12572|21|18|598.66|
|35|10歳児がサイバセキュリティの専門家になるには https://qiita.com/kaizen_nagoya/items/0aa201b09187bbe39ff3|6189|21|23|294.71|
|36|QiitaでもCOBOL https://qiita.com/kaizen_nagoya/items/60596bad631956127cf8|5714|21|14|272.09|
|37|凡人の生き残り戦略 〜 凡人網のつくりかた 〜 https://qiita.com/kaizen_nagoya/items/c8e2af61f344761c41be|3808|21|13|181.33|
|38|TOPPERSまとめ　名古屋のIoTは名古屋のOSで　https://qiita.com/kaizen_nagoya/items/9026c049cb0309b9d451|7862|20|21|393.1|
|39|Microsoftとの歴史　Cコンパイラを中心に https://qiita.com/kaizen_nagoya/items/d7c0cc257e99de0573cf|6375|20|12|318.75|
|40|言語規格、コーディング標準の使い方 https://qiita.com/kaizen_nagoya/items/01256365b82666e101aa|4906|20|17|245.3|
|41|10代、20代にお勧めの資格　https://qiita.com/kaizen_nagoya/items/4e0eb6e5d30c0237469d|2892|20|16|144.6|
|42|仕様を自然言語で書くのやめませんか。「言葉にすれば」「嘘に染まる」水谷啓二・ダンシングオールナイト　もんたよしのり　https://qiita.com/kaizen_nagoya/items/dd6ee74818f1a1a1c918|6098|18|16|338.77|
|43|なぜ経済学徒を辞め、計算機屋になったか（経済学部入学前・入学後・卒業後対応） 転職(1)https://qiita.com/kaizen_nagoya/items/06335a1d24c099733f64|5137|18|10|285.38|
|44|「雑用」という名の用はない　https://qiita.com/kaizen_nagoya/items/4fda5ba89d35d24a3a78|8086|17|5|475.64|
|45|「ITエンジニアとしてのPC初期環境構築 [macOS編] 」に付記したいこと　https://qiita.com/kaizen_nagoya/items/08c9f7e4b968472961fd|3063|16|16|191.43|
|46|「OCAML入門」入門　https://qiita.com/kaizen_nagoya/items/456bedf9f68b512663da|5437|15|19|362.46|
|47|開発環境を豊かにする開発事例　過去・現在・未来 https://qiita.com/kaizen_nagoya/items/d9bf0c2c671fe7f1c749|6736|14|12|481.14|
|48|凡人は天才、秀才と違うことをして生きていくhttps://qiita.com/kaizen_nagoya/items/0502aebb7610fef584f5|7129|13|13|548.38|
|49|日本のプログラマが世界で戦える16分野・事例。仮説（53）https://qiita.com/kaizen_nagoya/items/a7e634a996cdd02bc53b|4876|13|16|375.07|
|50|データサイエンティストへの５つの門。あなたはいくつの門をくぐりましたか？統計と確率(8) https://qiita.com/kaizen_nagoya/items/ee5fa7b2a7f7c2b450d4|2717|13|14|209|
|51|50歳からのプログラミング言語入門。docker(152)https://qiita.com/kaizen_nagoya/items/5c7cec79cb3b15237076|2676|13|6|205.84|
|52|今まで書いてよかった技術書を紹介しよう！　https://qiita.com/kaizen_nagoya/items/d31b7c158541d345a7ef|4210|12|5|350.83|
|53|IT業界でやめるとよいかもしれない３つの習慣（学歴（大学名）・理系文系・年齢） https://qiita.com/kaizen_nagoya/items/f0d252d1e70ccea18efc#comment-da0f2fb4493caa2cb00e|6198|10|8|619.8|
|54|プログラミング言語教育のXYZ。Youtube(1) 仮説（52）　　https://qiita.com/kaizen_nagoya/items/1950c5810fb5c0b07be4|6222|7|14|888.85|
|55|公開算譜は機敏だ(An Open Source Project is Agile) GitHub with Docker。Youtube(2) 仮説（51） https://qiita.com/kaizen_nagoya/items/5dd49a046b5991af3a5e|3731|7|2|533|
|56|Githubで開発環境構築から教育環境構築、教材作成へhttps://qiita.com/kaizen_nagoya/items/493bdd22c7d318402fe2|1184|7|4|169.14|
|57|確率論及統計論輪講。仮説(95) 統計と確率(9) https://qiita.com/kaizen_nagoya/items/89d0a91a56d33529e85c|2041|4|1|510.25|
|58|なぜ１０歳でプログラマを目指すとよいか「小学生だった僕がプログラミングを覚えるまでにやったこと」への賛歌。仮説（18）https://qiita.com/kaizen_nagoya/items/75b0e6882b1e9c9e58db|1736|4|1|434|
|59|統計の嘘。仮説（127） https://qiita.com/kaizen_nagoya/items/63b48ecf258a3471c51b|1043|4|2|260.75|
|60|Python3: URLをコマンドライン引数で(wikipedia) docker(90)。プログラムちょい替え（2）https://qiita.com/kaizen_nagoya/items/fc095b0c580a35001ea7|2834|3|1|944.66|
|61|設計はgit, dockerで。docker(13)https://qiita.com/kaizen_nagoya/items/5e85a825709f7f5f56ee|1855|3|2|618.33|
|62|折り紙の幾何学, 伏見満枝, 伏見康治　https://qiita.com/kaizen_nagoya/items/a894d35774b112b84229|775|3|0|258.33|
|63|四色問題 https://qiita.com/kaizen_nagoya/items/bde57da01c210402939f|998|2|0|499|
|64|構造屋(architect)としての成功２失敗６  https://qiita.com/kaizen_nagoya/items/117c7a1b6dad97470ae9|902|2|3|451|
|65|問題発見、問題解決、再発防止はGithubとDockerで。docker(143) https://qiita.com/kaizen_nagoya/items/7855011710074c3b8e3d|1160|1|0|1160|
|66|「人生で影響を受けた本100冊」に28冊足す計画（14冊） https://qiita.com/kaizen_nagoya/items/3ae6633725df77261df8|801|1|1|801|
|67|Posix Test Suite docker downloads, tar, install。docker(110) https://qiita.com/kaizen_nagoya/items/f1e24be04a2405ede00f|1035|0|0|#DIV/0!|
|68|データ形式の昨日、今日、明日。https://qiita.com/kaizen_nagoya/items/15a77a879dcd34c458f3|569|0|0|#DIV/0!|
| |合計|1008712|6093|5678|165.55|

# 参考記事(Reference)
@e99h2121 育児していたからこそエンジニアのお仕事に役立ったこと10選
https://qiita.com/e99h2121/items/db7e54c111ffcd3c3957

@e99h2121「女性こそエンジニアになるべきだ？」デブサミウーマン登壇記録
https://qiita.com/e99h2121/items/7c69be1b2c2f305f6a4c

@torifukukaiou 私のAdvent Calendar 2022 ーー はじめたきっかけ、1月のふりかえり、今後の展望
https://qiita.com/torifukukaiou/items/891db4e40a7f6194af56

@kazuo_reve ワークショップ「ソフトウェア開発におけるHAZOP入門」の結果
https://qiita.com/kaizen_nagoya/items/e62e91cb019c6275d6c1

@kazuo_reve 私が効果を確認した「小川メソッド」
https://qiita.com/kazuo_reve/items/a3ea1d9171deeccc04da
## 新人(new face)
@ohakutsu 新卒2年目から見た達人プログラマーの振る舞い
https://qiita.com/ohakutsu/items/387ff8d8c09f592f124f

@kazuo_reve  マネージャ・リーダーの私にとって有益な知見が得られた書籍
https://qiita.com/kazuo_reve/items/6976029e72763ea73245#_reference-df08fb0b4ee7eedaec9d

@kazuo_reve  新人の方によく展開している有益な情報
https://qiita.com/kazuo_reve/items/d1a3f0ee48e24bba38f1

@kazuo_reve  私がデータ分析に関して「教えていただいたこと」と「大切だと実感したこと」
https://qiita.com/kazuo_reve/items/ce39ccb23d2dc501c49f

## 自己参照
 新人(学生)を指導するよりも新人(学生)に指導してもらった方が効率的。仮説（139）
https://qiita.com/kaizen_nagoya/items/db993b1536055029f7c8

心理学の本を読むよりはコンパイラ書いた方がよくね。仮説（34）
https://qiita.com/kaizen_nagoya/items/fa715732cc148e48880e

効率的なHAZOPの進め方。仮説（187）
https://qiita.com/kaizen_nagoya/items/2b8eae196945b7976446

鉄ちゃんの名古屋地下鉄・鉄道延伸・新設の展望の分析手法。鉄道(10)
https://qiita.com/kaizen_nagoya/items/7d1c41e2ad51385c28a3

Data ScientistのためのPython, R, Machine Learning/Deep Learning環境構築。docker(20)
https://qiita.com/kaizen_nagoya/items/ff16ce6f2a1af43c77f3

データサイエンティストのための分析：Qiita自己記事まとめ2020：Qiita(98) 統計と確率(23)
https://qiita.com/kaizen_nagoya/items/ff51b03848908d38d7b3

https://qiita.com/kaizen_nagoya/items/b7090bca722c5a4a66b9


「三方よし」への三つの視点
https://qiita.com/kaizen_nagoya/items/ad4ffd6d8a4045d1117a

表示画像の大きさ調整(Display Image Size Arrange)。Qiita(28)。
https://qiita.com/kaizen_nagoya/items/cef6ae1fcbdbec9e7be2
## 謝辞(Special Thanks)
@torifukukaiou Qiita 10周年記念イベント LGTMランキング！
https://qiita.com/torifukukaiou/items/69980bf263d20eab1988

に一覧を作ってくださっています。ありがとうございます。

## 一覧
物理記事　上位100
https://qiita.com/kaizen_nagoya/items/66e90fe31fbe3facc6ff

数学関連記事１００
https://qiita.com/kaizen_nagoya/items/d8dadb49a6397e854c6d

言語・文学記事　１００
https://qiita.com/kaizen_nagoya/items/42d58d5ef7fb53c407d6

医工連携関連記事一覧
https://qiita.com/kaizen_nagoya/items/6ab51c12ba51bc260a82

自動車　記事　１００
https://qiita.com/kaizen_nagoya/items/f7f0b9ab36569ad409c5

通信記事１００
https://qiita.com/kaizen_nagoya/items/1d67de5e1cd207b05ef7

日本語（０）一欄
https://qiita.com/kaizen_nagoya/items/7498dcfa3a9ba7fd1e68

英語(0) 一覧
https://qiita.com/kaizen_nagoya/items/680e3f5cbf9430486c7d

転職(0)一覧
https://qiita.com/kaizen_nagoya/items/f77520d378d33451d6fe

仮説（0）一覧（目標100現在40）
https://qiita.com/kaizen_nagoya/items/f000506fe1837b3590df

Qiita(0)Qiita関連記事一覧（自分）
https://qiita.com/kaizen_nagoya/items/58db5fbf036b28e9dfa6

鉄道（０）鉄道のシステム考察はてっちゃんがてつだってくれる
https://qiita.com/kaizen_nagoya/items/26bda595f341a27901a0

安全（0）安全工学シンポジウムに向けて: 21
https://qiita.com/kaizen_nagoya/items/c5d78f3def8195cb2409

一覧の一覧( The directory of directories of mine.) Qiita(100)
https://qiita.com/kaizen_nagoya/items/7eb0e006543886138f39

Ethernet 記事一覧　Ethernet(0)
https://qiita.com/kaizen_nagoya/items/88d35e99f74aefc98794

Wireshark 一覧 wireshark(0)、Ethernet(48) 
https://qiita.com/kaizen_nagoya/items/fbed841f61875c4731d0

線網（Wi-Fi）空中線(antenna)(0) 記事一覧(118/300目標)
https://qiita.com/kaizen_nagoya/items/5e5464ac2b24bd4cd001

OSEK OS設計の基礎　OSEK(100)
https://qiita.com/kaizen_nagoya/items/7528a22a14242d2d58a3

Error一覧 error(0)
https://qiita.com/kaizen_nagoya/items/48b6cbc8d68eae2c42b8

プログラマによる、プログラマのための、統計(0)と確率のプログラミングとその後
https://qiita.com/kaizen_nagoya/items/6e9897eb641268766909

官公庁・学校・公的団体（NPOを含む）システムの課題、官（０）
https://qiita.com/kaizen_nagoya/items/04ee6eaf7ec13d3af4c3

「はじめての」シリーズ　 ベクタージャパン　
https://qiita.com/kaizen_nagoya/items/2e41634f6e21a3cf74eb

AUTOSAR(0)Qiita記事一覧, OSEK(75)
https://qiita.com/kaizen_nagoya/items/89c07961b59a8754c869

プログラマが知っていると良い「公序良俗」
https://qiita.com/kaizen_nagoya/items/9fe7c0dfac2fbd77a945

LaTeX(0) 一覧　
https://qiita.com/kaizen_nagoya/items/e3f7dafacab58c499792

自動制御、制御工学一覧（０）
https://qiita.com/kaizen_nagoya/items/7767a4e19a6ae1479e6b

Rust(0) 一覧　
https://qiita.com/kaizen_nagoya/items/5e8bb080ba6ca0281927

小川清最終講義、最終講義（再）計画, Ethernet(100) 英語(100) 安全(100)
https://qiita.com/kaizen_nagoya/items/e2df642e3951e35e6a53

＜この記事は個人の過去の経験に基づく個人の感想です。現在所属する組織、業務とは関係がありません。＞
This article is an individual impression based on the individual's experience. It has nothing to do with the organization or business to which I currently belong.
### 文書履歴(Document History)
ver. 0.01 初稿 20210911
ver. 0.02 URL追記　20210912
ver. 0.03 みだし追加 気づき1 現場経験 気づき2 隠蔽・改竄 気づき3 この１０年、領域全体または社会に貢献できるようなプログラミングをしていなかった 20210913
ver. 0.04 表現補足 20210914
ver. 0.05 それ自分かもってなった ２箇所追記 20210915
ver. 0.06 @kazuo_reve 自分のコーディングでユーザーに喜びの声いただいたこと 追記 20210916
ver. 0.07 デザイン、確率・統計　追記 20210917
ver. 0.08 分析屋はプログラム書かなくていいんだ。追記 20210918 未明
ver. 0.09 構造見直し、目次作成 20210918 午後
ver. 0.10 日本のプログラマが世界で戦える16分野・事例。追記 20210918 夕方
ver. 0.11  確率・統計、プログラミング言語、機械学習を歴史的な順番に変更 20210919 昼。
ver. 0.12 参考記事 心理学の本を読むよりはコンパイラ書いた方がよくね。追記 20210919 午後
ver. 0.13 付録 1. データサイエンティスのプログラミング言語, Python, JavaScript, R, Ruby, Fortran 追記 20210919 夜
ver. 0.14 一部編集 20210920 午前
ver. 0.15 Qiitaに企業登録するときの指針案, lapras 値の使い道 から参照 20210920 午後
ver. 0.16 「4. docker」「5.Github, Gitlab and Bitbucket」 追記 20210921
ver. 0.17 「6. data format(markdown. json)」追記 20210922
ver. 0.18 「付録 2. 心を入れ替え努力。まだここ止まり。」追記 20210923
ver. 0.19 目次補足,謝辞, 自己参照 20210924
ver. 0.20 What are the most important statistical ideas of the past 50 years? 追記 20210925午前
ver. 0.21 なんでも統計相談室(1)(2)(3) 20210925 午後
ver. 0.22 views over 12345 感謝 20210926 
ver. 0.23 加筆 20210929
ver. 0.24 標題？ 20211002
ver. 0.25「三方よし」への三つの視点、記事どうしの競争追記 20220124
ver. 0.26 表現補正　 20220215
ver. 0.27 構成・表現補正　 20220219
ver. 0.28 @ohakutsu 新卒2年目から見た達人プログラマーの振る舞い, @e99h2121 育児していたからこそエンジニアのお仕事に役立ったこと10選 URL追記 20220220
ver. 0.29 参照記事追加・補正 20220326
ver. 0.30 表題？を！！に変更。!の四段活用　20220914
ver. 0.31 表題!!!を?に変更。!は三段活用。表題から「だけ」削除 20220918
### 最後までおよみいただきありがとうございました。
いいね　💚、フォローをお願いします。
####  Thank you very much for reading to the last sentence.
Please press the like icon 💚　and follow me for your happy life.

<a href="https://b.hatena.ne.jp/entry/s/qiita.com/kaizen_nagoya/items/d85830d58d8dd7f71d07" class="hatena-bookmark-button" data-hatena-bookmark-layout="basic-label-counter" data-hatena-bookmark-lang="ja" title="このエントリーをはてなブックマークに追加"><img src="https://b.st-hatena.com/images/v4/public/entry-button/button-only@2x.png" alt="このエントリーをはてなブックマークに追加" width="20" height="20" style="border: none;" /></a><script type="text/javascript" src="https://b.st-hatena.com/js/bookmark_button.js" charset="utf-8" async="async"></script>
https://b.hatena.ne.jp/guide/bbutton
