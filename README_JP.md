# 履歴書
---
## 個人情報
> - 名前 : カン ミング
> - e-mail : 
> - 電話番号 : 
> - 居住地 : 東京
> - 最終学歴 : 
> - 言語 : 韓国語/日本語 ビジネスレメール/会話可能
---

## 経歴
### 有限会社 Colon
> - 在職期間 : 2015.08 ~ 現在
> - 職位 : infra team manager
> - 事業内容 : ウェブ SNS, ゲームプラットフォーム
> - やったこと
>   ```script
>   ウェブサービスに必要なシステム（サーバ、ネットワーク、DBなど）の設計/構築/運用
>   レガシーシステムのアップグレード/交代/再構築
>   作業スケジュール及びコストの管理
>   オープンソース（git, docker, ansible, glusterfsなど）の導入で運用プロセスの変更
>   ```

### 株式会社 ANNEX
> - 在職期間 : 2015.07 ~ 2015.08 （1ヶ月）
> - 職位 : 契約社員
> - 事業内容 : ゲーム、ウェブサービス
> - やったこと
>   ```script
>   Asakusa Gamesでサービスしていたゲームのインフラをオンプレミス環境からAWSに移管と構成/運用方法などの関連情報の引継ぎ
>   ```

### 株式会社 ROC Works / Asakusa Games
> - 在職期間 : 2009.10 ~ 2015.06 （５年９ヶ月）
> - 社名変更 : 2012.08 ROC Works --> Asakusa Games
> - 職位 : infra team manager
> - 事業内容 : ゲームのパブリッシング/モバイルゲームの開発
> - やったこと
>   ```script
>   ゲームのタイトル別 ネットワーク/DB/サーバの購入/構築/運用/管理
>   作業スケジュール/外部の会社/費用の管理
>   ゲームポータルの運用
>   ```

### 株式会社 Digital Daesung
> - 在職期間 : 2007.07 ~ 2009.09 （２年３ヶ月）
> - 職位 : 社員
> - 事業内容 : 小/中/高校と再受験の学院 
> - やったこと
>   ```script
>   Daesung N School/Dasooin/Reading Game/Genex などの学園ブランド別サイト用のサーバをオンプレ環境で構築/運用
>   ネットワーク機器の設定/運用/配線
>   ```
---

## ゲームプロジェクト
### キングダームロード
> - 自社ゲームポータルのgameleonでサービス
> - サーバ構築

### 激戦!三国演義
> - モバゲ、ワクプラ、アプリヒールズ、IOS、アンドロイドプラットフォームでサービス
> - ネットワーク/サーバ/DB 設計/構築/運用

### パイロンカードバトル
> - モバゲ、ワクプラ、アプリヒールズ、IOS、アンドロイドプラットフォームでサービス
> - ネットワーク/サーバ/DB 設計/構築/運用

### talesweaverコレクション
> - モバゲ、ワクプラ、アプリヒールズ、IOS、アンドロイドプラットフォームでサービス
> - ネットワーク/サーバ/DB 設計/構築/運用

### 삼국영웅콜렉션（三國英雄コレクション）
> - 上の「激戦!三国演義」を韓国でサービス
> - KTクラウドでサーバを構築/運用

### 激戦!三国志
> - ワクプラ、アプリヒールズ、IOS、アンドロイドプラットフォームでサービス
> - ネットワーク/サーバ/DB 設計/構築/運用

### クレヨンしんちゃん 空飛ぶ！カスカベ大冒険 
> - Nexon パブリッシング
> - IOS、アンドロイドプラットフォームでサービス
> - ネットワーク/サーバ/DB 設計/構築/運用

### クレヨンしんちゃん　UFO!パニック
> - Nexon パブリッシング
>   - 韓国/日本同時にサービス
> - IOS、アンドロイドプラットフォームでサービス
> - ネットワーク/サーバ/DB 設計/構築/運用

### クレヨンしんちゃん　夢みるカスカベ大合戦
> - Nexon パブリッシング
>   - 韓国/日本同時にサービス
> - IOS、アンドロイドプラットフォームでサービス
> - ネットワーク/サーバ/DB 設計/構築/運用
---

## 保有技術
0. OS
  > - Linux (CentOS/Ubuntu) 
  >   ```script
  >   - サーバ種類(web, db, proxy, ipvs, storage など)別に必要なカーネルのチューニング
  >   ```

1. WEB関連サーバ
  > - Webサーバ 構築/チューニング/運用
  >   ```script
  >   - Apache, Nginx, PHP, Tomcat, Perl, Python 環境
  >   ```

