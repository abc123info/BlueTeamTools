# BlueTeamTools
蓝队分析工具箱by:ABC_123
"蓝队分析研判工具箱"就是把我平时写的蓝队小工具集合起来形成的，重点解决蓝队分析工作中的一些痛点问题。

2024.07.24 更新IP地址查询库为最新版本，查询IP物理归属地更精确。

2024.07.18 修正冰蝎、哥斯拉、天蝎解密后中文乱码问题，可以手工选择相应编码进行切换。

2024.07.08 修复冰蝎webshell计算key功能得到的值非16位的bug(存在的md5前导零bug)。

2024.06.15 增加对ip地址列表批量查地址功能。

2024.06.14 增加对天蝎webshell的Java、PHP、NET、ASP的解密。

2024.06.14 增加对16进制hex编码的内存马反编译功能。

2024.05.29 增加对哥斯拉3.x~4.x请求包、返回包的解密结果生成二进制文件功能，解决流量中掺杂附件的问题。

2024.05.28 修复"网空资产测绘"功能的多个bug，添加对域名搜索功能。

2023.10.21 修正"IP地址处理"功能的192.168.1.1/16, 192.168.10.1/8不能解析的bug。

2023.10.18 更新"常用网址"的url列表，并重新整理。 

2023.10.14 识别哥斯拉webshell的流量解密结果，发现class文件格式，输出文件名GodzillaDecode.class。

2023.10.09 解决苹果Mac系统下的软件界面模糊问题。

2023.10.06 对"IP/端口连接分析"功能添加IPv6的支持，支持查询IPv6的物理地址。

2023.10.02 更新哥斯拉webshell的C#流量解密功能，ASP流量解密功能，添加字符串反转功能。

2023.10.01 更新哥斯拉webshell的Java流量解密功能、PHP流量解密功能。

2023.09.11 更新Xml转JSON、JSON转Xml功能。

2023.09.08 更新MySQL、SQLServer、Oracle、PostgreSQL、Hive数据库语句的格式化功能。

2023.09.06 更正"网空资产测绘"功能Hunter界面的显示问题。

2023.08.28 添加Base64+Gzip解码功能，用于特殊情况下解码出Java反序列化数据包。

2023.08.26 添加VirusTotal搜索功能，添加文件哈希校验功能。

2023.08.25 添加Hunter、Censys搜索功能。

2023.08.24 添加微步、Quake、Zoomeye搜索功能。

2023.08.06 添加Fofa、Shodan搜索功能。

2023.08.05 添加蓝队分析的常用网址。

2023.08.04 对各种报错异常进行抓取，并且显示出来。

2023.08.03 添加JavaScript、CSS、XML、JSON的格式化功能。

2023.07.25 解决Swing界面在不同JDK缩放问题。

2023.07.22 添加蓝队反制功能，获取图片的EXIF信息，包括经纬度位置信息、手机型号等。

2023.07.21 添加UTF-7编码、解码功能，更换离线IP数据库为最新版本。

2023.07.20 对每一个文本框添加右键撤销功能。

2023.07.20 添加URL全编码功能。

2023.07.19 对所有的文本输入框添加右键复制、粘贴、全选、删除功能。

2023.07.16 更换皮肤，使其兼容JDK8-JDK20版本。

2023.07.16 添加IP批量处理功能。

2023.07.15 将工具所有的依赖jar包更换为兼容JDK8-JDK20版本。

2023.04.28 新增Java代码格式化功能。

2023.04.10 经过反复测试，为软件添加皮肤，解决界面美观问题。

2023.04.02 新增对netstat -an结果中的国外地址进行高亮显示功能。

2023.03.21 新增Java反序列化数据包分析功能。

2023.03.15 新增在jar中搜索关键类的方法，用于排查web应用的lib目录中可能被注入的class不死马

2023.03.15 重构内存马反编译功能，当然也可以作为反编译工具使用。

2023.03.13 新增对文件的各种编码/解码功能。

2023.03.12 重新更改编码/解码功能界面，使用更方便。

2023.03.12 新增Gzip解码及反编译功能。

2022.11.06 优化BECL编码功能。

2022.11.05 更正Java反编译功能。

2022.11.04 将Base64编码功能统一更换为第三方jar包，使其通用性更强。

2022.11.03 加入对HEX编码文件功能。

2022.10.31 加入Java代码高亮显示功能。

2022.10.30 加入Java反编译功能，调用Fernflower、CFR、Procyon、JD-GUI共计4款主流的Java反编译功能。

2022.10.29 加入对Base64解码后的class文件的反编译功能。

2022.10.28 优化"端口连接分析"功能，提升查询IP的物理地址速度，秒出结果。

2022.10.26 加入$$BECL$解码的功能，并对class文件进行反编译。

2022.10.24 更正Log4j2反序列化Payload的反混淆功能，使其适用更复杂的混淆解密。

2022.05.04 开始对此工具进行大幅度更新。

2020.05.25 完成第一个版本，完成Shiro反序列化数据包解密功能。

![image](https://github.com/abc123info/BlueTeamTools/assets/143333826/85e2c331-3939-4d22-a052-b1fd5c999d75)

![c333](https://github.com/abc123info/BlueTeamTools/assets/143333826/941c8a99-e42b-4671-ac63-67b3e7c10746)

![image](https://github.com/abc123info/BlueTeamTools/assets/143333826/001c52f8-37aa-4e69-83ff-ac7d921a6d6e)

![image](https://github.com/abc123info/BlueTeamTools/assets/143333826/4ccfca83-e63c-481f-bccf-c813386986d3)

![b666](https://github.com/abc123info/BlueTeamTools/assets/143333826/19d97cc2-cb1d-42d0-845d-9d884b63e3fd)

![b777](https://github.com/abc123info/BlueTeamTools/assets/143333826/9a75f3dd-961b-410c-88a7-a6cfa2465949)
