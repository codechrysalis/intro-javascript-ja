# `function`s 入門

## ねらい

1. `function` とはなにか、なぜそれを使う必要があるかを知る
2. `function` を作る
3. `function` を呼び出す
4. `return` ステートメントと `console.log` とのちがいを知る

## 講義スライド

* [Functions 講義入門](https://docs.google.com/presentation/d/e/2PACX-1vSZNBSMIbREHO5NW_GTpbSIOucnS_Zq29EK7AOTyRymqp6YPq1reV_7S-gUqK5Nmd5k3XA54_17-Fbb/pub?start=false&loop=false&delayms=3000)

## Exercises

### 簡素な開発環境を作ってみよう

[スライドはこちら -->](https://docs.google.com/presentation/d/e/2PACX-1vSqptF2VmwR1R1Xx54emSqbp6TXyrewLPySmMt4Qo8x2q6LQMXZe_t0_5QIDTlSxo2S25RLi9GwzoA1/pub?start=false&loop=false&delayms=3000)

1. [このzipファイルをダウンロードしてください。](https://cdn.rawgit.com/codechrysalis/intro-javascript/2979d760/your-template.zip) それから以下に進んでください。
2. zipを解凍してください。
3. あなたの隣の人と一緒に、Visual Studio Code上での`your-template`フォルダーの開き方が正しいか、確認してみましょう。
4. Visual Studio Code上でzipファイルの中身を開けたら、その中身を見てみてください。何がありますか？
5. 以下のexercisesでは、拡張子が `.js` のファイルで作業することになります。

### 基礎編

// <-- バックスラッシュ2本はコメントになります。コメントはJavaScriptのエンジン（コードを読み、動作させるプログラム）が無視します。

```js
// この行はコメントでコードではありません。
// この行もまたコメントです。
```

バックスラッシュとアスタリスクを使うと、複数行をコメントにできます。

```js
/* これは一行以上のコメントです。
これは二行目です。 */
```

1. 今ダイレクトにコンソールではなく、ファイルにJavaScriptのコードを書いているので、コンソールに値を表示させるためには `console.log` を使う必要があります。**script.js** ファイルに以下の2行を追加してください。そして **index.html** をブラウザで開き、ディベロッパーツールを開いてみてください。ディベロッパーコンソールに何が見えますか？

    ```js
    5 + 6;
    console.log(6 + 6);
    ```

    なぜこのように動作するのでしょうか？

2. 以下の `function` を使って、2つの `number`s の合計を求めてみましょう。**script.js** に以下のコードを入力してみてください。:

    ```js
    function add(numOne, numTwo) {
      return numOne + numTwo;
    }

    // テスト
    console.log(add(4, 3)); // 7 が表示されるようにしましょう。
    console.log(add(100, 42)); // 142 が表示されるようにしましょう。
    ```

    **ヒント**: **script.js** の中で定義された `function`s はコンソールで使用できます。ディベロッパーコンソールに直接2つのテストを入力してみましょう。**script.js**にテストを入れ続けてください。デバッグに役に立ちます。

3. _subtract_ というファンクションを宣言しましょう。このファンクションは最初の引数の数字から、二番目の引数の数字を引き算するファンクションです。ファンクションが正しく動作するかどうかテストケースを試してみましょう。

    ```js
    function subtract(num1, num2) {
      // your code here
    }
    ```

    テストケース:

    ```js
    console.log(subtract(4, 3)); // => 1
    console.log(subtract(100, 42)); // => 58
    ```

4. _greeting_ というファンクションを宣言しましょう。このファンクションは `string` 型の `name` という引数を取って、挨拶文を表示させるものにします。

    ```js
    // Your code here
    ```

    テストケース:

    ```js
    console.log(greeting("Alex")); // => "Hello, Alex!"
    console.log(greeting("Beau")); // => "Hello, Beau!"
    ```

5. _average_ というファンクションを宣言しましょう。このファンクションは2つの`number`s をインプットとし、それらの平均を `number` として返します。今回は自分でテストケースを2つ作ってみましょう！

### 応用編

1. [図形問題の公式集](http://www.gbcnv.edu/documents/ASC/docs/00000005.pdf) をチェックしてみてください。それぞれの公式を `function`s で作ってみましょう。