2. DB関連サーバ
  > - Relational DB
  >   ```script
  >   - MySQL/MariaDB semi-sync replication 構築/チューニング/運用
  >   - MariaDB gtid replication 構築/チューニング/運用
  >   - MySQL/MariaDB semi-sync replication master HA構築/運用
  >   -  - DRBD + HearBeat
  >   -  - MHA
  >   - MariaDB Galera Cluster 構築/検証
  >   - MAX-Scale 検証
  >   ```
  > - NoSQL
  >   ```script
  >   - Tokyo Cabinet, Tokyo Tyrant(replication), Redis, InfluxDB, ElasticSearch
  >   - Apache Solr(replication), versionアップグレードの検証
  >   ```
  > - Cache sharding
  >   ```script
  >   - mcrouterを使ってstand aloneだったcacheサーバの構成をsharding + replicaに変更
  >   - mcrouterの冗長化
  >   - ノードの障害復旧、ノードの追加時にcold cache warm upの構成
  >   ```

3. モニタリングサーバ
  > - 内部サーバに設置　設計/構築/運用
  >   ```script
  >   - nagios, mrtg, cacti, grances, zabbix, netdata 
  >   - InfluxDB + Prometheus + Grafana (DashBoard制作)
  >   ```
  > - 外部サービス
  >   ```script
  >   - newrelic, cloudstat などのモニタリングサービスを利用
  >   ```

4. LOGサーバ
  > - GAME LOGを一つのサーバで管理できるようにLOGサーバを構築/運用
  >   ```script
  >   - Logstash, Elastic Search, Kibanaを使ってリアルタイムでLOG分析サーバを構築/運用
  >   ```

5. Storage関連
  > - NFSサーバ
  >   ```script
  >   - セカンドバックアップデータの保存、複数大のサーバで交通に使うソース/scriptの保存目的のNFSサーバを構築/運用
  >   ```
  > - SAMBAサーバ
  >   ```script
  >   - 社内チーム別のデータ保存用のSambaサーバを構築/運用
  >   ```
  > - CIFSサーバ
  >   ```script
  >   - イメージ、動画などのデータを保存してサービスするCIFSサーバを運用
  >   ```

6. Game関連サーバ
  > - Python(Django), Virtualenv 構築/運用 
  >   ```script
  >   - djangoはapacheにwsgi scriptを使って連動(mod_wsgi) 
  >   ```

7. Network関連サーバ
  > - VPNサーバ 
  >   ```script
  >   - openvpnを使って開発会社から社内の開発サーバに接続できるように構築/運用
  >   ```
  > - Loadbalancer 
  >   ```script
  >   - ipvs / HAProxy / ZenLBを使って構築/運用
  >   - DNSLB 
  >     - DNS専用LBのDNSDistを構築/運用
  >   ```
  > - Gatewayサーバ 
  >   ```script
  >   - 社内から外部インターネット通信をする時Gatewayサーバを通じて通信できるように構築/運用
  >   ```
  > - DHCPサーバ
  >   ```script
  >   - 社内にipをぶら下げるDHCPサーバを構築/運用
  >   ```

8. DNS関連
  > - PDNS
  >   ```script
  >   - Publicドメイン管理用のサーバを運用용
  >   ```
  > - TinyDNS (DJDNS)
  >   ```script
  >   - Privateドメイン管理用のサーバを構築/運用
  >   ```
  > - IDCFrontier DNS
  >   ```script
  >   - Public DNSをPDNSからクラウド上のDNSサービスに移管して運用
  >   ```
  
9. Virtualization
  > - ESXi / KVMを使って物理サーバを仮想化して運用
  > - Dockerを導入して社内のツールをコンテナー化して運用
  > - DCOS / Kubernetes導入を比較検証
  >   ```script
  >   - 現在開発チームとマイクロサービス化を協議しながら進行中
  >   ```

10. Cloudサービス
  > - AWS, GCP, Azure, KTCloudでサーバ構築
  >   ```script
  >   - ゲームサーバをオンプレからAWSに移管
  >   - WEBサービス会社の５０台規模のインフラをオンプレからAWSに移管するプロジェックトの相談
  >   - GCPのbig query分析用のシステム構築
  >   - Azureにテレワーク用のトンネリングサーバを構築
  >   ```

11. DevOps Tool
  > - Terraform
  >   ```script
  >   - LAMP環境のウェブサーバをterraformでAWSに構築
  >   ```
  > - Ansible
  >   ```script
  >   - kvm仮想サーバにいつも同じ環境を作れるようにplaybook用のyamlコードを作成
  >   ```
  > - ServerSpec
  >   ```script
  >   - 上で構築したサーバの検証ができるコードを作成
  >   ```
  > - Vagrant
  >   ```script
  >   - ローカルテスト用の環境を構築するコードを作成＆検証して社内に共有
  >   ```
  
