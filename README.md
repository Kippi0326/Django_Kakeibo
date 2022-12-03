# Djangoで家計簿作成
 
 Djangoで作成する家計簿をチーム開発で実装しましょう！
 
## メニュー
* [インストール方法](#インストール方法)
* [プロジェクト作成方法](#プロジェクト作成方法)

[return to menu](#メニュー)
 
# デモ

大枠が完成したらでも画像等を貼り付ける
 
# 家計簿システムについて
 
完成したら家計簿システムの強みを記載する
 
# 要件
 
家計簿アプリ開発に参画するために必要なライブラリを記載

↓例
* huga 3.5.2
* hogehuga 1.0.2
 
# インストール方法
 > 手順1：作業用ディレクトリ作成
 
 まずは、作業用ディレクトリとして、「DjangoWork」(※ディレクトリ名は任意)を作成。
作業用ディレクトリを作成する場所は、任意で OK 。
```bash
# 作業用ディレクトリの作成
mkdir DjangoWork
 
# 作業用ディレクトリへ移動
cd DjangoWork
```
<br>

> 手順2：仮想環境の作成とDjangoのインストール

続いて、仮想環境を作成し、Django のパッケージを pip 経由でインストール。
```bash
# 仮想環境の作成（仮想環境作成に必要なプログラムは.djangoenvディレクトリに格納）
python3 -m venv .djangoenv

# 仮想環境の起動
source .djangoenv/bin/activate

# Djangoのインストール
pip install django
```
<br>

> 手順3：Django パッケージの情報を確認

インストールした Django パッケージの情報を以下のようなコマンドで確認。
```bash
pip show Django
```


# プロジェクト作成方法
 > 手順1：プロジェクトディレクトリ作成
 ```bash
 # プロジェクト用ディレクトリの作成
mkdir mydiaryproject

# プロジェクト用ディレクトリへ移動
cd mydiaryproject
```

 > 手順2：GitHubからクローン
 
作業用ディレクトリ(Django_Kakeibo_project)(※プロジェクト名は任意)の配下にDjango_KakeiboリポジトリをGitHubからクローン

1.仮想開発サーバーを立てる
```bash
 # 仮想開発サーバーを立てる
python manage.py runserver
```

2.実行結果を確認
http://127.0.0.1:8000/index/


# 仮想環境の起動

source .djangoenv/bin/activate

# Django（ver. 3.1.2）のインストール
pip install django==3.1.2
```
 
# 使用方法
 
DEMOの実行方法など、基本的な使い方を説明する
 
  ↓例
```bash
git clone https://github.com/hoge/~
cd examples
python demo.py
```
 
# メモ
 
注意点などがあれば書く
 
# 開発メンバー
 
作成情報を列挙する
 
* メンバー１　
* メンバー２　さんした侍
 
# ライセンス
ライセンスを明示する
 
