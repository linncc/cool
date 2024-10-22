## 项目名称
> 仓库管理软件  
> 公众号《多多影音》

## 请勿用于任何盈利目的及商业演示场合，免费收集汇总！

多仓接口： https://cdn09022024.gitlink.org.cn/leevi0321/cool/raw/branch/main/room.json 
多线路接口： https://cdn09022024.gitlink.org.cn/leevi0321/cool/raw/branch/main/duo.json 


打赏VIP群加入方式：
https://www.gitlink.org.cn/api/leevi0321/cool/raw/%E5%B0%8F%E7%A8%8B%E5%BA%8F.png?ref=main
## 单线路、多线路、单仓、多仓解释
* 单线路（接口）：适用于一切基于Box壳子二开的软件；

> 包含多个站源：如豆瓣、南瓜、玩偶、厂长等等，所以一条单线路包含多个站源。


* 多线路：适用于影视、521影视、catbox、jade、多仓及魔改版（如Player）、easybox、影迷等支持；

> 包含多个单线路，如果放在多仓软件里，也可以叫单仓。

> 多线路中可包含几个或者无数个线路，放在多仓软件中仅显示为一个仓库


* 多仓：适用于多仓及魔改版（如Player）、easybox、影迷；

> 包含多个单仓，每个单仓里同时包含多条线路，每个线路里又包含多个站源。

>多仓的目的主要是为了区分线路的不同，快慢以及有效性等，比如长期有效稳定的线路放在同一个仓库，其余线路放在另外的仓库，比如加载快的放在一个仓库里。



## 接口、线路、仓库之间的关系

* 站源>>>>>>单线路>>>>>>多线路（单仓）>>>>>>多仓

>接口：一般说某个接口都是指单线路，也叫线路、接口，但不固定指单线路，比如多仓接口，也被叫做接口。

> 由此可见，多仓接口里包含了多个仓库，每个仓库里又包含了多个线路，所以有了多仓接口，你就拥有了几十甚至更多的单线路，这些单线路不可能全部同时都挂掉。

## 多仓写法
{
"storeHouse": [
{"sourceName":"仓库名字1","sourceUrl":"多仓接口地址1"},
{"sourceName":"仓库名字2","sourceUrl":"多仓接口地址2"},
{"sourceName":"仓库名字3","sourceUrl":"多仓接口地址3"},
{"sourceName":"仓库名字4","sourceUrl":"多仓接口地址4"}
]}

## 多线路（单仓）写法
{
"urls": 
    [
        {
            "url": "https://git.acwing.com/iduoduo/orange/-/raw/main/jsm.json",
            "name": "🚀PG线路"
        }, 	
        {
            "url": "http://ok321.top/ok",
            "name": "🚀OK线路"
        }, 		
        {
            "url": "http://www.饭太硬.com/tv",
            "name": "🚀饭太硬线路"
        },          	
        {
            "url": "https://gitlab.com/duomv/dzhipy/-/raw/main/index.json",
            "name": "🚀道长线路"
        }
	]
}	
## 此项目长期维护更新，保证其中接口的有效联通率，Fork并不会自动同步项目内容，如要保持持续更新，请直接使用本项目链接。