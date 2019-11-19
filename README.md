[![AndroidStudio](https://img.shields.io/badge/AndroidStudio-v3.5.2-green)](https://developer.android.com/studio)

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

<img width="964" alt="スクリーンショット 2019-11-20 0 32 34" src="https://user-images.githubusercontent.com/11660859/69161127-fe884a00-0b2d-11ea-9233-366091aa29e6.png">
