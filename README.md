# LOAJ Visualization Sample App.

[Linked Open Addresses Japan(試作版)](http://uedayou.net/loa/)のデータを使ったビジュアライズアプリのサンプルです。  

## 使い方

data[n].uri に Linked Open Addresses Japan の行政区画の境界データを持つ住所URIを入れると、地図上に境界データを表示します。

    var data = [
        {uri:"http://uedayou.net/loa/東京都あきる野市"},
        ...
    ];

Linked Open Addresses Japn のデータを使えば、GeojsonやShapeファイル等、GISデータを直接扱うことなくビジュアライズが可能です。  

## デモ

<http://uedayou.net/loaviz/>  

