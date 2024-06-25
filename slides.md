---
theme: default
layout: image
image: /first.png
class: text-center
transition: "slide-left"
colorSchema: light
defaults:
  fonts:
    sans: Noto Sans JP
---

<div class="flex items-center justify-center h-full">
  <div>
    <div class="text-black font-bold text-[60px]">ここに<br />タイトルです</div>
  </div>

  <div class="font-bold text-black absolute bottom-[80px] text-[24px]">
    <div>2024.7.1</div> 
    <div>部署部署部署 氏名氏名氏名</div>
  </div>
</div>

---

# 自己紹介

- こんにちは
- こんにちは
- こんにちは

---

# 画像の例

- 画像の例

<div class="flex items-center gap-[8px] mt-[20px] container">
  <img src="/link-card_1.png" class="h-[130px]">
  <div>➡️</div>
  <img src="/link-card_2.png" class="h-[130px]">
</div>

---

# 箇条書きじゃない文字

<div class="container">こんにちは</div>

---

# コードを貼り付ける

- `npm i open-graph-scraper`
- 使い方の例
  ```ts
  const ogs = require('open-graph-scraper');
  const options = { url: 'http://ogp.me/' };
  const data = await ogs(options)
  const { error, html, result, response } = data;
  console.log('error:', error);  // This returns true or false. True if there was an error. The error itself is inside the result object.
  console.log('html:', html); // This contains the HTML of page
  console.log('result:', result); // This contains all of the Open Graph results
  console.log('response:', response); // This contains response from the Fetch API
  ```

---

# 参考

- [クラスメソッド株式会社](https://classmethod.jp/)
