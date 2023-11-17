---
theme: light-icons
class: text-center
lineNumbers: false
info: |
  ## a-blog cms Training Camp 2023 Presentation slides

drawings:
  persist: false
transition: slide-left
title: ECテーマをつかって一覧からカートに追加するボタンを実装してみよう！
layout: title
colorSchema: 'light'
htmlAttrs:
  lang: 'ja'
image: '#FFFFFF'
---

  <div class="absolute pt-6 left-12">
    <span @click="next" class="p-1 rounded cursor-pointer hover:bg-white hover:bg-opacity-10 hover:opacity-90 opacity-60 flex justify-center items-center">
      Press Space for next page  <light-icon icon="arrow-narrow-right" size="24px"/>
    </span>
  </div>

  <div class="isolate grid place-items-center h-full z-1">
    <div>
      <div class="text-5xl/normal text-black" style="font-weight:600;" >
        ECテーマをつかって <br /> 一覧からカートに追加するボタンを <br /> 実装してみよう！
      </div>
      <span class="text-xl text-primary-lighter" style="font-weight:500;" >
        Nov. 17, 2023 a-blog cms Training Camp 2023 <light-icon class="font-bold" icon="rocket"/>
      </span>
    </div>
  </div>


---
layout: self-intro
title: 自己紹介
image: /profile.jpg
---

# 宇井 陸登

有限会社アップルップル<br />
フロントエンドエンジニア

a-blog cmsの開発や、a-blog cms でECを構築するための拡張アプリ、テーマの開発業務を担当しています。

<!--
こんいちは。有限会社アップルップルの宇井陸登です。

普段は、a-blog cmsの開発や、本日お話する、a-blog cms でECを構築するための拡張アプリ及びテーマの開発業務を担当しているエンジニアです。

1分
-->

---
layout: center-image
title: 一覧からカートに追加するイメージ
image: /add-to-cart.png
---

  <div class="mb-8">
    <span class="text-4xl text-black font-bold" >
      商品一覧ページから、カートに商品を追加できる
     <light-icon icon="shopping-cart" />
    </span>
  </div>

<!--
本日のセッションでは、a-blog cms でECサイトを構築するためのテーマをカスタマイズして、ECサイトの商品一覧ページから、直接カートに商品を追加できるボタンの実装方法を紹介します。
-->

---
layout: center-image
title: コンバージョン率が向上するイメージ
image: /data-reports.svg
---

<div class="mb-4">
    <span class="text-4xl text-black font-bold" >
      ユーザビリティ及び、コンバージョン率の向上
     <light-icon icon="chart-line" />
    </span>
  </div>

<!--
一覧ページに、直接カートに商品を追加できるようになることで、ユーザーは商品詳細ページに移動することなく、すばやく購入を進めることができるため、ECサイトのユーザビリティ及び、コンバージョン率の向上が期待できます。
-->

---
layout: section-title
title: デザイナーさん、ディレクターさん向けではないことをお知らせ
class: font-bold
---

<h1 class="!text-5xl">エンジニアさん向けの内容です 🙇</h1>

<!--
なお、今回のセッションはエンジニアさん向けの内容になります。そのため、a-blog cmsを一度も利用したことがない方や実装担当ではない Webデザイナーさんや Webディレクターの方には少しむずかしい内容になるかもしれません。そういった方にとっては a-blog cms でこういうことができるよということを知ってクライアントさんへの提案材料にしていただけると幸いです。

2分
-->

---
layout: section-title
title: ECテーマについて
---

<h1 class="font-bold">ECテーマについて 🛒</h1>

<!--
このセッションを理解するためには、ECテーマについて知っている必要がありますが、今回始めて知ったという方や、なんとなく聞いたことはあるけど詳しくは知らないという方のために簡単に説明をしたいと思います。
-->

---
layout: heading-and-body
title: 拡張アプリ「ShoppingCart」を実装したテーマ
---

<template #heading>
<h1>拡張アプリ「ShoppingCart」を実装したテーマ</h1>
</template>

<template #body>

