# FullScreenDemo
基于fullpage插件开发的全屏页面demo

## 步骤
1. 引入jquery.fullPage.css文件
2. 引入jquery.js文件
3. 引入jquery.fullPage.js文件
4. 编写html模板
    `<div id="fullpage'">
        <div class="section">Some section</div>
        <div class="section">Some section</div>
        <div class="section">Some section</div>
        <div class="section">Some section</div>
    </div>`
5. 初始化
    `$(document).ready(function() {
        $('#fullpage').fullpage(paramsObj);
    })`
6. paramsObj参数的配置参考网站 <a href="http://fullpage.81hu.com/"></a>