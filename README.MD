审计规则是魔改一项非常重要的功能，但发现好多人都不知道怎么用。今天正好有人在群里发了这个规则，我就顺便写一下吧。  

## 具体规则  
禁用BT  
BitTorrent protocol  
数据包明文匹配  

禁止百度定位  
(api|ps|sv|offnavi|newvector|ulog.imap|newloc)(.map|).(baidu|n.shifen).com  
数据包明文匹配  

禁止360  
(.+.|^)(360|so).(cn|com)  
数据包明文匹配  

禁止邮件滥发  
(Subject|HELO|SMTP)  
数据包明文匹配  

屏蔽轮子  
感谢 烟雨阁 前辈网站  
感谢 Daniel Jack  
(.*.||)(dafahao|minghui|dongtaiwang|epochtimes|ntdtv|falundafa|wujieliulan).(org|com|net)  
数据包明文匹配  



屏蔽 BT（2）  
感谢 91yunbbs 用户 Hina  
(torrent|.torrent|peer_id=|info_hash|get_peers|find_node|BitTorrent|announce_peer|announce.php?passkey=)  
数据包明文匹配  

屏蔽Spam  
感谢 91yunbbs 用户 liangzhukun  
(JasonLee修改完善)  
(^.*@)(guerrillamail|guerrillamailblock|sharklasers|grr|pokemail|spam4|bccto|chacuo|027168).(info|biz|com|de|net|org|me|la)  

屏蔽迅雷  
感谢Ashe 提供  
(.?)(xunlei|sandai|Thunder|XLLiveUD)(.)  
数据包明文匹配  

可基本屏蔽掉迅雷的网站，并且在全局模式下会影响迅雷的下载能力  
