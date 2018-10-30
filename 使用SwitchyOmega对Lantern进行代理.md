# 写在前面

电脑使用Lantern的时候，有时候会出现一些问题，像Winodos里的应用商店会打不开，网易云音乐的歌曲会不能播放之类的。是因为Lantern管理了系统的全部流量，在这里有冲突。所以我们可以只让Lantern代理浏览器就行了。
# 方法
## 安装SwitchyOmega

这部分就不赘述，我以Chrome为例，在应用商店里搜索SwitchyOmega安装即可。

安装后会自动打开选项页面，我简单的就直接在默认的页面设置即可了。

## 设置SwitchyOmega

### 获取Lantern代理服务器地址

打开Lantern，在“设置”——“高级设置”里看到服务器的地址，然后复制填到SwitchyOmega的代理服务器里

![](https://raw.githubusercontent.com/JDNew/Writing/master/image/20180128100744007.png)

![](https://raw.githubusercontent.com/JDNew/Writing/master/image/20180128100818399.png)

然后点击左下方的“应用选项”（此时应该是绿色的）

### 切换设置的选项

接下来就是在刚才Lantern的那个设置页面，取消勾选“管理系统代理”。

然后点击我们的SwitchyOmega拓展插件，点击切换到我们刚才设置的代理即可：

![](https://raw.githubusercontent.com/JDNew/Writing/master/image/20180128101209829.png)