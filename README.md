# GreenCamp

## 要件
- 検証
	Chrome, Edge, Firefox

- リセットCSS
	css/reset.css のファイル名で用意してあります。
	Josh W. Comeau氏によるリセットCSS("Josh's Custom CSS Reset")を使用します。
	https://coliss.com/articles/build-websites/operation/css/my-custom-css-reset.html

- 命名規則
	BEM
	https://qiita.com/takahirocook/items/01fd723b934e3b38cbbc

- img要素のwidth, height
	指定して下さい

- インデントを調整する
- PDF指示を明確にする
	- flex に導かれるように、要素間のgapを統一する
	- font

- SlickNav - Responsive Mobile Menu Plugin for jQuery
	https://computerwolf.github.io/SlickNav/
	CDN:
	https://github.com/ComputerWolf/SlickNav
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/SlickNav/1.0.10/slicknav.min.css" />
	<script src="https://cdnjs.cloudflare.com/ajax/libs/SlickNav/1.0.10/jquery.slicknav.min.js"></script>
	jQuery CDN:
	https://developers.google.com/speed/libraries?hl=ja#jquery
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.4/jquery.min.js"></script>

## 指示

HTMLファイル名：index.html
CSS書類名：css/style.css
主要言語：日本語
文字コード：utf-8
検索サイトに検索されないように設定してください。
タイトル：Green Camp
サイトの説明：Green Campでは、自然の中にある「森林探検隊」を運営しています。森林探検隊では、四季を通してイベントを開催したり、さまざまな商品の開発を行ってます。
ファビコン：favicon.ico

## その他指示
書体設定：　"メイリオ", Meiryo, "ＭＳ Ｐゴシック", "MS PGothic", "ヒラギノ角ゴ Pro W3", "Hiragino Kaku Gothic Pro", Osaka, sans-serif;

bodyに背景画像「back.gif」を配置。

h3 ボーダーカラー：#1a401a

photo01.jpg　代替えテキスト：森の木々に囲まれたロッジ風の探検基地の写真

photo02.jpg　代替えテキスト：雪が積もった雑木林の写真

photo03.jpg　代替えテキスト：探検基地に現れた野うさぎの写真

spring.jpg　イメージ画像なので代替えテキストの内容は不要

night.jpg　イメージ画像なので代替えテキストの内容は不要

footer　カラー：#1a401a

## Slick の導入

<link rel="stylesheet" href="css/slicknav.css">
<link rel="stylesheet" href="css/effct.css">
<script src="http://ajax.googleapis.com/ajax/libs/jquery/1/jquery.min.js"></script>
<script src="js/jquery.slicknav.min.js"></script>
<script>
  $(document).ready(function () {
    $('.menu').slicknav();
  });

  $('.menu').slicknav({
    label: '',
    prependTo: '.menu2',
    brand: ''
  });

  $(".slicknav_btn").click(function () {
    $(this).toggleClass("active");
  });
</script>

## テキスト素材

Green Camp

森林探検隊
季節のイベント
アクセスマップ
お問い合わせ
ブログ

Green Campは自然のあれこれをお届けする森林探検隊です
 
森林探検隊について

Green Campでは、自然の中にある「森林探検隊」を運営しています。森林探検隊では、四季を通してイベントを開催したり、さまざまな商品の開発を行ってます。

森の中にある探検基地

画像

森林探検隊は、木々のあふれる森の中にあります。森の入口から細い小道を通り、森の奥に進んでください。しばらくすると、森の中にある小さな丘に出てきます。その丘の上にある木造の建物が「森林探検隊」です。

この丘はちょうど森の中央に位置しており、森の中を散歩したり、自然の中で遊んだりするときにも、ちょうどいい拠点になります。森全体を見渡すことも可能で、夜は満点の星空を満喫できます。

四季を楽しむことができる場所

画像

森林探検隊では、春、夏、秋、冬と、四季折々の自然を楽しむことができます。

春には、雪解け水の中から芽を出す新しい命や、新緑の鮮やかな緑。夏には、緑濃く茂った木々の間を吹き抜けるさわやかな風に、川の清流での水遊び。秋には、森全体が赤や黄色に染まり、色鮮やかな紅葉に包まれます。木々の葉が落ち、冬になると、ここは雪に覆われて一面の銀世界になります。

探検基地のまわりにいる動物たち

画像

探検基地のまわりにはいろいろな動物たちが棲んでいます。キツネ、タヌキ、イタチ、ウサギ、リス、シカ、イノシシ…。森の中で出会うこともあれば、ひょこっと探検基地に顔を出すこともあります。土や雪の上に残った足跡から、正体を探るのも楽しみです。

ただし、森林探検隊では彼らに餌をやることはしていません。自然にあるがままの姿で、いっしょに生活していきたいと考えているからです。彼らに出会ったときには、びっくりさせないように遠くからそっと眺めてあげてください。

Green Camp イベント情報

春のお散歩ウィーク

（イメージ画像）春の花が咲き始め、木々の新緑がまぶしくなるころ、毎年「春のお散歩ウィーク」を開催しています。

ホタル観賞会

（イメージ画像）探検基地の近くの池でホタル観賞会を開催します。ここにはホタルが自生しており、周囲には明るい民家や外灯などもありませんので、真っ暗な闇の中を飛び交う幻想的なホタルの光を見ることができます。

 (c) Green Camp



