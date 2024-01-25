# 2023年度後期「JavaScript基礎」授業課題

##　授業内コード
1. 10月5日（木）　はじめの一歩
2. 10月5日（木）Github リボジトリ作成
3. 11月2日(木)　富士山の画像を入れました
4. 11月9日（木）　配列を使った要素の追加
5. 12月14日（木）　コールバック関数、アロー関数
6. 1月11日（木）　フォームとオブジェクト
7. 1月25日（木）　json とdate()


## 1月25日（木）

- json(javaScript object Notition)=

const now = new Date();
console.log(now); //Sat Dec 18 2021 21:06:07 GMT+0900 (日本標準時)



## 1月11日（木）

###　フォーム
formは、.valueで値が取れる
valueは文字列なので注意

### オブジェクト
ーやっと出てきたオブジェクトの正体



## 12月14日（木）

### アロー関数

```js
const arrow = () => {
    //関数の処理
};
```

thisは使えない
### スライドショウ２秒後に動く

```js
//２秒で切り替わる
const slideShow = function(func){
    setInterval(func,2000);
};
slideShow(nextStep);
```

- コールバック関数
    - コールバック関数は、関数の引数に関数を当てる使い方
- アロー関数
    - this が使えないので注意
- 関数名(function name)・関数の定義・関数式・関数の実行
    - 関数名しかない場合は、functionと同じ
    - 関数名に（）がついていると関数の実行
    - const 関数名は、関数式
    - returnは、戻り値
- 関数名
    - 関数名（function name）とは、関数に付ける名前。 プログラマが関数を区別、指定できるようにするためにソースコード中で定義する。 言語処理系や標準ライブラリが提供する組み込み関数にもそれぞれ処理内容を表す名前がついている


## 12月7日

### 関数式

```js
const 関数名　= function () {
    処理；
};

//関数の実行
関数名();
```