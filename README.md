<p align="center">
<img src="https://github.com/xb2016/lmgtfy/raw/master/lmgtfy.png" alt="讓我幫您 Google 一下">
</p>

<h3 align="center"> 「Let Me Google That For You」</h3>

<p align="center">
<img alt="Author" src="https://img.shields.io/badge/Author-Moedog-blue.svg?style=flat-square">
<img alt="License" src="https://img.shields.io/github/license/xb2016/lmgtfy.svg?style=flat-square"/>
</p>

## 基本介紹


創意來自於「讓我幫你百度一下」，這玩意出來好久了，同時，「讓我幫你谷歌一下」也有，不過有各種不方便，要麼就是年代久遠，用的舊樣式，要麼就是境內訪問有點難度。所以抽空改了一個出來。

感謝 [Sukka](https://github.com/SukkaW) 提供網絡環境判斷方案。

基於這兩個項目：[https://github.com/bangbang93/lmbtfy.cn](https://github.com/bangbang93/lmbtfy.cn) 以及[https://github.com/mengkunsoft/lmbtfy](https://github.com/mengkunsoft/lmbtfy)

演示站點：[https://moedog.org/tools/google/](https://moedog.org/tools/google/)

## 食用注意

首先，環境需要 PHP，用於生成短鏈接用的；其次，要提到這個程序的一個優點，它可以判斷使用者的網絡能不能訪問谷歌，如果不能，則調用反代站點訪問。

但是這個反代站需要程序搭建者自己準備了，本程序自帶的只能由我站調用。

編輯 lmgtfy.js ，把 www.loli.cab 換成你自己的谷歌反代鏈接，實在沒有就換成 www.google.com 吧。

## 捐贈

- [https://pay.fczbl.vip](https://pay.fczbl.vip)

## Author

**lmgtfy** © [Moedog](https://github.com/xb2016), Released under the [MIT](./LICENSE) License.<br>

> Blog [moedog.org](https://moedog.org) · GitHub [@xb2016](https://github.com/xb2016) · Twitter [@moesdog](https://twitter.com/moesdog)