域名依然是eu.org免费域名! 是注册的时候 必须要更换身份和所在地。
同时兴趣爱好，目的全部要改变。他们才会认为不是一个人!!!



登录邮箱

cdn

cdn@redalert.eu.org


dns

域名@redalert.eu.org




使用的域名


domain-ns.eu.org(使方案1)



domain-dns.eu.org(使用方案2)





重点是这两个

accelerate.eu.org（这个作网站加速 不能用第二个方案。只能用第一个方案!）


dnsaccelerate.eu.org(使用方案2)



权威服务器只能添加六条记录。无法使用多家做负载平衡。

方案1

cloudflare.com本身的dns，不开启cdn加速而已!
这个方案虽然简单，容易上手。但存在丢弃权威服务器
数据包实现阻断。


方案2

首先获取各大智能解析服务商的IP地址

然后在智能解析服务商哪里添加a记录（智能解析服务商ip地址）

然后把权威服务器指向自己的域名。


如果使用这个方案，需要的域名!

VoxAkuma.eu.org (方案1)

LucaKaneshiro.eu.org(方案1)


重点是这三个(全部使用方案2)

AM6MHZ.eu.org

AM12MHZ.eu.org

AM701KHZ.eu.org

为了安全起见，需要两手都给准备!!!!! 账号信息发到
http://github.com/underground






#作用就是让公共dns作为跳板。公共dns不但速度快，而且节点多。
可以大大增加网站的解析速度。可以阻止中共的防火墙阻断dns。
 在内地搭建一个服务器。在内地开放53端口 然后域名解析找到这个ip上。 
这个服务器上连接VPN 直接连接境外网络。然后让公共dns缓存。
可以破解防火墙阻断域名权威服务器被阻断。






ns1

这里使用阿里云dns

223.5.5.5

223.6.6.6

ns2

这里使用dnspod

119.29.29.29

119.28.29.28

182.254.116.116（可以大ttl）

182.254.118.118（可以大ttl）

ns3

这里使用sdns

1.2.4.8（联通可以大ttl）

210.2.4.8

ns4

这里使用dnspai/3721（360dns）

101.226.4.6

218.30.118.6

123.125.81.6

140.207.198.6

ns5

这里使用百度dns

180.76.76.76

ns6

这里使用onedns

117.50.11.11

52.80.66.66

117.50.10.10

52.80.52.52

117.50.60.30

52.80.60.30

注意 严格限制解析数量。

ns7

这里使用114dns

114.114.114.114

114.114.115.115

114.114.114.110

114.114.115.110

114.114.114.119

114.114.115.119


注意 严格限制解析数量。


