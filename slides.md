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
image: '/profile.jpg'
---

# 宇井 陸登

有限会社アップルップル<br />
フロントエンドエンジニア

a-blog cmsの開発や、a-blog cms でECを構築するための拡張アプリ、テーマの開発業務を担当しています。

---
layout: center-image
title: 一覧からカートに追加するイメージ
image: '/add-to-cart.svg'
---
  <div class="mb-4">
    <span class="text-4xl text-black font-bold" >
      商品一覧ページから、カートに商品を追加できる
     <light-icon icon="shopping-cart" />
    </span>
  </div>

---
layout: center-image
title: コンバージョン率が向上するイメージ
image: '/data-reports.svg'
---
  <div class="mb-4">
    <span class="text-4xl text-black font-bold" >
      ユーザビリティ及び、コンバージョン率の向上
     <light-icon icon="chart-line" />
    </span>
  </div>

---
layout: section-title
title: デザイナーさん、ディレクターさん向けではないことをお知らせ
---

# エンジニアさん向けの内容です

---
layout: section-title
title: ECテーマについて
---

<h1 class="font-bold">ECテーマについて 🛒</h1>

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

---
layout: section-title
title: HTMLとCSSのカスタマイズで見た目を整えればECサイトを納品できる
class: text-center
---

<h1 class="font-bold">HTMLとCSSのカスタマイズで <br />見た目を整えれば<br />ECサイトを納品できる</h1>

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

---
layout: image-left
image: /how-to-download.png
equal: true
title: ダウンロード
---

<div class="text-center">
  <h1 class="font-medium leading-relaxed">
  <a href="https://developer.a-blogcms.jp/document/ec-cart/Install.html" target="_blank" rel="noopener noreferrer">
    ダウンロード <light-icon icon="download" size="48px"/>
  </a>
  </h1>
</div>

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

---
layout: dynamic-image
image: '/add-to-cart-in-detail-page.png'
equal: true
left: true
title: 商品詳細ページからカートへ追加ができる
---

<h1 class="font-bold">商品詳細ページから<br/>カートへ追加ができる</h1>


---
layout: dynamic-image-with-body
image: '/web-shopping.svg'
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

---
layout: section-title
title: 実装方法紹介します！
class: text-center
---

<h1 class="font-bold">実装方法紹介します🙌</h1>

---
layout: section-title
title: 完成品デモ
class: text-center
---

<h1 class="font-bold">完成品デモ</h1>

<!-- 動画でデモしたいかも -->

---
layout: section-title
title: 仕組みの解説
class: text-center
---

<h1 class="font-bold">仕組みの解説</h1>

---
layout: dynamic-image-with-body
image: 'https://source.unsplash.com/collection/94734566/1920x1080'
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

---
layout: dynamic-image
image: '/network.png'
upperImage: '/expanded-network.png'
equal: true
left: false
title: 開発者ツールから実際の通信を確認してみる
---

<h1 class="font-bold">
  開発者ツールから<br />実際の通信を確認🔍
</h1>

---
layout: dynamic-image-with-body
image: 'parker-coffman-rg60lmL4AUs-unsplash.jpg'
equal: false
left: false
title: 「カートに入れる」ボタン
---


<template #heading>
<h1 class="!text-4xl">「カートに入れる」ボタン</h1>
</template>

<template #body>

<div class="mt-20 text-xl">

```html
<!-- include/entry/body-products.html -->

<div class="js-shopping-cart">
  <add-to-cart
    :eid="{entry:loop.eid}"
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

---
layout: section-title
title: 安心してください
class: text-center
---

<h1 class="font-bold">安心してください🍵</h1>

---
layout: center-image
title: HTMLとCSSでカスタマイズできます
image: '/static-website.svg'
class: text-center
---

<h1 class="font-bold text-4xl mb-4">HTMLとCSSでカスタマイズできます</h1>

---
layout: heading-and-body
title: <add-to-cart></add-to-cart>の説明
---

<template #heading>
<h1 class="!text-3xl">

  `<add-to-cart></add-to-cart>`

</h1>
</template>

<template #body>

<div class="mt-20 text-2xl">

`<add-to-cart :eid="{eid}" :stock="{stock}"></add-to-cart>` が include/vue-template/add-to-cart.html で定義されているHTMLに置き換わる

`:eid` 属性に指定されたエントリーIDが次の input 要素を生成

```html {2}
<!-- 例えば :eidが42の場合 -->
<input type="hidden" name="eid" value="42">
<input type="hidden" name="cart[]" value="eid">
```

このフォームで、ShoppingCart_AddItem モジュールを実行すると、エントリーIDが42の商品が、カートに追加される

</div>

</template>

---
layout: section-title
title: Entry_Summary の場合、entry:loop で {eid} を :eid 属性に指定すれば良い🤔
class: text-center
---

<h1 class="font-bold !text-4xl">
Entry_Summary の場合、<br />entry:loop で {eid} を <code>:eid</code> 属性に指定すれば良い🤔
</h1>

```html {all|5}
<!-- BEGIN entry:loop -->
...
<div class="js-shopping-cart">
  <add-to-cart
    :eid="{eid}"
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

---
layout: section-title
title: 動画でできなかった場合のデモ
class: text-center
---

# 動画でできなかった場合のデモを見せたい

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

---
layout: section-title
title: 実装方法の解説
class: text-center font-bold
---

# 実装方法の解説 🧑‍🏫

---
layout: heading-and-body
title: Vue.js の名前付きスロット機能を使って解決
image: '/add-to-cart.svg'
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

---
layout: bubble-frame-only
title: つまり…
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
    <div class="entry-price-bottom-box">
      <table v-if="remain > 0" class="entry-item-select-table">
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

```html {8-39|40-70}
<!-- BEGIN entry:loop -->
...
<div class="js-shopping-cart">
  <add-to-cart
    :eid="{eid}"
    :stock="<!-- BEGIN_IF [{item_stock}/isset] -->{item_stock}<!-- ELSE -->null<!-- END_IF -->"
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
layout: section-title
title: カスタマイズ後の動作確認
class: text-center font-bold
---

# カスタマイズ後の動作確認 🔍

---
layout: section-title
title: できた！
class: text-center font-bold
---

# できた！🎉

---
layout: section-title
title: まとめ
class: text-center font-bold
---

# まとめ

---
layout: section-title
title: ECテーマなら、HTMLとCSSとちょっとの Vue の知識で、一覧からカートに商品を追加するボタンの実装ができる
class: text-center font-bold
---

<h1 class="!text-3xl !leading-10">ECテーマなら、<br />HTMLとCSSとちょっとの Vue の知識で、<br />一覧からカートに商品を追加するボタンの実装ができる👏</h1>

---
layout: cover
title: a-blog cms Ver. 3.1 に対応したバージョンをリリース
background: '/release-new-version.png'
class: text-center
---

<h1 class="!text-5xl">Ver. 3.1 対応のバージョンをリリース</h1>

---
layout: section-title
title: ご清聴ありがとうございました
class: text-center font-bold
---

# ご清聴ありがとうございました🙇

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

