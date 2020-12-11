Block Elements
Headers đầu dòng
Thêm dấu # vào đầu dòng. sẽ tạo được bậc
# Bậc 1
## Bậc 2
### Bậc 3
#### Bậc 4
##### Bậc 5
###### Bậc 6
Bậc 1
Bậc 2
Bậc 3
Bậc 4
Bậc 5
Bậc 6
Block xuống dòng
空白行を挟むことで段落となります。

段落1
(空行)
段落2
段落1

段落2

Br 改行
改行の前に半角スペース を2つ記述します。

hoge
fuga(スペース2つ)
piyo
hoge fuga
piyo

Blockquotes 引用
先頭に>を記述します。ネストは>を多重に記述します。

> 引用  
> 引用
>> 多重引用
引用
引用

多重引用

Code コード
`バッククオート` 3つ、あるいはダッシュ~３つで囲みます。

print 'hoge'
print 'hoge'
インラインコード
`バッククオート` で単語を囲むとインラインコードになります。

これは `インラインコード`です。
これは インラインコードです。

pre 整形済みテキスト
半角スペース4個もしくはタブで、コードブロックをpre表示できます

    class Hoge
        def hoge
            print 'hoge'
        end
    end
class Hoge
    def hoge
        print 'hoge'
    end
end
Hr 水平線
アンダースコア_ 、アスタリスク*、ハイフン-などを3つ以上連続して記述します。

hoge
***
hoge
___
hoge
---
hoge

hoge

hoge
Lists
Ul 箇条書きリスト
ハイフン-、プラス+、アスタリスク*のいずれかを先頭に記述します。
ネストはタブで表現します。

- リスト1
    - リスト1_1
        - リスト1_1_1
        - リスト1_1_2
    - リスト1_2
- リスト2
- リスト3
リスト1
リスト1_1
リスト1_1_1
リスト1_1_2
リスト1_2
リスト2
リスト3
Ol 番号付きリスト
番号.を先頭に記述します。ネストはタブで表現します。
番号は自動的に採番されるため、すべての行を1.と記述するのがお勧めです。

1. 番号付きリスト1
    1. 番号付きリスト1-1
    1. 番号付きリスト1-2
1. 番号付きリスト2
1. 番号付きリスト3
番号付きリスト1
番号付きリスト1-1
番号付きリスト1-2
番号付きリスト2
番号付きリスト3
Span Elements
Link リンク
[表示文字](URL)でリンクに変換されます。

[Google](https://www.google.co.jp/)
Google

外部参照リンク
URLが長くて読みづらくなる場合や同じリンクを何度も使用する場合は、リンク先への参照を定義できます。

[Googleを見る][Google]
[Google]: http://www.yahoo.co.jp
[Googleを見る][Google] [Google]: http://www.yahoo.co.jp

強調
em
アスタリスク*もしくはアンダースコア_1個で文字列を囲みます。

これは *イタリック* です
これは _イタリック_ です
これは イタリック です これは イタリック です

strong
アスタリスク*もしくはアンダースコア_2個で文字列を囲みます。

これは **ボールド** です
これは __ボールド__ です
これは ボールド です これは ボールド です

em + strong
アスタリスク*もしくはアンダースコア_3個で文字列を囲みます。

これは ***イタリック＆ボールド*** です
これは ___イタリック＆ボールド___ です
これは イタリック＆ボールド です これは イタリック＆ボールド です

Images 画像
先頭の!で画像のと認識されます。画像の大きさなどの指定をする場合はimgタグを使用します。

![alt](画像URL)
![代替文字列](URL "タイトル")

<img src="attach:cat.jpg" alt="attach:cat" title="attach:cat" width="200" height="200">
Table 表
-と|を使ってtableを作成します。

| TH1 | TH2 |
----|---- 
| TD1 | TD3 |
| TD2 | TD4 |
TH1	TH2
TD1	TD3
TD2	TD4
| 左揃え | 中央揃え | 右揃え |
|:---|:---:|---:|
|1 |2 |3 |
|4 |5 |6 |
左揃え	中央揃え	右揃え
1	2	3
4	5	6