<div class="mt-20 text-3xl">

- ショッピングカート機能
- 決済フォーム機能
- Squareと連携したオンライン決済機能

</div>

</template>

<!--
EC テーマは、a-blog cms でECサイトを制作するための拡張アプリ「ShoppingCart」の機能を事前に実装したテーマになります。

ショッピングカートや決済フォーム、Square というサービスと連携したクレジットカード決済など、ECサイトに必要な機能が組み込まれているため、
-->

---
layout: section-title
title: HTMLとCSSのカスタマイズで見た目を整えればECサイトを納品できる
class: text-center
---

<h1 class="font-bold">HTMLとCSSのカスタマイズで <br />見た目を整えれば<br />ECサイトを納品できる</h1>

<!--
HTMLとCSSのカスタマイズで見た目を整えればECサイトを納品できるといったメリットがあります。
-->

---
layout: heading-and-body
title: 料金について
---

<template #heading>
<h1>料金について</h1>
</template>

<template #body>

<div class="mt-20 text-3xl">

- ECテーマと 拡張アプリ「ShoppingCart」は無料 🎊
- a-blog cms のライセンス料金だけでECサイトを公開できる

</div>

</template>

<!--
なお、ECテーマと 拡張アプリ「ShoppingCart」は無料でダウンロードできるようになっておりますので、a-blog cms のライセンス料金だけでWeb上にECサイトを公開することができます。
-->

---
layout: image-left
image: /demo-site.png
equal: true
title: デモサイト
---

<div class="text-center">
  <h1 class="font-medium leading-relaxed">
  <a href="https://appleple.shop" target="_blank" rel="noopener noreferrer">
    DEMO
  </a>
  </h1>
</div>

<!-- 4分 -->

---
layout: dynamic-image
image: /add-to-cart-in-detail-page.png
equal: true
left: true
title: 商品詳細ページからカートへ追加ができる
---

<h1 class="font-bold">商品詳細ページから<br/>カートへ追加ができる</h1>

<!--
このように、現状のショッピングカート機能は、商品の詳細ページからカートへの商品追加ができるといった仕様となっております。
-->

---
layout: dynamic-image-with-body
image: /web-shopping.svg
equal: false
left: false
title: 一覧からカートに追加できない問題
---

<template #heading>
<h1 class="!text-3xl">一覧からカートに追加できない問題</h1>
</template>

<template #body>

<div class="mt-20 text-2xl">

- 毎回カートに商品を追加するために詳細ページに遷移するのが手間
- ユーザーの購入意欲減少の原因

</div>

</template>

<!--
詳細ページからカートへの商品追加ができる仕様は、一つ一つの商品説明をじっくり確認して購入を決めるような商品であれば問題ありません。しかし、商品それぞれが少額であり、商品の説明もそこまで必要ないような商材を扱うECサイトの場合は、毎回カートに商品を追加するために詳細ページに遷移するというステップが手間になり、ユーザーの購入意欲減少の原因となる恐れがあります。
-->

---
layout: section-title
title: 🤦
---

<div class="grid place-content-center h-full">
  <span class="text-8xl">🤦</span>
</div>

---
layout: section-title
title: ECサイトの商品一覧ページから、カートに商品を追加できれば解決
class: text-center
---

<h1 class="font-bold">商品一覧ページから、<br />カートに追加できれば解決🥹</h1>

<!--
本日のセッションでは、毎回カートに商品を追加するために詳細ページに遷移することが手間になり、購入へつながらないという課題を解決するため、ECサイトの商品一覧ページに、直接カートに商品を追加できるボタンの実装方法を紹介します。

5分
-->

---
layout: section-title
title: 実装方法紹介します！
class: text-center
---

<h1 class="font-bold">実装方法紹介します🙌</h1>

---
layout: cover-video
title: 完成品デモ
video: /demo/goal.mov
---


<!--
まずはわかりやすいように、セッションの制作物の完成品をお見せいたします。このように商品一覧ページから直接カートに商品を追加できるようになります。

6分
-->

