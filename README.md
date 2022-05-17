# django-sample
## 目的
PythonのWebフレームワークであるDjangoをお手軽に触れるように、  
最低限の環境をGitHub上にアップします。  
今後、カリキュラムを作るかも。。。  

## 参照サイト
https://docs.docker.jp/compose/django.html  
https://qiita.com/nokonoko_1203/items/242367a83c313a5e46bf  
https://qiita.com/tegnike/items/bcdcee0320e11a928d46  
https://qiita.com/nokonoko_1203/items/242367a83c313a5e46bf  

## 構築手順
docker-compose build --no-cache  
docker-compose up --build -d

この手順で127.0.0.1にてdjangoのスタート画面が表示されます。
以降は各プロジェクト、アプリケーションの作成を行ってください。
プロジェクト作成: django-admin startproject [project名]
アプリケーション作成: python manage.py startapp [app名]

