# 仓库分类索引

[返回个人主页](README.md)

代表项目与独立改动见个人主页。此页按研究方向整理公开仓库，不把 Fork 数量或上游功能当成个人成果。分类只表示主题，不代表维护状态或安全结论。

## AI 与审计工具

- [autonomous-pentest-agent](https://github.com/Strugg1e/autonomous-pentest-agent)：LLM 多 Agent 授权安全测试系统，包含 Go 后端与 Next.js 界面。
- [codebase-memory-mcp-sec](https://github.com/Strugg1e/codebase-memory-mcp-sec)：AI 代码审计的静态分析与可引用程序证据。
- [rea](https://github.com/Strugg1e/rea)：Agent 辅助逆向工程，从应用行为到原生二进制。
- [strix](https://github.com/Strugg1e/strix)：中文控制台、报告导出与恢复扫描；开发改动见草稿 PR #1。

## 移动安全与逆向

- [AndroidSecurityStudy](https://github.com/Strugg1e/AndroidSecurityStudy)：安卓应用安全学习
- [frida-ios-dump](https://github.com/Strugg1e/frida-ios-dump)：从越狱设备导出解密 IPA 的研究工具。
- [frida-unpack](https://github.com/Strugg1e/frida-unpack)：基于Frida的脱壳工具
- [hooker](https://github.com/Strugg1e/hooker)：Frida 逆向脚本管理、Hook 生成与应用运行信息探查。
- [JustTrustMePlus](https://github.com/Strugg1e/JustTrustMePlus)：Android HTTPS 抓包研究工具，包含混淆 OkHttp 场景适配；保留上游实现与署名。
- [JustTrustMePP](https://github.com/Strugg1e/JustTrustMePP)：Android HTTPS 证书校验与混淆 OkHttp 的抓包研究；保留上游实现与署名。
- [mvt](https://github.com/Strugg1e/mvt)：移动设备感染迹象的取证分析工具。
- [NoVmp](https://github.com/Strugg1e/NoVmp)：基于 VTIL 的 VMProtect x64 静态去虚拟化工具。
- [OkHttpLogger-Frida](https://github.com/Strugg1e/OkHttpLogger-Frida)：Frida 实现拦截okhttp的脚本
- [QtScrcpy](https://github.com/Strugg1e/QtScrcpy)：Android 实时投屏与设备控制。
- [r0capture](https://github.com/Strugg1e/r0capture)：安卓应用层抓包通杀脚本
- [r0tracer](https://github.com/Strugg1e/r0tracer)：安卓Java层多功能追踪脚本
- [unpacker](https://github.com/Strugg1e/unpacker)：基于ART主动调用的脱壳机

## 资产发现与信息收集

- [AppInfoScanner](https://github.com/Strugg1e/AppInfoScanner)：移动应用与静态站点的信息收集、指纹识别。
- [ARL](https://github.com/Strugg1e/ARL)：互联网资产发现、关联与检索。
- [Autoscanner](https://github.com/Strugg1e/Autoscanner)：组合子域发现、端口扫描和 Web 扫描的自动化流程。
- [Eeyes](https://github.com/Strugg1e/Eeyes)：Eeyes(棱眼)-快速筛选真实IP并整理为C段
- [EHole](https://github.com/Strugg1e/EHole)：EHole(棱洞)-红队重点攻击系统指纹探测工具
- [farmscan_domain](https://github.com/Strugg1e/farmscan_domain)：信息收集——子域名、IP段、邮箱
- [FofaSpider](https://github.com/Strugg1e/FofaSpider)：Fofa爬虫支持高级查询语句批量爬取
- [Google-Spider](https://github.com/Strugg1e/Google-Spider)：谷歌爬虫，自动解析谷歌搜索信息，需搭配clash使用，生成cvs
- [InCloud](https://github.com/Strugg1e/InCloud)：基于 GitHub Actions 的信息收集与授权扫描工作流。
- [info-hub](https://github.com/Strugg1e/info-hub)：信息收集：资产收集、邮箱收集
- [Kunyu](https://github.com/Strugg1e/Kunyu)：企业资产信息收集工具。
- [OneForAll](https://github.com/Strugg1e/OneForAll)：OneForAll是一款功能强大的子域收集工具
- [ShuiZe_0x727](https://github.com/Strugg1e/ShuiZe_0x727)：信息收集自动化工具
- [SimplyEmail](https://github.com/Strugg1e/SimplyEmail)：邮箱信息收集与检索框架。
- [theHarvester](https://github.com/Strugg1e/theHarvester)：邮箱、子域与人员名称的公开信息收集。

## Web 与 Java 安全

- [burp-unauth-checker](https://github.com/Strugg1e/burp-unauth-checker)：Burp Suite 未授权访问检测扩展。
- [evil-mysql-server-su18](https://github.com/Strugg1e/evil-mysql-server-su18)：MySQL 协议与 Java 反序列化研究工具，包含 su18-ysu 适配；仅用于授权实验。
- [Gr33k](https://github.com/Strugg1e/Gr33k)：图形化漏洞利用集成工具
- [HackBar](https://github.com/Strugg1e/HackBar)：Burp Suite 的 HackBar 扩展。
- [java-sec-code](https://github.com/Strugg1e/java-sec-code)（归档）：学习存档：Java Web 漏洞靶场与安全示例。保留上游代码及历史，不维护依赖更新；仅用于隔离的授权实验环境。
- [learnjavabug](https://github.com/Strugg1e/learnjavabug)：Java 反序列化、框架与中间件安全研究示例。
- [micro_service_seclab](https://github.com/Strugg1e/micro_service_seclab)：Java漏洞靶场
- [shiro_attack](https://github.com/Strugg1e/shiro_attack)：shiro反序列化漏洞综合利用,包含（回显执行命令/注入内存马）
- [SpringBootVulExploit](https://github.com/Strugg1e/SpringBootVulExploit)：SpringBoot 相关漏洞学习资料，利用方法和技巧合集，黑盒安全评估 check list
- [ssrf-king](https://github.com/Strugg1e/ssrf-king)：Burp Suite 的 SSRF 检测扩展。
- [XSStrike](https://github.com/Strugg1e/XSStrike)：XSS 检测与研究工具。

## 漏洞资料与复现

- [advisories](https://github.com/Strugg1e/advisories)：安全公告与漏洞研究资料；派生自 x41sec/advisories，保留上游来源。
- [ArbitraryFileReadList](https://github.com/Strugg1e/ArbitraryFileReadList)：CTF中任意文件读取的fuzz列表 (Arbitrary file read fuzz list in CTF)
- [AttackWebFrameworkTools](https://github.com/Strugg1e/AttackWebFrameworkTools)：Web 框架高危漏洞的验证与复现工具合集。
- [cve](https://github.com/Strugg1e/cve)：CVE 与公开 PoC 资料索引。
- [exphub](https://github.com/Strugg1e/exphub)：Web 框架与中间件漏洞复现脚本合集。
- [Kernelhub](https://github.com/Strugg1e/Kernelhub)：Windows 内核提权漏洞研究与复现资料。
- [keyhacks](https://github.com/Strugg1e/keyhacks)：漏洞奖励计划中 API key 有效性核验的研究资料。
- [loophole](https://github.com/Strugg1e/loophole)：记录搭建漏洞环境及漏洞复现
- [Middleware-Vulnerability-detection](https://github.com/Strugg1e/Middleware-Vulnerability-detection)：CVE、CMS、中间件漏洞检测利用合集 Since 2019-9-15
- [Penetration_Testing_POC](https://github.com/Strugg1e/Penetration_Testing_POC)：授权安全测试的 PoC、脚本与小工具资料。
- [POC-S](https://github.com/Strugg1e/POC-S)：基于 POC-T 的验证脚本分类与功能扩展。
- [POChouse](https://github.com/Strugg1e/POChouse)：POC&EXP仓库、hvv弹药库、Nday、1day
- [Some-PoC-oR-ExP](https://github.com/Strugg1e/Some-PoC-oR-ExP)：各种漏洞poc、Exp的收集或编写

## 授权测试与红队研究

- [2021_Hvv](https://github.com/Strugg1e/2021_Hvv)：2021 hw
- [BypassAntiVirus](https://github.com/Strugg1e/BypassAntiVirus)：终端安全对抗技术、测试文章与配套工具。
- [cf](https://github.com/Strugg1e/cf)：云环境利用框架（Cloud exploitation framework）主要用来方便红队人员在获得 AK 的后续工作。
- [CS-Loader](https://github.com/Strugg1e/CS-Loader)：CS免杀
- [DNS-Shell](https://github.com/Strugg1e/DNS-Shell)：DNS 通道交互式 Shell 的研究示例。
- [fscan](https://github.com/Strugg1e/fscan)：一款内网综合扫描工具，方便一键自动化、全方位漏扫扫描。
- [InScan](https://github.com/Strugg1e/InScan)：边界打点后的自动化渗透工具
- [K8tools](https://github.com/Strugg1e/K8tools)：内网安全、提权与漏洞复现工具资料合集。
- [LuWu](https://github.com/Strugg1e/LuWu)：红队基础设施自动化部署工具
- [Medusa](https://github.com/Strugg1e/Medusa)：红队研究平台，包含 XSS、CVE 监控与 DNSLog。
- [pypykatz](https://github.com/Strugg1e/pypykatz)：Python 实现的 Mimikatz 研究工具。
- [red-tldr](https://github.com/Strugg1e/red-tldr)：红队研究命令与操作要点的文本检索。
- [redteam-tools](https://github.com/Strugg1e/redteam-tools)：红队作战中的一些工具分享。
- [RedTeamAttack](https://github.com/Strugg1e/RedTeamAttack)：关于红队方面的一些工具\资料\Checklist
- [redteam_attack](https://github.com/Strugg1e/redteam_attack)：收集红蓝对抗以及ATT&CK相关的一些资料和工具
- [SatanSword](https://github.com/Strugg1e/SatanSword)：红队综合渗透框架
- [ShellManageTool](https://github.com/Strugg1e/ShellManageTool)：在网传的哥斯拉&冰蝎源码基础上加了一点注释
- [Taie-RedTeam-OS](https://github.com/Strugg1e/Taie-RedTeam-OS)：泰阿安全实验室-基于XUbuntu私人订制的红蓝对抗渗透操作系统
- [TENGSHE-OS](https://github.com/Strugg1e/TENGSHE-OS)：腾蛇系列渗透系统
- [Viper](https://github.com/Strugg1e/Viper)：Viper (炫彩蛇) 开源图形化内网渗透工具
- [vscan](https://github.com/Strugg1e/vscan)：端口、指纹与已知漏洞的授权扫描工具。

## 学习资料与 CTF

- [awesome-hacking-lists](https://github.com/Strugg1e/awesome-hacking-lists)：平常看到好的渗透hacking工具和多领域效率工具的集合
- [ctf-wiki](https://github.com/Strugg1e/ctf-wiki)：CTF 知识与题型学习资料。
- [Dictionary-Of-Pentesting](https://github.com/Strugg1e/Dictionary-Of-Pentesting)：授权安全测试、Fuzzing 与漏洞研究的字典资料。
- [HackerMind](https://github.com/Strugg1e/HackerMind)：Web、移动、二进制与安全运维的学习资料。
- [sec-chart](https://github.com/Strugg1e/sec-chart)：安全思维导图集合
- [Venom-WP](https://github.com/Strugg1e/Venom-WP)：CTF 竞赛 Writeup 与题解 PDF 资料，保留上游来源。

## 防御与安全运维

- [APT-Hunter](https://github.com/Strugg1e/APT-Hunter)：基于 Windows 事件日志的威胁狩猎工具。
- [code6](https://github.com/Strugg1e/code6)：码小六 - GitHub 代码泄露监控系统
- [DuckMemoryScan](https://github.com/Strugg1e/DuckMemoryScan)：检测绝大部分所谓的内存免杀马
- [Security-Operation](https://github.com/Strugg1e/Security-Operation)：安全运维技巧整理

## 资讯、自动化与其他项目

- [0sec-Sign](https://github.com/Strugg1e/0sec-Sign)：零组文库签到
- [blog_for_thinkphp6](https://github.com/Strugg1e/blog_for_thinkphp6)：用作毕业设计和个人博客基于thinkphp6的web应用
- [holiday-cn](https://github.com/Strugg1e/holiday-cn)：从国务院公告更新中国法定节假日数据。
- [opensips](https://github.com/Strugg1e/opensips)（归档）：学习存档：OpenSIPS SIP Server 上游副本。保留代码与历史，不维护自动依赖更新；最新版本请查看上游。
- [shadow1ng.github.io](https://github.com/Strugg1e/shadow1ng.github.io)：shadow1ng.github.io 的静态页面副本，保留上游来源。
- [wechat-radarf](https://github.com/Strugg1e/wechat-radarf)：微信聊天情报看板：聚合群聊信号、话题、链接和趋势
- [yarb-feishu](https://github.com/Strugg1e/yarb-feishu)：每日安全资讯 RSS 聚合与飞书群推送。

## 阅读说明

- 各仓库的 Fork 标记和上游链接是来源依据；独立贡献以实际提交、README 和 PR 为准。
- 归档仓库保留作参考，不作为正在维护的产品推荐。
- 本索引不展示私人仓库、平台禁用仓库或正在调整可见性的项目。
