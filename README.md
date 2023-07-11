# VtuberMonitor
一个网页版的虚拟主播监控室，方便作者的朋友看VTB。

基于[https://github.com/DanKE123abc/VtuberMonitor](https://github.com/DanKE123abc/VtuberMonitor)修改而成 感谢源码

体验地址：[https://dd.1919.cf/](https://dd.1919.cf/)


### #添加虚拟主播

###### 1. 打开/foot.html

###### 2. 在如下代码中添加自己爱看的虚拟主播

```
<select name="zhubo" id="zhubo" onchange="change()">
            <!--
                这里是蛋壳爱看的虚拟主播，你可以根据你的爱好自行修改
                格式：
                <option value="直播间号">主播名称</option>
            -->
            <option value="null">请选择直播间</option>
            <option value="2233">这里是一个直播间示例</option>
        </select>
```
