# コメントではその内容の前後へ空白文字を置く

いくつかの文字はコメントの開始直後や終了直前に書けません。

悪い例:

    <!--This section is non-normative-->

良い例:

    <!-- This section is non-normative -->

コメントは比較的自由に書けます。数少ない制限のひとつとして、コメント内の最初と最後に使えない文字（列）があります。具体的には以下の3つです。

1. &gt;で開始
2. ->で開始
3. -で終了

コメントは、自身で能動的に書く以外にも、様々な形で自動的に挿入されます。そういった場合も含めて、これらの制限を確実に避けるためには、良い例で挙げたようにコメントの最初と最後に*半角空白*を入れるのが良いでしょう。理論上は半角空白以外の何かしらの文字でも問題ありませんが、読みやすさや入力のしやすさを考慮すると半角空白が適当です。
