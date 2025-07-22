# cmliuedge
edgetunnel参考cmliu大佬的项目并混淆
大佬项目地址：https://github.com/cmliu/edgetunnel
变量名：
1,UUID - 可输入任意值(非UUIDv4标准的值会自动切换成动态UUID)
2,KEY - 动态UUID秘钥，使用变量KEY的时候，将不再启用变量UUID
3,ADD - 本地优选TLS域名/优选IP(支持多元素之间,或换行作间隔)
4,ADDAPI - 优选IP的API地址(支持多元素之间,或 换行 作间隔)
5,ADDCSV - iptest测速结果(支持多元素, 元素之间使用,作间隔)
6,SUB - 优选订阅生成器域名
7,SUBAPI - clash、singbox等 订阅转换后端,例SUBAPI.cmliussss.net
