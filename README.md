# 404 StarLink Project 2.0 - Galaxy

---

![](./logo.png) 

The 404 Starlink Project was started by Knownsec 404Team in 2020. We aim to denfend network and promote the  Instrumentalizing  of security research in different fields through open source or open methods. Just like Starlink, this project will link researchers with different security background.

Not only large tools which break security barriers，various small tools that optimizing the daily experience are included. We will open all tools developed by 404 Team, and continue to collect pain points in the process of security research and penetration testing.  The security field used to have various problems, like   tools jumbled, different levels obvious, and open source be unmaintained. Through the 404 Starlink Project, we wish security field would become a better place where people like to communicate and progress together.

[“404星链计划”](https://github.com/knownsec/404StarLink-Project) 是知道创宇404实验室于2020年8月开始的计划，旨在通过开源或者开放的方式，**长期维护**并推进涉及安全研究各个领域不同环节的工具化，就像星链一样，将立足于不同安全领域、不同安全环节的研究人员链接起来。

[“404星链计划”](https://github.com/knownsec/404StarLink-Project) 主要目的是改善安全圈内工具庞杂、水平层次不齐、开源无人维护的多种问题，营造一个更好更开放的安全工具促进与交流的技术氛围。

2020年11月，知道创宇404实验室正式推出星链计划2.0。通过星链计划核心社群成员作为核心，筛选**优质、有意义、有趣、坚持维护**的开源项目加入星链计划2.0，由404实验室核心成员及星链计划核心成员作为背书，将优质的开源项目汇聚成星河，为立足于不同安全领域的安全研究人员指明方向。代号**Galaxy**。

同时，真正优质的开源项目将会优先推荐KCON 2021兵器谱，在KCON 2021上获得专属的曝光机会。404实验室也会为优秀的个人开源维护者提供知道创宇的优先内推绿色通道，星链计划的核心成员群也会不定期送出礼品。

星链计划2.0会将开源项目按照两个核心项作为主要指标：
- 成熟、有意义的开源项目       Open-Projects
- 有新意、解决痛点的开源项目   Fun-tools

入选星链计划2.0的项目至少需要满足以下四个要求：
- 安全相关的各个环节以及链路
- 开源
- 坚持维护
- 通过由404实验室以及星链计划核心成员组成的审阅组审阅

入选项目将由代码质量、技术难度、新颖度等多个维度评价打分(满分5星) ，是否坚持维护将作为最重要的评价标准。入选Open-Projects的项目不得超过1年未更新，且超过6个月未更新的项目只能获得上限为4星的评价。入选Fun-Tools分类的开源项目由星链计划2.0核心社群成员判定当前的维护状态，被判定为未维护的项目将会被从星链计划中去除。

参与星链计划2.0的开源项目可以借由星链计划社群与开发者直接沟通，真正将研究人员和开发人员连在一起。

希望星链计划2.0能像北斗七星一样，引领安全研究人员前进的方向。


# Rules

- Positivity: 积极度，工具正处于积极维护期的项目将被标记为In，正出于弱维护期的项目将被标记为TBD，已经不再维护的的项目将被标记为OUT.

- Score: Open-Projects的评分上限为5星，Fun-tools的评分上限为4星.

# Update

这里会更新最近涉及更新的项目

- 2021.3.23 [**星链计划2.0-Galaxy**](https://github.com/knownsec/404StarLink2.0-Galaxy)

  ​	星链计划2.0-Galaxy 收录[**linglong**](https://github.com/knownsec/404StarLink2.0-Galaxy/blob/master/TOOLS_README.md#linglong-)、[**Viper**](https://github.com/knownsec/404StarLink2.0-Galaxy/blob/master/TOOLS_README.md#viper-)、[**CodeReviewTools**](https://github.com/knownsec/404StarLink2.0-Galaxy/blob/master/TOOLS_README.md#codereviewtools-)。

- 2021.3.23 [**Zoomeye-python**](https://github.com/knownsec/ZoomEye-python)

  ​	Zoomeye-python更新v2.0.4.1.


# Contents

## 甲方工具向
- Threat identification 威胁识别
    - 在攻击发生之前识别，如流量分析等 
- Mitigation measures 缓解措施
    - 在攻击发生之中缓解威胁，如hids，waf等
    - [Juggler](https://github.com/knownsec/404StarLink2.0-Galaxy/blob/master/TOOLS_README.md#juggler) 
        - ![](https://img.shields.io/badge/Positivity-TBD-yellow) ![](https://img.shields.io/badge/Score-%E2%98%85%E2%98%85%E2%98%85%e2%98%86-yellow) ![](https://img.shields.io/badge/Author-C4o-orange) ![](https://img.shields.io/badge/Language-Go-blue) 
        - 一个也许能骗到黑客的系统。可以作为WAF等防护体系的一环。
- Security inspection 安全检测
    - 对目标的安全检测，主要集中在对不同链路的主动安全检测
    - [linglong](https://github.com/knownsec/404StarLink2.0-Galaxy/blob/master/TOOLS_README.md#linglong-) ![](https://img.shields.io/badge/-New-red)
      - ![](https://img.shields.io/badge/Positivity-IN-green) ![](https://img.shields.io/badge/Score-%E2%98%85%E2%98%85%E2%98%85%e2%98%86-yellow) ![](https://img.shields.io/badge/Author-awake1t-orange) ![](https://img.shields.io/badge/Language-Go-blue)
      - linglong是一款甲方资产巡航扫描系统。系统定位是发现资产，进行端口爆破。帮助企业更快发现弱口令问题。主要功能包括: 资产探测、端口爆破、定时任务、管理后台识别、报表展示。
- Security Monitor 安全监控
    - 对某个安全链路的安全监控、管理平台
    - [gshark](https://github.com/knownsec/404StarLink2.0-Galaxy/blob/master/TOOLS_README.md#gshark-)
    	- ![](https://img.shields.io/badge/Positivity-IN-green) ![](https://img.shields.io/badge/Score-%E2%98%85%E2%98%85%E2%98%85%E2%98%85-green) ![](https://img.shields.io/badge/Author-madneal-orange) ![](https://img.shields.io/badge/Language-Go-blue) 
    	- 一款开源敏感信息监测系统，支持github、gitlab、searchcode

## 乙方工具向
- Reconnaissance 信息收集

    - 在渗透测试前置准备工作过程种涉及到的各类信息收集
    - [zsdevX/DarkEye](https://github.com/knownsec/404StarLink2.0-Galaxy/blob/master/TOOLS_README.md#zsdevxdarkeye) 
        - ![](https://img.shields.io/badge/Positivity-IN-green) ![](https://img.shields.io/badge/Score-%E2%98%85%E2%98%85%E2%98%85%E2%98%85-green) ![](https://img.shields.io/badge/Author-zsdevX-orange) ![](https://img.shields.io/badge/Language-Go-blue) 
    	- 基于go完成的渗透测试信息收集利器
    - [Glass](https://github.com/knownsec/404StarLink2.0-Galaxy/blob/master/TOOLS_README.md#Glass) 
        - ![](https://img.shields.io/badge/Positivity-IN-green) ![](https://img.shields.io/badge/Score-%E2%98%85%E2%98%85%E2%98%85-yellow) ![](https://img.shields.io/badge/Author-s7ckTeam-orange) ![](https://img.shields.io/badge/Language-Python-blue) 
    	- Glass是一款针对资产列表的快速指纹识别工具，通过调用Fofa/ZoomEye/Shodan/360等api接口快速查询资产信息并识别重点资产的指纹，也可针对IP/IP段或资产列表进行快速的指纹识别。
    - [HaE](https://github.com/knownsec/404StarLink2.0-Galaxy/blob/master/TOOLS_README.md#HaE) 
        - ![](https://img.shields.io/badge/Positivity-IN-green) ![](https://img.shields.io/badge/Score-%E2%98%85%E2%98%85%E2%98%85-yellow) ![](https://img.shields.io/badge/Author-gh0stkey-orange) ![](https://img.shields.io/badge/Language-Java-blue) 
    	- HaE是一款可以快速挖掘目标指纹和关键信息的Burp插件
    - [AppInfoScanner](https://github.com/knownsec/404StarLink2.0-Galaxy/blob/master/TOOLS_README.md#AppInfoScanner) 
        - ![](https://img.shields.io/badge/Positivity-IN-green) ![](https://img.shields.io/badge/Score-%E2%98%85%E2%98%85%E2%98%85%E2%98%85-green) ![](https://img.shields.io/badge/Author-kelvinBen-orange) ![](https://img.shields.io/badge/Language-Python-blue) 
    	- 一款适用于以HW行动/红队/渗透测试团队为场景的移动端(Android、iOS、WEB、H5、静态网站)信息收集扫描工具。

	- [ZoomEye-go](https://github.com/knownsec/404StarLink2.0-Galaxy/blob/master/TOOLS_README.md#zoomeye-go)  
        - ![](https://img.shields.io/badge/Positivity-IN-green) ![](https://img.shields.io/badge/Score-%E2%98%85%E2%98%85%E2%98%85%E2%98%85-green)  ![](https://img.shields.io/badge/Author-gyyyy-orange) ![](https://img.shields.io/badge/Language-Go-blue)
        - ZoomEye-go 是一款基于 ZoomEye API 开发的 Golang 库，提供了 ZoomEye 命令行模式。

- Vulnerability Assessment 漏洞探测
  
    - 对目标的各类漏洞探测扫描
    - [kunpeng](https://github.com/knownsec/404StarLink2.0-Galaxy/blob/master/TOOLS_README.md#kunpeng) 
        - ![](https://img.shields.io/badge/Positivity-TBD-yellow) ![](https://img.shields.io/badge/Score-%E2%98%85%E2%98%85%E2%98%85%E2%98%85-green) ![](https://img.shields.io/badge/Author-opensec_cn-orange) ![](https://img.shields.io/badge/Language-Go-blue) 
    	- Kunpeng是一个Golang编写的开源POC检测框架。
    - [myscan](https://github.com/knownsec/404StarLink2.0-Galaxy/blob/master/TOOLS_README.md#myscan) 
        - ![](https://img.shields.io/badge/Positivity-IN-green) ![](https://img.shields.io/badge/Score-%E2%98%85%E2%98%85%E2%98%85%e2%98%86-yellow) ![](https://img.shields.io/badge/Author-amcai-orange) ![](https://img.shields.io/badge/Language-Python-blue) 
        - myscan由python3开发而成的被动扫描工具。
    
- Penetration Test 攻击与利用
    - 在实际渗透测试过程中涉及到的工具
    - [Redis Rogue Server](https://github.com/knownsec/404StarLink2.0-Galaxy/blob/master/TOOLS_README.md#redis-rogue-server) 
        - ![](https://img.shields.io/badge/Positivity-IN-green) ![](https://img.shields.io/badge/Score-%E2%98%85%E2%98%85%e2%98%86-yellow) ![](https://img.shields.io/badge/Author-Dliv3-orange) ![](https://img.shields.io/badge/Language-Python-blue) 
        - Redis 4.x/Redis 5.x RCE利用脚本. 
    - [CDK](https://github.com/knownsec/404StarLink2.0-Galaxy/blob/master/TOOLS_README.md#cdk-)  
        - ![](https://img.shields.io/badge/Positivity-IN-green) ![](https://img.shields.io/badge/Score-%E2%98%85%E2%98%85%E2%98%85%E2%98%85%E2%98%85-green) ![](https://img.shields.io/badge/Author-cdkteam-orange) ![](https://img.shields.io/badge/Language-Go-blue)
        - CDK是一款为容器环境定制的渗透测试工具。
    - [MysqlT & WhetherMysqlSham](https://github.com/knownsec/404StarLink2.0-Galaxy/blob/master/TOOLS_README.md#mysqlt--whethermysqlsham-) ![](https://img.shields.io/badge/-New-red) 
        - ![](https://img.shields.io/badge/Positivity-IN-green) ![](https://img.shields.io/badge/Score-%E2%98%85%E2%98%85%E2%98%85%E2%98%85-green)  ![](https://img.shields.io/badge/Author-BeichenDream-orange) ![](https://img.shields.io/badge/Language-C%23-blue)
        - MysqlT: 伪造Myslq服务端,并利用Mysql逻辑漏洞来获取客户端的任意文件反击攻击者。
        - WhetherMysqlSham：检测目标Mysql数据库是不是蜜罐。
    - [Viper](https://github.com/knownsec/404StarLink2.0-Galaxy/blob/master/TOOLS_README.md#viper-) ![](https://img.shields.io/badge/-New-red)
        - ![](https://img.shields.io/badge/Positivity-IN-green) ![](https://img.shields.io/badge/Score-%E2%98%85%E2%98%85%E2%98%85%E2%98%85-green) ![](https://img.shields.io/badge/Language-JS/Python-blue) ![](https://img.shields.io/badge/Author-FunnyWolf-orange)
        - VIPER是一款图形化内网渗透工具,将内网渗透过程中常用的战术及技术进行模块化及武器化。
    
- Information analysis 信息分析
    - 对在渗透测试中获取到的各种信息做分析
    - [java-object-searcher](https://github.com/knownsec/404StarLink2.0-Galaxy/blob/master/TOOLS_README.md#java-object-searcher) 
      
        - ![](https://img.shields.io/badge/Positivity-In-green) ![](https://img.shields.io/badge/Score-%E2%98%85%E2%98%85%E2%98%85%E2%98%85-green) ![](https://img.shields.io/badge/Author-c0ny1-orange) ![](https://img.shields.io/badge/Language-Java-blue) 
        - java内存对象搜索辅助工具，配合IDEA在Java应用运行时，对内存中的对象进行搜索。比如可以可以用挖掘request对象用于回显等场景。
	-  [HackBrowserData](https://github.com/knownsec/404StarLink2.0-Galaxy/blob/master/TOOLS_README.md#hackbrowserdata-) 
		-  ![](https://img.shields.io/badge/Positivity-IN-green) ![](https://img.shields.io/badge/Score-%E2%98%85%E2%98%85%E2%98%85%E2%98%85-green) ![](https://img.shields.io/badge/Author-moonD4rk-orange) ![](https://img.shields.io/badge/Language-Go-blue) 
		-  一款可全平台运行的浏览器数据导出解密工具
	- [frida-skeleton](https://github.com/knownsec/404StarLink2.0-Galaxy/blob/master/TOOLS_README.md#frida-skeleton-) 
		- ![](https://img.shields.io/badge/Positivity-IN-green) ![](https://img.shields.io/badge/Score-%E2%98%85%E2%98%85%E2%98%85%E2%98%85-green) ![](https://img.shields.io/badge/Author-Margular-orange) ![](https://img.shields.io/badge/Language-Python-blue) 
		- 基于Frida完成的一个更简单易用的安卓hook框架
	- [MySQLMonitor & FileMonitor](https://github.com/knownsec/404StarLink2.0-Galaxy/blob/master/TOOLS_README.md#mysqlmonitor--filemonitor-)  
	- 	- ![](https://img.shields.io/badge/Positivity-IN-green) ![![](https://img.shields.io/badge/Author-madneal-orange) ](https://img.shields.io/badge/Score-%E2%98%85%E2%98%85%E2%98%85-yellow) ![](https://img.shields.io/badge/Author-TheKingofDuck-orange) ![](https://img.shields.io/badge/Language-Java|Python-blue) 
		- MySQL实时监控工具 & 文件变化实时监控工具
    - [CodeReviewTools](https://github.com/knownsec/404StarLink2.0-Galaxy/blob/master/TOOLS_README.md#codereviewtools-) ![](https://img.shields.io/badge/-New-red)
        - ![](https://img.shields.io/badge/Positivity-IN-green) ![](https://img.shields.io/badge/Score-%E2%98%85%E2%98%85%E2%98%85%e2%98%86-yellow) ![](https://img.shields.io/badge/Language-Java-blue) ![](https://img.shields.io/badge/Author-Ppsoft1991-orange)
        - CodeReviewTools是一个可以快速批量反编译jar包的工具。
    
- Back-penetration, intranet tools  后渗透、内网工具
    - 在渗透测试后涉及到的权限维持，或者内网渗透涉及到的工具
    - [antSword](https://github.com/knownsec/404StarLink2.0-Galaxy/blob/master/TOOLS_README.md#antSword) 
        - ![](https://img.shields.io/badge/Positivity-IN-green) ![](https://img.shields.io/badge/Score-%E2%98%85%E2%98%85%E2%98%85%E2%98%85%E2%98%85-green) ![](https://img.shields.io/badge/Author-AntSwordProject-orange) ![](https://img.shields.io/badge/Language-Nodejs-blue) 
        - 中国蚁剑是一款开源的跨平台网站管理工具，一个所有安全从业者都不应该错过的开源项目。
    - [ServerScan](https://github.com/knownsec/404StarLink2.0-Galaxy/blob/master/TOOLS_README.md#serverscan--)  
        - ![](https://img.shields.io/badge/Positivity-IN-green) ![](https://img.shields.io/badge/Score-%E2%98%85%E2%98%85%E2%98%85%E2%98%85-green) ![](https://img.shields.io/badge/Author-Trim-orange) ![](https://img.shields.io/badge/Language-Go-blue) 
        - 一款使用Golang开发且适用于攻防演习内网横向信息收集的高并发网络扫描、服务探测工具。
    
- Others 其他相关
    - 其他安全链路下的安全类工具
    - [passive-scan-client](https://github.com/knownsec/404StarLink2.0-Galaxy/blob/master/TOOLS_README.md#passive-scan-client)
        - ![](https://img.shields.io/badge/Positivity-IN-green) ![](https://img.shields.io/badge/Score-%E2%98%85%E2%98%85%E2%98%85-yellow) ![](https://img.shields.io/badge/Author-c0ny1-orange) ![](https://img.shields.io/badge/Language-Java-blue) 
        - Passive Scan Client是一款可以将经过筛选的流量转发到指定代理的Burp被动扫描流量转发插件。
    - [f8x](https://github.com/knownsec/404StarLink2.0-Galaxy/blob/master/TOOLS_README.md#f8x--)  
      
        - ![](https://img.shields.io/badge/Positivity-IN-green) ![](https://img.shields.io/badge/Score-%E2%98%85%E2%98%85%E2%98%85%E2%98%85-green) ![](https://img.shields.io/badge/Author-ffffffff0x-orange) ![](https://img.shields.io/badge/Language-Bash-blue) 
- 一款红/蓝队环境自动化部署工具,支持多种场景,渗透,开发,代理环境,服务可选项等。
      
  
  ​        

# Community

如果有问题可以在各项目下提交issue，如果有不错的工具推荐，可以向github提交issue, 也可以添加下方的讨论组中参与讨论。

1、Github issue: [https://github.com/knownsec/404StarLink2.0-Galaxy/issues](https://github.com/knownsec/404StarLink2.0-Galaxy/issues) 

2、微信群：

微信群有两种添加方式：

(1) 联系Seebug的各位小伙伴拉你入群，如：
![image-20200902105354031](./init1.png) 

(2) 扫描一下二维码添加我的个人微信，并备注**星链计划**，会把大家拉到星链计划交流群中

<img src="./wechat.jpg" alt="image-20200902105546332" style="zoom:50%;" />