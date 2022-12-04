# Djangoで家計簿作成
 
 Djangoで作成する家計簿をチーム開発で実装しましょう！
 
## メニュー
* [デモ](#デモ)
* [家計簿システムについて](#家計簿システムについて)
* [要件](#要件)
* [インストール方法](#インストール方法)
* [プロジェクト作成方法](#プロジェクト作成方法)
* [メモ](#メモ)
* [開発メンバー](#開発メンバー)
* [ライセンス](#ライセンス)

 
# デモ

大枠が完成したらでも画像等を貼り付ける
 
# 家計簿システムについて
 
完成したら家計簿システムの強みを記載する
 
# 要件
 
家計簿アプリ開発に参画するために必要なライブラリを記載

 asgiref==3.5.2
<br>
 defusedxml==0.7.1
<br>
 diff-match-patch==20200713
<br>
 Django==4.1.3
<br>
 django-import-export==3.0.1
<br>
 django-pandas==0.6.6
<br>
 et-xmlfile==1.1.0
<br>
 MarkupPy==1.14
<br>
 numpy==1.23.5
<br>
 odfpy==1.4.1
<br>
 openpyxl==3.0.10
<br>
 pandas==1.5.2
<br>
 plotly==5.11.0
<br>
 python-dateutil==2.8.2
<br>
 pytz==2022.6
<br>
 PyYAML==6.0
<br>
 six==1.16.0
<br>
 sqlparse==0.4.3
<br>
 tablib==3.2.1
<br>
 tenacity==8.1.0
<br>
 tzdata==2022.6
<br>
 xlrd==2.0.1
<br>
 xlwt==1.3.0
 
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

> 手順2：仮想環境の作成

続いて、仮想環境を作成し、Django のパッケージを pip 経由でインストール。
```bash
# 仮想環境の作成（仮想環境作成に必要なプログラムは.djangoenvディレクトリに格納）
python3 -m venv .djangoenv

# 仮想環境の起動
source .djangoenv/bin/activate
```
<br>

> 手順3：requirements.txtの作成

続いてpipでのインストールに用いるrequirements.txtファイルを作成する。
.txtファイルを用いたpipのインストールはチームで共有することで必要なPythonパッケージを一括で入れることができるので非常に便利
まず任意のフォルダにrequirements.txtを作成して、中身を以下のようにする。

(requirements.txt)
<br>
django
<br>
django-pandas
<br>
pandas
<br>
plotly
<br>
django-import-export

<br>

> 手順4：requirements.txtのインストール

仮想環境内の以下の階層にインストール
djangoenv\scripts\activate
```bash
pip install -r requirements.txt
```
<br>

> 手順5：インストールされているパッケージを確認

インストールが完了したらpip freezeコマンドでインストールされているパッケージを確認(pip listコマンドも使える)。
```bash
pip freeze
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
http://127.0.0.1:8000/
 
# メモ
 
注意点などがあれば書く
 
# 開発メンバー
 
作成情報を列挙する
 
* メンバー１　
* メンバー２　さんした侍
 
# ライセンス
ライセンスを明示する

[return to menu](#メニュー)
 
