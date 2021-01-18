# Falix-infra

## 環境構築手順
ローカル環境任意のディレクトリを作成して直下にプロジェクトをクローン  
`mkdir work`->`cd work`  
`git clone git@github.com:Falix-inc/Falix-infra.git`  
(クローンする前に必ずSSHの設定をする事 `https://qiita.com/shizuma/items/2b2f873a0034839e47ce`)  
  
クローンしたら`cd Falix-infra/mysql/`直下で`mkdir data`を実行  
  
`Falix-infra`のディレクトリ直下に戻って`docker-compose up -d --build`を実行すればコンテナが動くはず  
  
`workbench`等ローカルで使う場合は以下を入力してください。  
`Hostname:127.0.0.1`  
`port:23306`  
`Username:root`  
`Password:secret`  


