# fixpoint_programming_exam

## 環境

- Python 3.8.3

### 動作確認

||PC 1|
|---|---|
|OS|Windows 10 Home|
|CPU|Intel Core i5-7200 2.50GHz|
|メモリ|8.00GB DDR4|


## 設問1_解答の流れ

1. ログデータの読み込み
2. タイムアウトしているサーバのアドレスを取得
3. 2で取得したアドレスのサーバを走査
4. タイムアウトから応答までのインデックスを各サーバで取得
5. インデックスから日付を取得
6. 故障期間の出力

## 設問2_解答の流れ
1. ログデータの読み込み
2. タイムアウトしているサーバのアドレスを取得
3. 2で取得したアドレスのサーバを走査
4. 連続でタイムアウトした回数をカウント
5. 指定したNを超えた場合、「故障とみなす」

## ディレクトリ構造

### script

- 要求に対する解答のプログラム

### security_log

- ログデータ
