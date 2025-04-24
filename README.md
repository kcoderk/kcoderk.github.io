 <center>
     <h1>黄锴康个人简历</h1>
     <div>
         <span>
             <img src="assets/phone-solid.svg" width="18px">
             13261163826
         </span>
         ·
         <span>
             <img src="assets/envelope-solid.svg" width="18px">
             huangkaikang@gmail.com
         </span>
     </div>
 </center>

 ## <img src="assets/info-circle-solid.svg" width="30px"> 个人信息 

 - 男，1996 年出生
 - 求职意向：工程师
 - 工作经验：6 年

## <img src="assets/graduation-cap-solid.svg" width="30px"> 教育经历

- 学士，中国石油大学，电子商务专业，2014.9~2018.7
- 学士，中国石油大学，计算机双学位，2014.9~2018.7


## <img src="assets/briefcase-solid.svg" width="30px"> 工作经历

- **博彦科技（杭州）有限公司，高级技术支持工程师，2024.09~至今**
  
  负责阿里云国际站客户技术支持，帮助客户解决技术疑难问题，提供客户关于云服务相关问题解决方案。

- **浪桥科技（杭州）有限公司（Splashtop Inc），杭州研发中心，Engineering Manager，2021.11~2024.2**
  
  负责零信任网络安全（ZTNA）相关产品矩阵从0到1核心功能设计与研发工作，主导系统稳定性维护方案设计与实施。主导团队新成员招募与技术管理，跨部门沟通协作，项目风险管控，人员部署与任务分配。

- **华为杭州研究所，2012实验室，研发工程师，2020.11~2021.10**
  
    负责实验室自动化环境SRE相关工作

- **北京快快网络有限公司，国际化创新科技部门，研发工程师，2017.11~2020.10**

    负责公司国际金融业务 app 后台系统以及风控系统研发工作，独立负责后台业务系统从开发与维护工作。
    
    负责国际化金融产品海外支付渠道，短信服务系统，开发工作。

- **北京快快网络有限公司，国际化创新科技部门，项目经理，2019.11~2020.10**
    国际化金融项目，负责项目进度管理，跨部门协调，高效推进相关产品需求，业务风险控制。

## <img src="assets/project-diagram-solid.svg" width="30px"> 项目经历


- **零信任网络(ZTNA)项目**

    零信任主要我们做了两个产品，一个是Splash Vault 一个是SDP，其中Spalshtop Vault主要使用密码学的技术，比如对称加密和非对称加密已经签名，我们结合这些技术实现了将用户的密码加密成密文保存到云端，而Master Code在用户本机，如此一来规避了中间人攻击，使得云端存储到数据除了用户本人之外其他人都无法解密。
    SDP 即 Software Defined Perimeter，传统VPN需要打通公司网络和个人主机进行公司内网访问，我们结合零信任模型，做到更细粒度的隔离，实现单点应用打通加密Tunnel进行访问，实现多子网之间更安全更快速的访问，在各业务节点还会进行权限的管制，实现更灵活的访问控制。

    其中使用的技术栈：Golang,PostgreSQL,Docker,K8s,ZeroTrustNetwork,TCP/UDP,HTTP/HTTPS

    相关技术点设计与攻克：端到端对称与非对称加密，boundary,controler，control plane，connector service，网络session管理，network sharing，远程控制协议RDP，VNC，SSH等，
    客户端与服务端打通，客户端与服务端网络网络通信架构方案设计，网络稳定性方案设计与实施。

    
- **国内信贷风控系统**
  
    主要负责系统维护工作。接入 Apollo 配置系统，使项目实现配置化管理，系统安全性和可维护性大大提升。优化风控数据源接入逻辑，解决系统bug。

    负责测试机自动同步环境部署以及自动化部署 Bash 脚本的开发，使用 rsync+fswatch 实现同步本地代码至服务器并解决新版本 MacOS 版本兼容问题。

    其中使用的技术栈：PHP,Mysql,Docker,K8s,HTTP/HTTPS,BASH,Nginx

- **国际化后端微服务化**
  
    负责国际化金融业务App 后端微服务的设计开发，
    
    1.独立负责国际化短信微服务模块与支付微服务从开发到上线整个流程；使用 MQ 实现短信异步发送，提升短信服务性能与可用性；重新设计数据库及服务架构，使短信模块能过够适应多条业务线使用;设计与优化支付系统，与前端对接当地银行卡及各类支付渠道，提升用户支付体验。
    
    2.负责业务监控系统的搭建与exporter开发，从数据，日志，接口，中间件等多维度实施监控，保障业务平稳运行，有问题能够及时发现并发送报警，持续优化实现了较低的误报率；技术实现为前端使用 grafana，后端多台 Prometheus 作为主节点，多台 Prometheus 为不同业务线提供监控服务将数据汇总到主节点，Prometheus从 exporter 拉取业务数据，实现监控。使用 Supervisor 管理服务进程。

    其中使用的技术栈：PHP,Mysql,Docker,K8s,HTTP/HTTPS,BASH,Prometheus,Nginx
    
- **金融数据爬虫项目**

    负责金融风控爬虫系统开发，
    抓取电商类、企业类网站数据，熟悉爬虫相关技术，熟悉网页及 api 数据解析，清洗，入库，
    ​去重过程，在攻克某网站的验证码过程中，使用了 KNN，SVM 等算法，搭建神经网络模型，训练模型识别图片验证码，成功率高达 98%。

    其中使用的技术栈：Python,Mysql,Docker,HTTP/HTTPS,BASH,Machine Learning


## <img src="assets/tools-solid.svg" width="30px"> 技能清单

- Java、Golang、Python、PHP
- MySQL、PostgreSQL
- Redis
- Gin、Flask、Django、
- Docker、K8s
- Experts in software and hardware installation and maintenance
- Fluent communication skills in Chinese and English
- AWS 解决方案架构师专业级认证(AWS Certified Solutions Architect - Professional)