12. システム運用に必要なツールの開発
  > - メインはbashを使って必要によってpython, perlなどを使う
  > - Backup
  >   ```script
  >   - 指定したdirectory, fileを圧縮してローカルとNFSに保存して、サーバの基本的情報(process list, df など)を管理者メールに送信する
  >   - パーティションの容量が90%以上やバックアップのエラーが発生した時メールのタイトルに表示
  >   ```
  > - 統計
  >   ```script
  >   - ゲーム内の決済ない域をログから出して日/アイテム/ユーザ別の売上計算をする
  >   - その結果をWebページに出す（PHP）
  >   ```
  > - ソース配布 (最近はansibleを使用)
  >   ```script
  >   - 開発サーバから本番サーバにソースを配布するGUI script
  >   ```
  > - 運用関連
  >   ```script
  >   - Memcached bakcup & restore script
  >   - サーバにHOSTNAMEだけで自動接続できるscrip (ansibleが出る前に管理用に使用)
  >   - KVM仮想サーバの生成する会話式のscript
  >   - 物理/仮想サーバの初期設定をする会話式のscript
  >   - モニタリング用のscript (問題があったらslackにメッセージを飛ばすように)
  >     など運用に必要なscriptを制作可能
  >   ```

13. 作ったもの & Open Source 参加
  > - telegram 管理bot
  >   ```script
  >   - telegramでサーバに簡単なコメンドを投げサーバの状況把握ができるように作ったプログラム
  >   - bot.Telegramから提供してくれるapiをLua scriptでコントロール
  >   - telegram-bot リンク : https://github.com/t2sc0m/telegram_bot
  >   ```
  > - Docker関連
  >   - DB Monitoring 
  >   ```script
  >   - prometheus + grafanaを使ってDBサーバをモニタリングするコンテナーを作成
  >   - Exporter(agent)はperconaで提供したものを使用
  >   - pro-gf リンク : https://hub.docker.com/r/adite/pro-gf/
  >   ```
  > - Docker Cli Dashboard 
  >   ```script
  >   - dcsと言うopen sourceのコードと機能の改善/追加
  >   - DCS リンク : https://github.com/t2sc0m/docker_cli_dashboard
  >   ```
  > - ansibleの導入 
  >   ```script
  >   - 本番サーバのdeploy環境をsvc + redmine --> git + ansibleに変更
  >   ```

14. ETC
  > - 物理やソフトウェアから発生するtrouble shooting可能
  > - Windows Server 2003でDNSサーバ運用
  > - IBM NOTES Groupware 設定/運用
  > - Git Repository(git, gitlab), OwnCloud, Redmine サーバ 構築/運用
  > - Openresty(nginx) + lua scriptでreverse proxy 構築
  >   ```script
  >   - ドメインを変更してバックエンドに伝えるreverse proxyを構築/運用
  >   ```
  > - Apache Solr replication 設定/運用
  > - 物理サーバマネジメントの設定/運用 
  >   ```script
  >   - HP : iLO , DELL : iDRAC
  >   ```
  > - 現在運用中のサービス規模
  >   ```script
  >   - DAU : 25 ~ 27万
  >   - MAU : 60 ~ 65万
  >   - 外部トラフィック : 650 ~ 700 Mbps
  >   - サーバ : 300台以上
  >   ```
  > - GlusterFSの検証/導入/構築/運用
  >   ```script
  >   - 紹介資料作成して社内に発表
  >   - テストと本番用の環境設計/構築
  >   - 検証して本番に適用/運用
  >   ```

15. ネットワーク機器関連
  > - Cisco L2SW, Firewall, VPN, WiFi運用
  > - HP, Dell L2SW 設定/運用
  >   ```script
  >   - LACP, Stack 設定
  >   ```
  > - Yamaha VPN 設定/運用
  > - Barracuda spam filtering solution運用
  > - BIG-IP 設定/運用
  > - Arbor IDSシステム設定/運用
  > - Fortigate firewall 設定/運用
  > - A10 thunder LB 検証
  
---

## 資格書
> - JLPT N2 (日本語能力試験)
> - 情報処理産業技師
>   - 組織名 : 韓国産業人力管理公団
>   - 取得日 : 2000.07.31
> - SCSA (Sun Certified System Administrator)
>   - 組織名: Sun Microsystems
>   - 取得日 : 2006.12.30
> - OCP-DBA (Oracle Certified Professional-DBA)
>   - 組織名 : Oracle
>   - 取得日 : 2007.03.05
> - JLPT N2 （日本語能力試験）
>   - 組織名 : JEES
>   - 取得日 : 2012.01.27
---