---
layout: section-title
title: 仕組みの解説
class: text-center
---

<h1 class="font-bold">仕組みの解説</h1>

<!--
実際に実装方法の説明をする前に現状のカートへの商品の追加はどのような仕組みで動作していて、商品一覧ページから直接カートに商品を追加できるようにするために何が足りないのかを説明していきます。
-->

---
layout: dynamic-image-with-body
image: https://source.unsplash.com/collection/94734566/1920x1080
equal: true
left: false
title: ShoppingCart_AddItem
---

<template #heading>
<h1 class="!text-4xl">ShoppingCart_AddItem</h1>
</template>

<template #body>

<div class="mt-20 text-xl">

- カートに商品を追加するためのPOSTモジュール
- 商品のエントリーIDと、数量を指定してフォームを送信（POST）する

</div>

</template>

<!--
まず、カートに商品を追加する機能ですが、ShoppingCart_AddItem というPOSTモジュールで行われています。このPOSTモジュールはカートに追加するエントリー（商品）のエントリーIDと、数量のデータを受け取りカートに追加します。
-->

---
layout: dynamic-image
image: /network.png
upperImage: /expanded-network.png
equal: true
left: false
title: 開発者ツールから実際の通信を確認してみる
---

<h1 class="font-bold">
  開発者ツールから<br />実際の通信を確認🔍
</h1>

<!--
詳細ページで実装されている「カートに入れる」ボタンもエントリーIDと数量をフォームで送信することで動作しています。この送信は Ajax としてJavaScript で実装されていますので、Chromeの開発者ツールからネットワークタブを見ることで実際の通信が確認できます。
-->

---
layout: dynamic-image-with-body
image: parker-coffman-rg60lmL4AUs-unsplash.jpg
equal: false
left: false
title: 「カートに入れる」ボタン
---

<template #heading>
<h1 class="!text-4xl">「カートに入れる」ボタン</h1>
</template>

<template #body>

<div class="mt-20 text-xl">

```html {all|5-11}
<!-- include/entry/body-products.html -->

<div class="js-shopping-cart">
  <add-to-cart
    :eid="{entry:loop.eid}"
    title="{title}"
    <!-- BEGIN_IF [{item_stock}/isset] -->
    :stock="{item_stock}"
    <!-- ELSE -->
    :stock="null"
    <!-- END_IF -->
  ></add-to-cart>
</div>
```

</div>

</template>

<!--
次に実際の「カートに入れる」ボタンのテンプレートを確認してみます。
<add-to-cart></ add-to-cart> という見慣れないHTMLタグが書かれています。

また、eid、title、stock という属性で、エントリーID、商品名、在庫数の情報を渡しています。
-->

---
layout: image-right
image: /vue.svg
equal: true
title: Vue.js
---

<div>
  <h1 class="text-black" >Vue.js</h1>
</div>
<div class="leading-snug text-black dark:text-white text-opacity-60 dark:text-opacity-60">
  JavaScriptのライブラリです。
  <br/><br/>
  ユーザービリティの高いUIが構築できる！
</div>

<!--
これは Vue.js という JavaScript ライブラリの機能で作成されたタグです。Vue.js と聞いて JavaScript があまり得意でない方は「ウッ」となったかもしれません。
-->

---
layout: section-title
title: 安心してください
class: text-center
---

<h1 class="font-bold">安心してください🍵</h1>

<!--
安心してください
-->

---
layout: center-image
title: HTMLとCSSでカスタマイズできます
image: /static-website.svg
class: text-center
---

<h1 class="font-bold text-4xl mb-4">HTMLとCSSでカスタマイズできます</h1>

<!--
テンプレートのカスタマイズは、HTMLとCSSでできるようになっております。
-->

---
layout: heading-and-body
title: <add-to-cart></add-to-cart>の説明
---

<template #heading>
<h1 class="!text-3xl">
include/vue-template/add-to-cart.html
</h1>
</template>

<template #body>

<div class="mt-8 text-xl">

