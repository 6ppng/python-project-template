## 概要

このリポジトリはPythonプロジェクトのテンプレートである。  
  
プロジェクトを問わず必要なライブラリを予め準備する。  
加えて、VSCodeでの使用を前提とした諸設定も予め行う。

## 導入されるライブラリ

以下に挙げるライブラリを準備する。

* `pysen`
    * 以下に示すフォーマッタ・リンタライブラリをラップし、一括で設定するライブラリ。
        * フォーマッタ
            * `balack`
            * `isort`
        * リンター
            * `flake8`
            * `mypy`

* `flake8-cognitive-complexity`
    * `flake8`用プラグインライブラリ。
    * 認知的複雑度に制約を設ける。
* `flake8-annotations`
    * `flake8`用プラグインライブラリ。
    * 型アノテーションの記述を強要する。
* `flake8-docstrings`
    * `flake8`用プラグインライブラリ。
    * Docstringの記述を強要する。

## 環境構築方法
### poetry環境の構築方法

anyevnを用いたpoetryの導入方法を示す。

1. TODO

### 本リポジトリをもとにしたPythonプロジェクトの作成方法

本リポジトリをクローンし、任意のPythonプロジェクトを開始する際の手順を示す。

1. TODO
