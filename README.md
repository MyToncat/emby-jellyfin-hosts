## emby-jellyfin-hosts
>适用于emby/jellyfin刮削hosts专用的远程订阅

1.在`/etc/`目录下新建`myhosts`文件，粘贴[最新](https://raw.githubusercontent.com/CodeFishK/emby-jellyfin-hosts/main/remote-submit.host)的规则并保存；  

2.在OpenWRT的`网络→DHCP/DNS→HOSTS和解析文件→额外的HOSTS文件`添加hosts文件路径`/etc/myhosts`即可；  
![image](https://user-images.githubusercontent.com/38446347/183243476-bbffaf0f-645d-4df9-95f9-814db44029b5.png)
