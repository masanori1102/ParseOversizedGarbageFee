# 1. はじめに

このプロジェクトは、Python 3.xの最新版で動作する。


## 1-2. パッケージを更新する

パッケージの更新は、実行前に都度おこなう

### 1-2-1. Windows

<pre>
> py -m pip install --upgrade pip --user
</pre>

### 1-2-2. Linux

<pre>
$ python3 -m ensurepip --upgrade --user
$ pip3 install --upgrade pip --user
</pre>

### 1-2-3. macOSX

1-2-2. Linux参照

# 2. Pythonファイルを実行する

## 2-1. 実行手順

### 2-1-1. Windows

<pre>
> cd src¥main
> pip3 install -r ..¥..¥requirements.txt --user
>
> py -3 parse_oversized_garbage_fee.py {設定ファイルのパス}
</pre>

例.
<pre>
> py -3 parse_oversized_garbage_fee.py ../../data/Tokyo/Setagaya/settings
</pre>

### 2-1-2. Linux

<pre>
$ cd src/main
$ pip3 install -r ../../requirements.txt --user
$
$ python3 parse_oversized_garbage_fee.py {設定ファイルのパス}
</pre>

例.
<pre>
$ python3 parse_oversized_garbage_fee.py ../../data/Tokyo/Setagaya/settings
</pre>

### 2-1-3. macOSX

2-2. Linux参照

## 2-2. 結果を確認する

結果は、`{設定ファイルのパス}/output`に出力される
