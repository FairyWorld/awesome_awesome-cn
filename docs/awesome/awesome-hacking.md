<div class="github-widget" data-repo="carpedm20/awesome-hacking"></div>
## Awesome Hacking -An Amazing Project [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

精选的黑客攻击列表. 灵感来自 [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning/)

如果您想为此列表做出贡献（请这样做），请向我发送拉取请求或与我联系 [@carpedm20](https://twitter.com/carpedm20)

如需可供下载的免费黑客书籍列表，请访问 [here](https://github.com/Hack-with-Github/Free-Security-eBooks)



<!-- MarkdownTOC depth=4 -->


<!-- /MarkdownTOC -->

## System

## Tutorials
 * [Roppers Computing Fundamentals](https://hoppersroppers.org/course.html)
     * 免费、自定进度的课程，构建计算机和网络知识基础. 旨在培养没有先验技术知识的学生，让他们相信自己有能力学习任何东西并继续接受安全教育. 全文可作为 [gitbook](https://www.hoppersroppers.org/fundamentals/).
 * [Corelan Team's Exploit writing tutorial](https://www.corelan.be/index.php/2009/07/19/exploit-writing-tutorial-part-1-stack-based-overflows/)
 * [Exploit Writing Tutorials for Pentesters](http://web.archive.org/web/20140916085343/http://www.punter-infosec.com/exploit-writing-tutorials-for-pentesters/)
 * [Understanding the basics of Linux Binary Exploitation](https://github.com/r0hi7/BinExp)
 * [Shells](https://www.youtube.com/playlist?list=PLyzOVJj3bHQuloKGG59rS43e29ro7I57J)
 * [Missing Semester](https://missing.csail.mit.edu/2020/course-shell/)


## Tools
 * [Metasploit](https://github.com/rapid7/metasploit-framework) 一个计算机安全项目，提供有关安全漏洞的信息并帮助渗透测试和 IDS 签名开发.
 * [mimikatz](https://github.com/gentilkiwi/mimikatz) - 玩转Windows安全的小工具
 * [Hackers tools](https://www.youtube.com/playlist?list=PLyzOVJj3bHQuiujH1lpn8cA9dsyulbYRv) - 工具教程.

### Docker Images for Penetration Testing & Security
 * `docker pull kalilinux/kali-linux-docker` [official Kali Linux](https://hub.docker.com/r/kalilinux/kali-linux-docker/)
 *`docker pull owasp/zap2docker-stable`- [official OWASP ZAP](https://github.com/zaproxy/zaproxy)
 * `docker pull wpscanteam/wpscan` - [official WPScan](https://hub.docker.com/r/wpscanteam/wpscan/)
 * `docker pull metasploitframework/metasploit-framework
` - [Official Metasploit](https://hub.docker.com/r/metasploitframework/metasploit-framework/)
 * `docker pull citizenstig/dvwa` - [Damn Vulnerable Web Application (DVWA)](https://hub.docker.com/r/citizenstig/dvwa/)
 * `docker pull wpscanteam/vulnerablewordpress` - [Vulnerable WordPress Installation](https://hub.docker.com/r/wpscanteam/vulnerablewordpress/)
 * `docker pull hmlio/vaas-cve-2014-6271` - [Vulnerability as a service: Shellshock](https://hub.docker.com/r/hmlio/vaas-cve-2014-6271/)
 * `docker pull hmlio/vaas-cve-2014-0160` - [Vulnerability as a service: Heartbleed](https://hub.docker.com/r/hmlio/vaas-cve-2014-0160/)
 * `docker pull opendns/security-ninjas` - [Security Ninjas](https://hub.docker.com/r/opendns/security-ninjas/)
 *`docker pull noncetonic/archlinux-pentest-lxde`- [Arch Linux Penetration Tester](https://hub.docker.com/r/noncetonic/archlinux-pentest-lxde)
 *`docker pull diogomonica/docker-bench-security`- [Docker Bench for Security](https://hub.docker.com/r/diogomonica/docker-bench-security/)
 * `docker pull ismisepaul/securityshepherd` - [OWASP Security Shepherd](https://hub.docker.com/r/ismisepaul/securityshepherd/)
 * `docker pull danmx/docker-owasp-webgoat` - [OWASP WebGoat Project docker image](https://hub.docker.com/r/danmx/docker-owasp-webgoat/)
 * `docker pull 弱点/web-owasp-nodegoat` - [OWASP NodeGoat](https://github.com/owasp/nodegoat#option-3---run-nodegoat-on-docker)
 * `docker pull citizenstig/nowasp` - [OWASP Mutillidae II Web Pen-Test Practice Application](https://hub.docker.com/r/citizenstig/nowasp/)
 * `docker pull bkimminich/juice-shop` - [OWASP Juice Shop](https://github.com/bkimminich/juice-shop#docker-container--)
 * `docker pull phocean/msf` - [Docker Metasploit](https://hub.docker.com/r/phocean/msf/)

## General
 * [Exploit database](https://www.exploit-db.com/) - 漏洞利用和易受攻击软件的终极档案


## Reverse Engineering

## Tutorials
* [Begin RE: A Reverse Engineering Tutorial Workshop](https://www.begin.re/the-workshop)
* [Malware Analysis Tutorials: a Reverse Engineering Approach](http://fumalwareanalysis.blogspot.kr/p/malware-analysis-tutorials-reverse.html)
* [Malware Unicorn Reverse Engineering Tutorial](https://malwareunicorn.org/workshops/re101.html#0)
* [Lena151: Reversing With Lena](https://archive.org/details/lena151)

## Tools
### Disassemblers and debuggers
 * [IDA](https://www.hex-rays.com/products/ida/) - IDA 是 Windows、Linux 或 Mac OS X 托管的多处理器反汇编器和调试器
 * [OllyDbg](http://www.ollydbg.de/) - 适用于 Windows 的 32 位汇编程序级分析调试器
 * [x64dbg](https://github.com/x64dbg/x64dbg) - An open-source x64/x32 debugger for Windows
 * [radare2](https://github.com/radare/radare2) - 便携式倒车框架
 * [plasma](https://github.com/joelpx/plasma)  - 用于 x86/ARM/MIPS 的交互式反汇编器. 生成带有彩色语法代码的缩进伪代码.
 * [ScratchABit](https://github.com/pfalcon/ScratchABit) - 使用 IDAPython 兼容的插件 API 轻松重定向和破解交互式反汇编程序
 * [Capstone](https://github.com/aquynh/capstone)
 * [Ghidra](https://ghidra-sre.org/) - 由 NSA 研究理事会开发的软件逆向工程 (SRE) 工具套件，用于支持网络安全任务

### Decompilers
* 基于 JVM 的语言
  * [Krakatau](https://github.com/Storyyeller/Krakatau)  - 我用过的最好的反编译器. 能够将用 Scala 和 Kotlin 编写的应用程序反编译为 Java 代码.  JD-GUI 和 Luyten 都未能完全做到这一点.
  * [JD-GUI](https://github.com/java-decompiler/jd-gui)
  * [procyon](https://bitbucket.org/mstrobel/procyon/wiki/Java%20Decompiler)
    * [Luyten](https://github.com/deathmarine/Luyten) - 最好的之一，虽然有点慢，但挂在一些二进制文件上并且维护得不是很好.
  * [JAD](http://varaneckas.com/jad/) - JAD Java 反编译器（闭源，未维护）
  * [JADX](https://github.com/skylot/jadx)  - Android 应用程序的反编译器. 与 JAD 无关.

* 基于 .net 的语言
  * [dotPeek](https://www.jetbrains.com/decompiler/) - 来自 JetBrains 的免费 .NET 反编译器
  * [ILSpy](https://github.com/icsharpcode/ILSpy/) - 开源 .NET 程序集浏览器和反编译器
  * [dnSpy](https://github.com/0xd4d/dnSpy) - .NET 程序集编辑器、反编译器和调试器

* 本机代码
  * [Hopper](https://www.hopperapp.com) - 用于 32/64 位 Windows/Mac/Linux/iOS 可执行文件的 OS X 和 Linux 反汇编程序/反编译程序.
  * [cutter](https://github.com/radareorg/cutter) - 基于 radare2 的反编译器.
  * [retdec](https://github.com/avast-tl/retdec)
  * [snowman](https://github.com/yegord/snowman)
  * [Hex-Rays](https://www.hex-rays.com/products/decompiler/)

* Python
  * [uncompyle6](https://github.com/rocky/python-uncompyle6) - 用于 20 多个版本和 20 年的 CPython 的反编译器.


### Deobfuscators
 * [de4dot](https://github.com/0xd4d/de4dot) - .NET 去混淆器和解包器.
 * [JS Beautifier](https://github.com/beautify-web/js-beautify)
 * [JS Nice](http://jsnice.org/) - 基于开源模型猜测 JS 变量名称和类型的 Web 服务.

### Other
 * [nudge4j](https://github.com/lorenzoongithub/nudge4j) - 让浏览器与 JVM 对话的 Java 工具
 * [dex2jar](https://github.com/pxb1988/dex2jar) - 用于处理 Android .dex 和 Java .class 文件的工具
 * [androguard](https://code.google.com/p/androguard/) - Android 应用程序的逆向工程、恶意软件和好软件分析
 * [antinet](https://github.com/0xd4d/antinet) - .NET 反托管调试器和反分析器代码
 * [UPX](http://upx.sourceforge.net/) - 用于可执行文件的 Ultimate Packer（和解包器）

### Execution logging and tracing
 * [Wireshark](https://www.wireshark.org/) - 一个免费的开源数据包分析器
 * [tcpdump](http://www.tcpdump.org/)  - 强大的命令行数据包分析器； 和 libpcap，一个用于网络流量捕获的可移植 C/C++ 库
 * [mitmproxy](https://github.com/mitmproxy/mitmproxy) - 具有控制台界面的 HTTP 交互式、支持 SSL 的中间人代理
 * [Charles Proxy](https://charlesproxy.com) - 一个跨平台的 GUI 网络调试代理，用于查看拦截的 HTTP 和 HTTPS/SSL 实时流量
 * [usbmon](https://www.kernel.org/doc/Documentation/usb/usbmon.txt) - 用于 Linux 的 USB 捕获.
 * [USBPcap](https://github.com/desowin/usbpcap) - 适用于 Windows 的 USB 捕获.
 * [dynStruct](https://github.com/ampotos/dynStruct) - 通过动态检测结构恢复.
 * [drltrace](https://github.com/mxmssh/drltrace) - 共享库调用跟踪.

### Binary files examination and editing

#### Hex editors
 * [HxD](http://mh-nexus.de/en/hxd/) - 一个十六进制编辑器，除了原始磁盘编辑和修改主内存 (RAM) 之外，还可以处理任何大小的文件
 * [WinHex](http://www.winhex.com/winhex/) - 十六进制编辑器，有助于计算机取证、数据恢复、低级数据处理和 IT 安全领域
* [wxHexEditor](https://github.com/EUA/wxHexEditor)
* [Synalize It](https://www.synalysis.net/)/[Hexinator](https://hexinator.com/) -

#### Other
 * [Binwalk](https://github.com/ReFirmLabs/binwalk) - 检测签名、解压缩档案、可视化熵.
 * [Veles](https://github.com/codilime/veles) - blob 统计特性的可视化工具.
 * [Kaitai Struct](https://github.com/kaitai-io/kaitai_struct)  - 用于创建各种编程语言解析器的 DSL.  Web IDE 对于逆向工程特别有用.
 * [Protobuf inspector](https://github.com/jmendeth/protobuf-inspector)
 * [DarunGrim](https://github.com/ohjeongwook/DarunGrim) - 可执行文件不同.
 * [DBeaver](https://github.com/dbeaver/dbeaver) - 数据库编辑器.
 * [Dependencies](https://github.com/lucasg/Dependencies) - Dependency Walker 的 FOSS 替代品.
 * [PEview](http://wjradburn.com/software/) - 查看 32 位可移植可执行 (PE) 和组件对象文件格式 (COFF) 文件的结构和内容的快速简便方法
* [BinText](https://web.archive.org/web/http://www.mcafee.com/kr/downloads/free-tools/bintext.aspx) - 一个小型、非常快速且功能强大的文本提取器，程序员将特别感兴趣.

## General
 * [Open Malware](http://www.offensivecomputing.net/)

## Web

## Tools
 * [Spyse](https://spyse.com/)  - 使用 OSINT 收集网络信息的数据收集服务. 提供的信息：IPv4 主机、域/whois、端口/标语/协议、技术、操作系统、AS、维护巨大的 SSL/TLS 数据库等等……所有数据都存储在自己的数据库中，无需扫描即可获取数据.
 * [sqlmap](https://github.com/sqlmapproject/sqlmap) - 自动 SQL 注入和数据库接管工具
 * [NoSQLMap](https://github.com/codingo/NoSQLMap) - 自动 NoSQL 数据库枚举和 Web 应用程序开发工具.
 * [tools.web-max.ca](http://tools.web-max.ca/encode_decode.php) - base64 base85 md4,5 hash, sha1 hash编码/解码
 * [VHostScan](https://github.com/codingo/VHostScan) - 执行反向查找的虚拟主机扫描器，可与数据透视工具一起使用，检测包罗万象的场景、别名和动态默认页面.
 * [SubFinder](https://github.com/subfinder/subfinder) - SubFinder 是一种子域发现工具，可使用被动在线资源为任何目标发现有效的子域.
 * [Findsubdomains](https://findsubdomains.com/) - 一个子域发现工具，从开源互联网收集所有可能的子域，并通过各种工具验证它们以提供准确的结果.
 * [badtouch](https://github.com/kpcyrd/badtouch) - 可编写脚本的网络身份验证破解程序
 * [PhpSploit](https://github.com/nil0x42/phpsploit) - 功能齐全的 C2 框架，通过邪恶的 PHP oneliner 默默地存在于网络服务器上
 * [Git-Scanner](https://github.com/HightechSec/git-scanner) - 一种针对具有公开可用的开放 `.git` 存储库的网站进行错误搜索或渗透测试的工具
 * [CSP Scanner](https://cspscanner.com/) - 分析站点的内容安全策略 (CSP) 以查找绕过和丢失的指令.
 * [Decompiler.com](https://www.decompiler.com/) - Java, Android, Python, C# online decompiler.

## General
 * [Strong node.js](https://github.com/jesusprubio/strong-node) - 一个详尽的清单，以帮助对 node.js Web 服务的源代码安全性进行分析.


## Network

## Tools
 * [NetworkMiner](http://www.netresec.com/?page=NetworkMiner) - 网络取证分析工具 (NFAT)
 * [Paros](http://sourceforge.net/projects/paros/) - 用于评估 Web 应用程序漏洞的基于 Java 的 HTTP/HTTPS 代理
 * [pig](https://github.com/rafael-santiago/pig) - 一个 Linux 数据包制作工具
 * [findsubdomains](https://findsubdomains.com) - 真正快速的子域扫描服务，比简单的子域查找器（使用 OSINT 工作）有更多的机会.
 * [cirt-fuzzer](http://www.cirt.dk/) - 一个简单的 TCP/UDP 协议模糊器.
 * [ASlookup](https://aslookup.com/) - 探索自治系统和所有相关信息（CIDR、ASN、Org...）的有用工具
 * [ZAP](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project) - Zed Attack Proxy (ZAP) 是一种易于使用的集成渗透测试工具，用于查找 Web 应用程序中的漏洞
 * [mitmsocks4j](https://github.com/Akdeniz/mitmsocks4j) - Java 的中间人 SOCKS 代理
 * [ssh-mitm](https://github.com/jtesta/ssh-mitm) - 记录交互式会话和密码的 SSH/SFTP 中间人工具.
 * [nmap](https://nmap.org/) - Nmap (Network Mapper) 是一个安全扫描器
 * [Aircrack-ng](http://www.aircrack-ng.org/) - 一个 802.11 WEP 和 WPA-PSK 密钥破解程序
 * [Nipe](https://github.com/GouveaHeitor/nipe) - 使 Tor 网络成为默认网关的脚本.
 * [Habu](https://github.com/portantier/habu) - Python 网络黑客工具包
 * [Wifi Jammer](https://n0where.net/wifijammer/) - 干扰范围内所有 wifi 客户端的免费程序
 * [Firesheep](https://codebutler.github.io/firesheep/) - 用于 HTTP 会话劫持攻击的免费程序.
 * [Scapy](https://github.com/secdev/awesome-scapy) - 用于低级数据包创建和操作的 Python 工具和库
 * [Amass](https://github.com/OWASP/Amass) - 深入的子域枚举工具，可执行抓取、递归暴力破解、网络档案抓取、名称更改和反向 DNS 扫描
 * [sniffglue](https://github.com/kpcyrd/sniffglue) - 安全的多线程数据包嗅探器
 * [Netz](https://github.com/spectralops/netz) - 使用 zgrab2 和其他工具发现 Internet 范围内的错误配置.
 * [RustScan](https://github.com/rustscan/rustscan) - 用 Rust 构建的极快的端口扫描器，旨在在几秒钟内扫描所有端口，并利用 nmap 在很短的时间内执行端口枚举.

## Forensic

## Tools
 * [Autopsy](http://www.sleuthkit.org/autopsy/) - 数字取证平台和图形界面 [The Sleuth Kit](http://www.sleuthkit.org/sleuthkit/index.php) 和其他数字取证工具
 * [sleuthkit](https://github.com/sleuthkit/sleuthkit) - 命令行数字取证工具库和集合
 * [EnCase](https://www.guidancesoftware.com/products/Pages/encase-forensic/overview.aspx) - Guidance Software 的一套数字调查产品中的共享技术
 * [malzilla](http://malzilla.sourceforge.net/) - 恶意软件搜寻工具
 * [IPED - Indexador e Processador de Evidências Digitais](https://servicos.dpf.gov.br/ferramentas/IPED/) - 巴西联邦警察法医调查工具

## Cryptography

### Tools
 * [xortool](https://github.com/hellman/xortool) - 分析多字节异或密码的工具
 * [John the Ripper](http://www.openwall.com/john/) - 一个快速的密码破解器
 * [Aircrack](http://www.aircrack-ng.org/) - Aircrack 是 802.11 WEP 和 WPA-PSK 密钥破解程序.
 * [Ciphey](https://github.com/ciphey/ciphey) - 使用人工智能和自然语言处理的自动解密工具.


## Wargame

## System
 * [OverTheWire - Semtex](http://overthewire.org/wargames/semtex/)
 * [OverTheWire - Vortex](http://overthewire.org/wargames/vortex/)
 * [OverTheWire - Drifter](http://overthewire.org/wargames/drifter/)
 * [pwnable.kr](http://pwnable.kr/) - 提供关于系统安全的各种pwn挑战
 * [Exploit Exercises - Nebula](https://exploit-exercises.com/nebula/)
 * [SmashTheStack](http://smashthestack.org/)
 * [HackingLab](https://www.hacking-lab.com/) 

## Reverse Engineering
 * [Reversing.kr](http://www.reversing.kr/) - 该站点测试您破解和逆向代码工程的能力
 * [CodeEngn](http://codeengn.com/challenges/) - （韩国人）
 * [simples.kr](http://simples.kr/) - （韩国人）
 * [Crackmes.de](http://crackmes.de/) - 世界上第一个也是最大的 crackmes 和 reversemes 社区网站.

## Web
 * [Hack This Site!](https://www.hackthissite.org/) - 一个免费、安全和合法的黑客培训基地，供黑客测试和扩展他们的黑客技能
 * [Hack The Box](https://www.hackthebox.eu) - 一个免费网站，可以在各种不同的系统中进行渗透测试.
 * [Webhacking.kr](http://webhacking.kr/)
 * [0xf.at](https://0xf.at/) - 一个没有登录名或广告的网站，您可以在其中解决密码谜语（所谓的 hackits）.
 * [fuzzy.land](https://fuzzy.land/)  - 奥地利集团的网站. 从他们参加的 CTF 中获得了很多挑战.
 * [Gruyere](https://google-gruyere.appspot.com/)
 * [Others](https://www.owasp.org/index.php/OWASP_Vulnerable_Web_Applications_Directory_Project#tab=On-Line_apps)
 * [TryHackMe](https://tryhackme.com/) - 通过真实场景进行实践网络安全培训.

## Cryptography
 * [OverTheWire - Krypton](http://overthewire.org/wargames/krypton/)

## Bug bounty
  * [Awesome bug bounty resources by EdOverflow](https://github.com/EdOverflow/bugbounty-cheatsheet)

## Bug bounty -  Earn Some Money
  * [Bugcrowd](https://www.bugcrowd.com/)
  * [Hackerone](https://www.hackerone.com/start-hacking)


## CTF

## Competition
 * [DEF CON](https://legitbs.net/)
 * [CSAW CTF](https://ctf.isis.poly.edu/)
 * [hack.lu CTF](http://hack.lu/)
 * [Pliad CTF](http://www.plaidctf.com/)
 * [RuCTFe](http://ructf.org/e/)
 * [Ghost in the Shellcode](http://ghostintheshellcode.com/)
 * [PHD CTF](http://www.phdays.com/)
 * [SECUINSIDE CTF](http://secuinside.com/)
 * [Codegate CTF](http://ctf.codegate.org/html/Main.html?lang=eng)
 * [Boston Key Party CTF](http://bostonkeyparty.net/)
 * [ZeroDays CTF](https://zerodays.ie/)
 * [Insomni’hack](https://insomnihack.ch/)
 * [Pico CTF](https://picoctf.com/)
 * [prompt(1) to win](http://prompt.ml/) - XSS 挑战
 * [HackTheBox](https://www.hackthebox.eu/)

## General

 * [Hack+](http://hack.plus) - 获取最新 InfoSec 内容的智能机器人网络.
 * [CTFtime.org](https://ctftime.org/) - 关于 CTF（夺旗）的一切
 * [WeChall](http://www.wechall.net/)
 * [CTF archives (shell-storm)](http://shell-storm.org/repo/CTF/)
 * [Rookit Arsenal](https://amzn.com/144962636X) - OS RE 和 rootkit 开发
 * [Pentest Cheat Sheets](https://github.com/coreb1t/awesome-pentest-cheat-sheets) - 用于渗透测试的备忘单集合
 * [Movies For Hackers](https://github.com/k4m4/movies-for-hackers) - 每个黑客和赛博朋克都必须观看的精选电影列表.
 * [Roppers CTF Fundamentals Course](https://www.hoppersroppers.org/courseCTF.html)  - 旨在让学生尽快掌握 CTF 的免费课程. 教授加密、取证等所需的心态和技能. 全文可作为 [gitbook](https://www.hoppersroppers.org/ctf/).

## OS

## Online resources

 * [Security related Operating Systems @ Rawsec](https://inventory.raw.pm/operating_systems.html) - 安全相关操作系统的完整列表
 * [Best Linux Penetration Testing Distributions @ CyberPunk](https://n0where.net/best-linux-penetration-testing-distributions/) - 主要渗透测试分布的描述
 * [Security @ Distrowatch](http://distrowatch.com/search.php?category=Security) - 专门讨论、审查和了解开源操作系统最新信息的网站


## Post exploitation

## tools
* [empire](https://github.com/EmpireProject/Empire) - 用于 powershell 和 python 的后期开发框架.
* [silenttrinity](https://github.com/byt3bl33d3r/SILENTTRINITY) - 一种使用铁蟒绕过 powershell 限制的开发后工具.
* [PowerSploit](https://github.com/PowerShellMafia/PowerSploit) - 一个 PowerShell 后开发框架
* [ebowla](https://github.com/Genetic-Malware/Ebowla) - 制作环境键控有效载荷的框架

## ETC

 * [SecTools](http://sectools.org/) - 排名前 125 的网络安全工具
 * [Roppers Security Fundamentals](https://www.hoppersroppers.org/courseSecurity.html)  - 向初学者教授安全在现实世界中如何运作的免费课程. 学习安全理论并执行防御措施，以便更好地应对在线和现实世界中的威胁. 全文可作为 [gitbook](https://www.hoppersroppers.org/security/).
 * [Rawsec's CyberSecurity Inventory](https://inventory.raw.pm/)  - 关于网络安全的工具、资源、CTF 平台和操作系统的开源清单.  ([Source](https://gitlab.com/rawsec/rawsec-cybersecurity-list))
