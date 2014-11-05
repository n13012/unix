# Vagrant
============
### Vagrantとは？
仮想マシンの作成や環境構築、仮想マシンの破棄までを自動化するツール
### こういう時に便利
すぐに使える仮想環境を構築したい  
ちょっとしたテストのために壊してもいい環境が欲しい  
チームで同一の環境を簡単に構築したい

------

### 1.インストール手順
Vagrantをインストール  
http://downloads.vagrantup.com/からv1.3.5を取得  
sudo dpkg -i vagrant_1.3.5_x86_64.deb  
vagrant -v でバージョン確認
#### 2.Boxファイル追加

#### 3.Vagrantfile生成
vagrant init なんとか
ls
Vagrantfile
#### 4.仮想マシンを起動
vagrant up
