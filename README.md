# 이력서
---
## 개인 정보
> - 이   름 : 강 민구
> - 전자메일 : tescom9@naver.com
> - 전화번호 : +81 80-4372-8087
> - 현거주지 : 도쿄
> - 최종학력 : 가톨릭대학교 컴퓨터공학 학사
---

## 경력
### 유한회사 콜론
> - 재직기간 : 2015.08 ~ 현재
> - 직   위 : 인프라팀장
> - 한 일
> - ```script
웹 서비스에 필요한 시스템 설계/구축/운용
레거시 시스템의 교체/업그레이드
작업 스케줄/비용 관리
오픈소스 도입으로 운용 프로세스 변경
```

### 주식회사 ANNEX
- 재직기간 : 2015.07 ~ 2015.08 (1개월)
- 직   위 : 계약사원
- 한 일
```script
Asakusa Games에서 서비스하던 게임의 인프라를 온프레미스 환경에서 AWS로 이전하고 구성/운영방법 등의 관련정보 인수인계
```

### 주식회사 ROC Works / Asakusa Games
- 재직기간 : 2009.10 ~ 2015.06 (5년 9개월)
- 직   위 : 인프라팀장
- 한 일
```script
게임 타이틀별 네트웍/디비/서버 구입/설계/구축/운용/관리
작업 스케줄/외부업체/비용 관리
```

### 주식회사 디지털 대성
- 재직기간 : 2007.07 ~ 2009.09 (2년 3개월)
- 직   위 : 사원
- 한 일
```script
대성N스쿨(직영/분원)/다수인/리딩게임/제넥스 등의 사이트 구축/운용
```
---

## 보유 역량
0. OS
  > Linux (CentOS/Ubuntu) 
1. WEB관련 서버
  > Apache, Nginx, Mysql/MariaDB, Memcached, PHP, Tomcat, Perl, Python 환경의 web관련 서버 구축/튜닝/운용
2. MONITORING서버
  > nagios, mrtg, cacti, grances, prometheus, zabbix, netdata 등을 사용하여 모니터링 서버를 구축/운용
  > datadog, newerlic, cloudstat 등의 모니터링 서비스 이용
3. LOG서버
  > GAME LOG를 하나의 서버로 관리할 수 있도록 LOG서버를 구축/운용
  >> Logstash, Elastic Search, Kibana를 사용해 실시간 Log 분석 서버를 구축/운용
4. NFS서버
  > 세컨드백업데이터의 보존, 복수대의 서버에서 공통으로 사용되는 소스/스크립트의 보관목적의 NFS서버 구축/운용
5. SAMBA서버
　> 사내팀별 데이터 저장용 Samba 서버 구축/운용
6. DB관련 서버
  - Relational DB
    > MySQL/MariaDB semi-sync replication 구축/튜닝/운용
    > MariaDB gtid replication 구축/튜닝/운용
    > MySQL/MariaDB semi-sync replication master HA구축/운용
    >> DRBD + HearBeat
    >> MHA
    > MariaDB Galera Cluster
NoSQL 
Tokyo Cabinet, Tokyo Tyrant(replication), Redis, InfluxDB, ElasticSearch
7. Game관련 서버
Python(Django), Virtualenv 구축/운용(django는 apache에 wsgi script를 사용해 연동(mod_wsgi))
8. Network 관련 서버
VPN 서버 openvpn을 사용해 개발사가 사내의 개발서버에 접속할 수 있도록 구축/운용
Loadbalancer:ipvs/haproxy/ZenLB를 사용하고 높은 L4를 사용하지 않고 로드 바란 구축/운용
Gateway 서버 사내에서 외부넷을 사용할 때 Gateway 서버를 통해 외부와 통신할 수 있도록 구축/운용
DHCP 서버 사내 ip 할당용 DHCP 서버 구축/운용
9. Virtualization
Esxi/KVM으로 물리서버를 가상화하여 운용
Docker도입하여 사내 툴을 docker화하여 운용
10. Shell Script
기본bash에서 필요에 따라 python, perl 등을 사용
-백업
지정된 디렉토리, 파일을 압축해 로컬과 NFS에 보존하고, 서버의 기본적인 정보(process list, df 등)를 관리자 메일로 송신하는 셸 스크립트. 
(파티션 용량이 90%이상이거나 백업 에러 발생시에 메일 제목에 표시)
-통계
게임내의 결제의 일부를 로그로부터 뽑아내 일/아이템/유저마다의 매상 계산의 쉘 스크립트.
소스배포 (최근에는 ansible으로 변경)
GUI에서 개발 서버로 실전 서버에 소스를 배포하는 셸 스크립트.
운용관련
Apache의 자동 재기동 셸 스크립트.
서버에 HOSTNAME로 자동적으로 접속되는 셸 스크립트.
KVM서버생성 스크립트
서버 초기설정 스크립트
모니터링용 스크립트(문제가 있으면 slack에게 메세지 보내도록)
등의 운용에 필요한 셸스크립트 제작 가능.

11. 만든 것 & Open Source 참가
telegram 관리bot:telegram이라는 messenger에서 서버에 간단한 명령어를 던져 서버 상황을 확인할 수 있도록 bot.Telegram에서 제공하는api를 Lua script에서 컨트롤
링크:https://github.com/t2sc0m/telegram_bot
-Docker관련
DB Monitoring : prometheus + grafana에서 DB서버를 모니터링 할 수 있는 콘테이너를 작성.Exporter(agent)는 percona에서 제공한 것을 사용.
링크:https://hub.docker.com/r/adite/pro-gf/
Docker Cli Dashboard open source contributer 
dcs라는open source의 코드와 기능의 개선&추가
링크:https://github.com/t2sc0m/docker_cli_dashboard
InfluxDB + Prometheus + Grafana 로 모니터링 시스템 구축
ansible : 본번 deploy 환경을 git + ansible로 변경
11)ETC
Linux, Windows 2003 DNS서버 운용
Git Repository(git, gitlab), OwnCloud, Redmine 서버 구축/운용
Openresty(nginx)+lua script로 도메인을 변경하여 전달하는 reverse proxy 구축/운용
---

## 보유 자격증
- 정보처리산업기사
  - 기관명 : 한국산업인력관리공단
  - 취득일 : 2000.07.31
- SCSA (Sun Certified System Administrator)
  - 기관명 : Sun Microsystems
  - 취득일 : 2006.12.30
- OCP-DBA (Oracle Certified Professional-DBA)
  - 기관명 : Oracle
  - 취득일 : 2007.03.05
- JLPT N2 (일본어능력시험)
  - 기관명 : JEES
  - 취득일 : 2012.01.27
---

## 개인 프로젝트
- 홈페이지 : [http://www.atdt01410.com/](http://www.atdt01410.com/)
- 텔넷 서비스 : 러시아/중국의 끝없는 해킹 시도로 현재 서비스 중단
  - 사설BBS : 2007 ~ 2018
  - 머드게임 : 2007 ~ 2015
- 미소일기 : 온라인에서 만난 사람들과 함께 재미로 SNS서비스를 만들어봄
  - 비용 문제로 현재 서비스 종료 후 백업사이트 운영 중
  - 서비스 기간 : 2014.04 ~ 2019.05
  - [미소일기 위키](https://namu.wiki/w/%EB%AF%B8%EC%86%8C%EC%9D%BC%EA%B8%B0)
  - [미소일기 대피소](http://www.misodiary.net/)
- [깃허브](https://github.com/t2sc0m)
- [링크드인](https://www.linkedin.com/in/tescom/)
