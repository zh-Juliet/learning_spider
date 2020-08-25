## 简介  
此项目主要分为三个部分  
* 爬虫案例  
对一些网站的数据进行爬取，标记出 难度和要点  
* 辅助工具/脚本制造  
尝试制作各种爬虫工具/脚本  
* web网站  
尝试去接入各种不同的验证码，尝试自行通过  
根据反反爬经验设置各种难点，研究前端知识  


## 已完成的内容 - 目前进度估计 1%

## 爬虫案例  
<table>
    <tr><th colspan="5">案例列表</th></tr>
    <tr>
        <th>难度</th>
        <th>内容</th>
        <th>信息</th>
        <th>方式</th>
        <th>难点</th>
    </tr>
    <tr>
        <td>基础</td>
        <td><a href="https://github.com/RecluseXU/learning_spider/tree/master/example/0_Basic_usage_of_the_library" target="_blank">各类库的简单用法</a></td>
        <td>基本使用方法</td>
        <td>查看文档</br>编写demo</td>
        <td></td>
    </tr>
    <tr>
        <td rowspan="6">入门</td>
        <td>
        <a href="https://github.com/RecluseXU/learning_spider/tree/master/example/1_%E5%85%A5%E9%97%A8_%E7%8C%AB%E7%9C%BC%E7%94%B5%E5%BD%B1%E6%8E%92%E8%A1%8C%E6%A6%9Ctop100" target="_blank">猫眼电影排行榜top100</a></td>
        <td>静态网页</td>
        <td>模拟http</td>
        <td></td>
    </tr>
    <tr>
        <td><a href="https://github.com/RecluseXU/learning_spider/tree/master/example/1_%E5%85%A5%E9%97%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%95%86%E5%9F%8E%E6%90%9C%E7%B4%A2%E9%A1%B5" target="_blank">亚马逊中国商城搜索页</a></td>
        <td>静态网页</td>
        <td>模拟http</td>
    </tr>
    <tr>
        <td>
        <a href="https://github.com/RecluseXU/learning_spider/tree/master/example/1_%E5%85%A5%E9%97%A8_%E4%BB%8A%E6%97%A5%E5%A4%B4%E6%9D%A1%E6%90%9C%E7%B4%A2%E7%BB%93%E6%9E%9C" target="_blank">今日头条搜索结果</a></td>
        <td>动态网页</td>
        <td>模拟http</td>
        <td></td>
    </tr>
    <tr>
        <td>
        <a href="https://github.com/RecluseXU/learning_spider/tree/master/example/1_%E5%85%A5%E9%97%A8_%E5%BE%AE%E5%8D%9A%E7%A7%BB%E5%8A%A8%E7%AB%AF%E7%94%A8%E6%88%B7%E5%8A%A8%E6%80%81%E4%BF%A1%E6%81%AF" target="_blank">
        微博移动端用户动态信息</a></td>
        <td>动态网页</td>
        <td>模拟http</td>
        <td>since_id参数的所在地</td>
    </tr>
    <tr>
        <td>
        <a href="https://github.com/RecluseXU/learning_spider/tree/master/example/1_%E5%85%A5%E9%97%A8_Bilibili%E8%A7%82%E5%AF%9F%E8%80%85%E8%A7%81%E9%BD%90%E6%8C%87%E6%95%B0" target="_blank">
        Bilibili观察者 见齐指数</a></td>
        <td>动态网页</td>
        <td>模拟http</td>
        <td>被压缩的 指数数据 的还原</td>
    </tr>
    <tr>
        <td>
        <a href="https://github.com/RecluseXU/learning_spider/tree/master/example/1_%E5%85%A5%E9%97%A8_%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E6%BB%91%E5%9D%97%E9%AA%8C%E8%AF%81%E7%A0%81" target="_blank">最简单的滑块验证码</a></td>
        <td>动态网页</td>
        <td>模拟浏览器</td>
        <td>滑块移动</td>
    </tr>
    <tr>
        <td rowspan="5">简单</td>
        <td>
        <a href="https://github.com/RecluseXU/learning_spider/tree/master/example/2_%E7%AE%80%E5%8D%95_%E6%9F%90%E8%B7%AF%E7%94%B1%E5%99%A8%E5%AF%86%E7%A0%81%E5%8A%A0%E5%AF%86%E6%96%B9%E6%B3%95" target="_blank">某路由器密码加密方法</a></td>
        <td>单个js文件</td>
        <td></td>
        <td>寻找加密函数</td>
    </tr>
    <tr>
        <td>
        <a href="https://github.com/RecluseXU/learning_spider/tree/master/example/2_%E7%AE%80%E5%8D%95_%E6%97%A0%E9%99%90debugger" target="_blank">无限debugger处理</a></td>
        <td>动态网页</td>
        <td>reres</td>
        <td>反调试</td>
    </tr>
    <tr>
        <td><a href="https://github.com/RecluseXU/learning_spider/tree/master/example/2_%E7%AE%80%E5%8D%95_AAEncode%E8%A7%A3%E6%B7%B7%E6%B7%86" target="_blank">AAEncode解混淆</a></td>
        <td>动态网页</td>
        <td>devtool</td>
        <td>编码混淆</td>
    </tr>
    <tr>
        <td><a href="https://github.com/RecluseXU/learning_spider/tree/master/example/2_%E7%AE%80%E5%8D%95_CSS%E5%85%83%E7%B4%A0%E7%BB%9D%E5%AF%B9%E5%AE%9A%E4%BD%8D%E5%8F%8D%E7%88%AC" target="_blank">CSS元素绝对定位反爬</a></td>
        <td>静态网页</td>
        <td>devtool</td>
        <td>还原顺序</td>
    </tr>


