# ansible用ファイル
nginx + mattermost のセットアップ用

## 実行方法
```
▼必要パッケージのインストール
EL7系統
# yum install pip git -y

EL8系統
# dnf install pip git -y

# pip install ansible

▼本リポジトリをclone
# cd /opt/

# git clone https://github.com/taiki-ether/mm-study.git

▼ansibleを実行
# cd mm-study

MY_DOMAINの調整 (お好きなドメインに)
# vi vars/vars.yml

Basic認証の情報変更 (お好きなユーザ・パスワードに)
# htpasswd files/.htpasswd test

# ansible-playbook install.yml
```

## Basic Auth
適宜書き換えてください
