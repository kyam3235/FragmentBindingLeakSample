# FragmentBindingLeakSample

## 概要

DataBindingを使った時にどのような時にメモリリークが発生するためのリポジトリです。

## ブランチ

|ブランチ|説明|
|---|---|
|master|リークしないコード|
|leaked|リークするコード|

## リークさせる方法

leakedブランチでのみリークが発生します。

### 方法

NEXTボタンとBACKボタンを連打し続ける

## リーク時のprofile