</table>

## 工具/脚本制造  
<table>
    <tr><th colspan="4">工具/脚本制造</th></tr>
    <tr>
        <th>附属于</th>
        <th>内容</th>
        <th>信息</th>
    </tr>
    <tr>
        <td>Selenium</td>
        <td>Auto DL ChromeWebDriver</td>
        <td>获知已安装的Chrome版本信息，去<a href="http://chromedriver.storage.googleapis.com/index.html">google</a>下载最符合版本的Selenium Chrome Web Driver，使得Selenium能正常运行<br>(虽然实际上最好的解决方法不是这样做，而是在服务器上下一个docker，拉取Image，然后部署上)</td>
    </tr>
</table>

## 基础练习网站  
<table>
    <th colspan="4">案例</th>
    <tr>
        <th>类型</th>
        <th>难度</th>
        <th>名称</th>
        <th>信息</th>
    </tr>
    <tr>
        <td rowspan="2">滑块验证</td>
        <td>入门</td>
        <td>最简单的滑块验证</td>
        <td>只要拖动滑块，滑到尽头就可以通过，不存在任何检测</td>
    </tr>
    <tr>
        <td>简单</td>
        <td>SliderCaptcha</td>
        <td>默认设置部署，存在基本的人机验证，匀速拉动/直线拉动不会通过验证</td>
    </tr>
</table>

<table>
    <tr><th colspan="4">技术应用</th></tr>
    <tr>
        <th></th>
        <th>使用</th>
        <th>信息</th>
    </tr>
    <tr>
        <td>规范</td>
        <td>RESTful</td>
        <td>规范的API，规范的响应</td>
    </tr>
    <tr>
        <td rowspan="5">前端</td>
        <td>JQuery 2.2.4</td>
        <td>一个快速、简洁的JavaScript框架</td>
    </tr>
    <tr>
        <td>Materialize</td>
        <td>基于Material Design的前端响应式框架</td>
    </tr>
    <tr>
        <td>twitter-bootstrap 3.4.1</td>
        <td>Twitter推出的一个用于前端开发的开源工具包</td>
    </tr>
    <tr>
        <td>font-awesome 4.7.0</td>
        <td>一套图标字体库和CSS框架</td>
    </tr>
    <tr>
        <td>metisMenu 3.0.6</td>
        <td>Vanilla-JS 折叠菜单插件</td>
    </tr>
    <tr>
        <td>CDN</td>
        <td>bootcdn.cn</td>
        <td>免费的前端开源项目 CDN 加速服务</td>
    </tr>
    <tr>
        <td rowspan="4">后端</td>
        <td>Flask 1.1.2</td>
        <td>Python轻量级web框架</td>
    </tr>
    <tr>
        <td>Flask-RESTful 0.3.8</td>
        <td>Flask-RESTful 一个 支持快速创建REST APIs的 Flask插件</td>
    </tr>
</table>

2020年8月5日18:33:19