- `<add-to-cart></add-to-cart>` で表示されるHTMLを定義しているファイル

- `:eid` 属性に指定されたエントリーIDが次の input 要素を生成

```html
<add-to-cart
  :eid="42"
  title="商品名"
  :stock="5"
></add-to-cart>
```

```html {2}
<!-- 例えば :eidが42の場合 -->
<input type="hidden" name="eid" value="42">
<input type="hidden" name="cart[]" value="eid">
```

- このフォームで、ShoppingCart_AddItem モジュールを実行すると、エントリーIDが42の商品が、カートに追加される

</div>

</template>

---
layout: section-title
title: Entry_Summary の場合、entry:loop で {eid} を :eid 属性に指定すれば良い🤔
class: text-center
---

<h1 class="font-bold !text-3xl">
Entry_Summary の場合<br />entry:loop で {eid} を <code>:eid</code> 属性に指定すれば良い？🤔
</h1>

```html {all|5}
<!-- BEGIN entry:loop -->
...
<div class="js-shopping-cart">
  <add-to-cart
    :eid="{eid}"
    title="{title}"
    <!-- BEGIN_IF [{item_stock}/isset] -->
    :stock="{item_stock}"
    <!-- ELSE -->
    :stock="null"
    <!-- END_IF -->
  ></add-to-cart>
</div>
...
<!-- END entry:loop -->
```

<!--
ということは、Entry_Summary で一覧を表示している場合、entry:loop ブロック内で表示できる {eid} を:eid という属性に指定すれば良いのではないでしょうか？
-->

---
layout: section-title
title: やってみる
class: text-center font-bold
---

# やってみる ✌

---
layout: cover-video
title: 動画でできなかった場合のデモ
video: /demo/bad.mov
---


<!--
実際に試してみると、「カートに入れる」ボタンを押して、商品を追加することは一応できてるようです。しかし、すべての商品のフォームで色とサイズのフォーム項目が表示されてしまっています。また、カートへの追加が成功時に表示されるモーダル内の画像が破れてしまっています。これは <add-to-cart /> のテンプレートである include/vue-template/add-to-cart.html が、複数のフォームが表示されるときのことを考慮していないためです。
-->

---
layout: heading-and-body
title: 「カートに入れる」ボタン毎に異なる表示をしたい部分がうまく制御できていません。
---

<template #heading>
<h1 class="!text-3xl">
「カートに入れる」ボタン毎に表示を変えたい部分ができていない
</h1>
</template>

<template #body>

<div class="mt-20 text-2xl">

- 色とサイズのフォーム項目
- カートへの商品の追加が成功したときに表示されるモーダル内の画像

</div>

</template>

<!--
このため、フォームの色とサイズの項目や、カートへの商品の追加が成功したときに表示されるモーダル内の画像といった、「カートに入れる」ボタンそれぞれで異なる表示をしたい部分がうまく制御できていません。
-->

---
layout: bubble-frame-only
title: つまり…
class: px-20
---

<h1 class="font-bold">つまり</h1>

<div grid="~ cols-2 gap-2" class="mt-16">

<h2 class="font-bold">できる🙆</h2>

<h2 class="font-bold">できない🙅</h2>


<img border="rounded" src="https://github.com/slidevjs/themes/blob/main/screenshots/theme-default/01.png?raw=true" alt="">

<img border="rounded" src="https://github.com/slidevjs/themes/blob/main/screenshots/theme-seriph/01.png?raw=true" alt="">

</div>

<!--
つまり、カートへの商品の追加は、 <add-to-cart /> を設置するだけでできるが、「カートに入れる」ボタンそれぞれで異なる表示をすることができていないということになります。

11分
-->

---
layout: section-title
title: 実装方法の解説
class: text-center font-bold
---

# 実装方法の解説 🧑‍🏫

---
layout: heading-and-body
title: Vue.js の名前付きスロット機能を使って解決
image: /add-to-cart.svg
---

<template #heading>
<h1 class="!text-3xl">
【Vue.js】 名前付きスロット機能
</h1>
</template>

<template #body>

