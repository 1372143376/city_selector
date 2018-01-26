## 省份/城市/区县定位选择器 ##

 <br/>
 
>  💨🚀 微信小程序，一行代码引入的省份/城市/区县定位选择器的库

 <br/>

### 主要功能 ###
* 自动定位 城市、区县（也支持手动重新定位）
* 手动 汉字、拼音搜索 城市，支持搜索数量335个，覆盖地级市
* 亦可通过 侧边栏 选择，城市按拼音首字母排列
* 选择好城市后，自动显示 辖下区县




### 集成说明 ###
* 将libs文件夹拷贝至您的小程序项目根目录
* 在您的项目根目录 app.json 里的 pages 数组里增加一行 <code>"libs/citySelector/switchcity/switchcity"</code>
* 打开项目里的<code>/libs/citySelector/config.default.js</code>文件
* 将其中的key改为自己的腾讯地图key（申请快速并免费）<a href="http://lbs.qq.com/console/key.html">点击立即打开腾讯地图Key申请页面</a>

### 快速使用 ###

>在您要打开选择器地方用navigator组件，将url设置为<code>"/libs/citySelector/switchcity/switchcity"</code>

>或者，在 JS 代码里直接使用 wx.navigateTo 打开地区选择器
<pre>
<code>
wx.navigateTo({
    url: '/libs/citySelector/switchcity/switchcity',
});
</code>
</pre>
> 两种方法二选一即可
 

### 获取返回数据 ###

> 在switchcity页选择完地区之后，点击会自动返回，并且将省份/城市/区县数据设置到本页面的<code> this.data.address </code> 内

###### 如图所示 ######
 <img width="60%" src="https://ws4.sinaimg.cn/large/006tNc79ly1fns2fxjjwtj314o0gsmz8.jpg"/>

###### 修改颜色样式 ######
* 在libs文件夹搜索 #c60a0d ，替换为您想要的颜色值即可

### 功能演示 ###

##### Gif有点卡，不过实际操作起来是超级流畅的 

 <img src="https://ws3.sinaimg.cn/large/006tNc79ly1fns1qa2ztxg30bs0jrwxs.gif"/>
 
 
 <br/><br/>
### 🤗 🤗 🤗 如果对您有帮助，请star ###
 <br/> <br/> <br/> <br/>