# w_2113
网站访客大数据腾讯地图API展示源码
<br/></br>
[下载地址](https://www.uuid2.com/2113.html "下载地址")
<br/></br>
<h3>源码简介：</h3>
<p>一款基于腾讯地图API开发的网站访客大数据展示源码，具体大家看效果图就明白是什么东西了。<p>
<p>本程序只支持 PHP，PHP > = 7.0，网站程序有全局统一调用一个公共函数文件。<p>
<p>1. 解压文件，把 map 文件夹拖到桌面<p>
<p>2. 修改 /map/map.php 头部的服务器信息以及 KEY 信息<p>
<p>3. 把 map 文件夹上传到你的网站根目录<p>
<p>4. 在网站核心文件中代码顶部添加以下代码：<p>
<p>require (dirname(__FILE__) . '/map/map.php');<p>
<p>5. 网站核心文件，每次访问都会引用的文件<p>
<p>6. 然后，打开你的网站/map 刷新几次就行了<p>
<p>注：网站核心函数文件一般都是 config.php 或 funtion.php<p>
<p>如果地图无法显示，打开谷歌内核浏览器的控制台 F12，查看错误信息。<p>
<p>错误信息：XX 数据错误<p>
<p>解决办法：在当前环境 php.ini 的配置文件中修改：<p>
<p>搜索 serialize_precision 把值改成 -1 即可。<p>
<p>保存后重启 PHP 即可！<p>
<h3>截图：</h3>
<img src="https://www.uuid2.com/wp-content/uploads/img/202205/919830f987.jpg" alt="网站访客大数据腾讯地图API展示源码"><img src="https://www.uuid2.com/wp-content/uploads/img/202205/919830f515.png" alt="网站访客大数据腾讯地图API展示源码"><img src="https://www.uuid2.com/wp-content/uploads/img/202205/bd4b144306.png" alt="网站访客大数据腾讯地图API展示源码">