<div class="mt-20 text-2xl">

- Vue.js の機能
- コンポーネント毎にどのようなHTMLを表示するか変更できる
- a-blog cms でいうと、テンプレートの継承機能

</div>

</template>

<!--
この問題を解決するためには Vue.js の 名前付きスロット という機能を活用します。名前付きスロットを利用することで、Vue.js で作成したコンポーネントの呼び出し側でどのようなHTMLを表示するかを制御することができるようになります。
-->

---
layout: bubble-frame-only
title: テンプレートの継承機能とやりたいことは同じ
class: px-20
---

<h1 class="font-bold !text-4xl !mb-8">テンプレートの継承機能とやりたいことは同じ</h1>

<div grid="~ cols-2 gap-2" m="-t-2">

<h2 class="font-bold">a-blog cms</h2>

<h2 class="font-bold">Vue.js</h2>


```html
<!-- 継承されるテンプレート -->
<header>ヘッダーは共通パーツ</header>

@section(main)
  <h2>継承元のコンテンツ</h2>
@endsection

<!-- 継承するテンプレート -->
@extends(/layout/base.html)

@section(main)
  <h2>継承したメインのコンテンツ</h2>
@endsection
```

```html
<!-- 継承されるテンプレート -->
<template>
  <header>ヘッダーは共通パーツ</header>

  <slot name="main">
    <h2>継承元のコンテンツ</h2>
  </slot>
</template>

<!-- 継承するテンプレート -->
<base>
  <template #main>
    <h2>継承したメインのコンテンツ</h2>
  </template>
</base>
```

</div>

<!--
Vue.js のスロット機能を a-blog cms の機能に置き換えるとテンプレートの継承機能に該当します。テンプレートの継承機能では基本的には継承元のテンプレートだけど、継承先で部分的に変更したいところだけ@section 要素で囲んでおくと思います。その Vue.js 版が スロットだと思っていただけるとわかりやすいかと思います。
-->

---
layout: heading-and-body
title: 色とサイズの項目をスロットで動的化 その1
---

<style>
  pre {
    max-height: 430px!important;
  }
</style>

<template #heading>
<h1 class="!text-3xl">
色とサイズの項目をスロットで動的化
</h1>
</template>

<template #body>

<div class="">

```html {6-35}
<!-- include/vue-template/add-to-cart.html -->
<script id="AddToCart" type="text/x-template" class="check-csrf-token">
  <form ref="form" @submit.prevent="addToCart">
    <div class="entry-price-bottom-box">
      <table v-if="remain > 0" class="entry-item-select-table">
        <!-- BEGIN color:veil -->
        <tr>
          <th>色選択</th>
          <td>
            <select name="item_color">
              <option value="">選択してください</option>
              <!-- BEGIN color:loop -->
              <option value="{color}">{color}</option>
              <!-- END color:loop -->
              <input type="hidden" name="field[]" value="item_color" />
              <input type="hidden" name="item_color:validator#required" />
            </select>
          </td>
        </tr>
        <!-- END color:veil -->
        <!-- BEGIN size:veil -->
        <tr>
          <th>サイズ</th>
          <td>
            <select name="item_size">
              <option value="">選択してください</option>
              <!-- BEGIN size:loop -->
              <option value="{size}">{size}</option>
              <!-- END size:loop -->
              <input type="hidden" name="field[]" value="item_size" />
              <input type="hidden" name="item_size:validator#required" />
            </select>
          </td>
        </tr>
        <!-- END size:veil -->
        <tr>
          <th>個数</th>
          <td>
            <quantity-select
              :max-quantity="remain"
              name="quantity"
            />
            <input type="hidden" name="cart[]" value="quantity">
          </td>
        </tr>
      </table>
    </div>
    ...
  </form>
  ...
</script>
```

</div>

</template>

<!--
今回は、フォームの上部と、カートへの商品の追加が成功したときに表示されるモーダルの画像を「カートに入れる」ボタン毎に変更したいので、 form-header と success-modal-content というスロットを作成します。
-->

---
layout: heading-and-body
title: 色とサイズの項目をスロットで動的化 その2
---

<template #heading>
<h1 class="!text-3xl">
色とサイズの項目をスロットで動的化
</h1>
</template>

<template #body>

<div class="">

```html {6}
<!-- include/vue-template/add-to-cart.html -->
<script id="AddToCart" type="text/x-template" class="check-csrf-token">
  <form ref="form" @submit.prevent="addToCart">
    <div>
      <table v-if="remain > 0" class="add-to-cart-table">
        <slot name="form-header"></slot>
        <tr>
          <th>個数</th>
          <td>
            <quantity-select
              :max-quantity="remain"
              name="quantity"
            />
            <input type="hidden" name="cart[]" value="quantity">
          </td>
        </tr>
      </table>
    </div>
    ...
  </form>
  ...
</script>
```

</div>

</template>

---
layout: heading-and-body
title: モーダルの画像をスロットで動的化 その1
---

<template #heading>
<h1 class="!text-3xl">
モーダルの画像をスロットで動的化
</h1>
</template>

<template #body>

<div class="">

```html {16-44}
<!-- include/vue-template/add-to-cart.html -->
<script id="AddToCart" type="text/x-template" class="check-csrf-token">
  ...
  <modal
    :isOpen="added"
    :onClose="() => setAdded(false)"
    :closeTimeout="300"
    aria-labelledby="shopping-cart-modal-title"
    aria-describedby="shopping-cart-modal-content"
  >
    <template #header>
      <h2 id="shopping-cart-modal-title" class="modal-title">「{{ title }}」をカートに追加しました</h2>
    </template>
    <template #default>
      <div id="shopping-cart-modal-content" class="modal-img-wrap">
        <!-- BEGIN_IF [{item_image@path}/nem] -->
          <img
            class="acms-img-responsive"
            src="%{MEDIA_ARCHIVES_DIR}{item_image@path}[resizeImg(300)]"
            width="300"
            height="{item_image@ratio}[getHeightFromRatio(300)]"
            alt="{item_image@alt}"
          >
        <!-- ELSE -->
        <!-- BEGIN_MODULE Blog_Field id="BF_root" -->
          <!-- BEGIN_IF [{noimage@path}/nem] -->
          <img
            class="acms-img-responsive"
            src="%{MEDIA_ARCHIVES_DIR}{noimage@path}[resizeImg(300)]"
            alt="{noimage@alt}"
            width="300"
            height="{noimage@ratio}[getHeightFromRatio(300)]"
          >
          <!-- ELSE -->
          <img
            class="acms-img-responsive"
            data-src="/images/noimage.png"
            alt="noimage画像"
            width="300"
            height="168"
          />
          <!-- END_IF -->
        <!-- END_MODULE Blog_Field -->
        <!-- END_IF -->
      </div>
    </template>
    <template #footer>
      <div class="modal-btn-wrap">
        <button type="button" class="btn is-secondary" @click="setAdded(false)">買い物を続ける</button>
        <a href="%{BASE_URL}cart/" class="btn">注文手続きに進む</a>
      </div>
    </template>
  </modal>

  ...
</script>
```

</div>

</template>

---
layout: heading-and-body
title: モーダルの画像をスロットで動的化 その2
---

<template #heading>
<h1 class="!text-3xl">
モーダルの画像をスロットで動的化
</h1>
</template>

<template #body>

<div class="">

```html {16}
<!-- include/vue-template/add-to-cart.html -->
<script id="AddToCart" type="text/x-template" class="check-csrf-token">
  ...
  <modal
    :isOpen="added"
    :onClose="() => setAdded(false)"
    :closeTimeout="300"
    aria-labelledby="shopping-cart-modal-title"
    aria-describedby="shopping-cart-modal-content"
  >
    <template #header>
      <h2 id="shopping-cart-modal-title" class="modal-title">「{{ title }}」をカートに追加しました</h2>
    </template>
    <template #default>
      <div id="shopping-cart-modal-content" class="modal-img-wrap">
        <slot name="success-modal-content"></slot>
      </div>
    </template>
    <template #footer>
      <div class="modal-btn-wrap">
        <button type="button" class="btn is-secondary" @click="setAdded(false)">買い物を続ける</button>
        <a href="%{BASE_URL}cart/" class="btn">注文手続きに進む</a>
      </div>
    </template>
  </modal>

  ...
</script>
```

</div>

</template>


---
layout: heading-and-body
title: Entry_Summaryのentry:loopブロックで <add-to-cart></add-to-cart> を使う
---

<template #heading>
<h1 class="!text-3xl">

Entry_Summaryのentry:loopブロックで使う

</h1>
</template>

<template #body>

<div class="">

```html {all|13-44|45-75}
<!-- BEGIN entry:loop -->
...
<div class="js-shopping-cart">
  <add-to-cart
    :eid="{eid}"
    title="{title}"
    <!-- BEGIN_IF [{item_stock}/isset] -->
    :stock="{item_stock}"
    <!-- ELSE -->
    :stock="null"
    <!-- END_IF -->
  >
    <template #form-header>
      <!-- BEGIN color:veil -->
      <tr>
        <th>色選択</th>
        <td>
          <select name="item_color">
            <option value="">選択してください</option>
            <!-- BEGIN color:loop -->
            <option value="{color}">{color}</option>
            <!-- END color:loop -->
            <input type="hidden" name="field[]" value="item_color" />
            <input type="hidden" name="item_color:validator#required" />
          </select>
        </td>
      </tr>
      <!-- END color:veil -->
      <!-- BEGIN size:veil -->
      <tr>
        <th>サイズ</th>
        <td>
          <select name="item_size">
            <option value="">選択してください</option>
            <!-- BEGIN size:loop -->
            <option value="{size}">{size}</option>
            <!-- END size:loop -->
            <input type="hidden" name="field[]" value="item_size" />
            <input type="hidden" name="item_size:validator#required" />
          </select>
        </td>
      </tr>
      <!-- END size:veil -->
    </template>
    <template #success-modal-content>
      <!-- BEGIN_IF [{item_image@path}/nem] -->
      <img
        class="acms-img-responsive"
        src="%{MEDIA_ARCHIVES_DIR}{item_image@path}[resizeImg(300)]"
        width="300"
        height="{item_image@ratio}[getHeightFromRatio(300)]"
        alt="{item_image@alt}"
      >
      <!-- ELSE -->
      <!-- BEGIN_MODULE Blog_Field id="BF_root" -->
        <!-- BEGIN_IF [{noimage@path}/nem] -->
        <img
          class="acms-img-responsive"
          src="%{MEDIA_ARCHIVES_DIR}{noimage@path}[resizeImg(300)]"
          alt="{noimage@alt}"
          width="300"
          height="{noimage@ratio}[getHeightFromRatio(300)]"
        >
        <!-- ELSE -->
        <img
          class="acms-img-responsive"
          data-src="/images/noimage.png"
          alt="noimage画像"
          width="300"
          height="168"
        />
        <!-- END_IF -->
      <!-- END_MODULE Blog_Field -->
      <!-- END_IF -->
    </template>
  </add-to-cart>
</div>
...
<!-- END entry:loop -->
```

</div>

</template>

<!--
そして<add-to-cart /> を呼び出す側、 Entry_Summary モジュールの entry:loop ブロックで、フォームの色とサイズの項目や、カートへの商品の追加が成功したときに表示されるモーダル内の画像のHTMLを記述します。
-->

---
layout: heading-and-body
title: add-to-cart.htmlを読み込むのを忘れずに！
---

<template #heading>
<h1 class="!text-3xl">

add-to-cart.htmlを読み込むのを忘れずに！

</h1>
</template>

<template #body>

<div class="mt-20">

```html
<!-- include vue template -->
@include("/include/vue-template/add-to-cart.html")

<!-- BEGIN_MODULE Entry_Summary id="{{module_id}}" -->
...
<!-- END_MODULE Entry_Summary -->
```

</div>

</template>

---
layout: heading-and-body
title: カスタマイズ後の動作確認
---

<template #heading>
<h1>カスタマイズ後の動作確認 🔍</h1>
</template>

<template #body>

<div class="h-full w-full grid place-content-center mt-25 text-center">
  <div>
      <img
        src="/demo/qr.png"
        alt="動作確認用のデモ環境環境にアクセスするためのQRコード"
        class="m-auto"
      >
  </div>
  <div>
    <a href="https://7bq44ng3.ablogcms.io/" class="text-4xl text-black font-bold" target="_blank" rel="noopener noreferrer">
      https://7bq44ng3.ablogcms.io/
    </a>
  </div>
</div>

</template>

<!--
これで一覧ページから商品一覧ページに、直接カートに商品を追加できるようになったと思うので、実際の動作を確認してみましょう。
-->

---
layout: section-title
title: できた！
class: text-center font-bold
---

# できた！🎉

<!--
はい、フォームの色とサイズの項目が必要なエントリーにだけ表示されていることと、カートへの商品の追加が成功したときに表示されるモーダル内の画像がそれぞれのエントリー毎に変わっていることが確認できました。

14分
-->

---
layout: section-title
title: まとめ
class: text-center font-bold
---

# まとめ

<!--
ではセッション時間もそろそろ終了となりますので、最後にセッションのポイントをお伝えして終わりにしたいと思います。
-->

---
layout: section-title
title: 一覧からカートに商品を追加するボタンで、ECサイトのユーザビリティ、そして売上をアップさせよう！
class: text-center font-bold
---

<h1 class="!text-3xl !leading-10">一覧からカートに商品を追加するボタンで<br />ECサイトのユーザビリティ、そして売上をアップさせよう！💸</h1>

<!--
一覧からカートに商品を追加するボタンで、ECサイトのユーザビリティそして売上を向上させましょう！
-->

---
layout: section-title
title: ECテーマなら、HTMLとCSSとちょっとの Vue の知識で、一覧からカートに商品を追加するボタンの実装ができる
class: text-center font-bold
---

<h1 class="!text-3xl !leading-10">ECテーマなら<br />HTMLとCSSとちょっとの Vue の知識で<br />一覧からカートに商品を追加するボタンの実装ができる👏</h1>

<!--
そして、ECテーマなら、HTMLとCSSとちょっとの Vue の知識で、一覧からカートに商品を追加するボタンの実装ができてしまうということです。

プログラムを書かなくても柔軟にカスタマイズできるシステムをお求めの方は是非試してみていただけますと嬉しいです。
-->

---
layout: cover
title: a-blog cms Ver. 3.1 に対応したバージョンをリリース
background: /release-new-version.png
class: text-center
---

<h1 class="!text-5xl">Ver. 3.1 対応のバージョンをリリース</h1>
<div>
  <a href="https://www.a-blogcms.jp/lp/square/" class="text-sm text-white font-bold" target="_blank" rel="noopener noreferrer">
    https://www.a-blogcms.jp/lp/square/
  </a>
</div>

<!--
すぐに利用できるように、合宿に合わせてa-blog cms Ver. 3.1 に対応したバージョンをリリースしております。
-->

---
layout: section-title
title: ご清聴ありがとうございました
class: text-center font-bold
---

# ご清聴ありがとうございました🙇

<!--
皆さん、いかがでしたでしょうか？最後の方は少し駆け足となってしまいましたが、皆様の参考になればと思います。これで発表を終わりたいと思います。質問がある方は、ぜひお気軽にどうぞ。それでは、ご清聴ありがとうございました。
-->

---
layout: bubble-frame-only
title: X（旧Twitter）やってます
---
<h1 class="font-bold !text-5xl"> X（旧Twitter）やってます！</h1>
<div class="h-full w-full grid place-content-center">
  <div>
    <img
      src="/x-qr.png"
      alt="X（旧Twitter）のQRコード"
    >
  </div>
</div>

<!-- 15分 -->
