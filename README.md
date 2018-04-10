<!doctype html>
<html lang="{{ site.lang | default: "en-US" }}">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">

{% seo %}
    <link rel="stylesheet" href="{{ '/assets/css/style.css?v=' | append: site.github.build_revision | relative_url }}">
    <script src="https://code.jquery.com/jquery-1.12.4.min.js" integrity="sha256-ZosEbRLbNQzLpnKIkEdrPv7lOy9C27hHQ+Xp8a4MxAQ=" crossorigin="anonymous"></script>
    <script src="{{ '/assets/js/respond.js' | relative_url }}"></script>
    <!--[if lt IE 9]>
      <script src="//html5shiv.googlecode.com/svn/trunk/html5.js"></script>
    <![endif]-->
    <!--[if lt IE 8]>
    <link rel="stylesheet" href="{{ '/assets/css/ie.css' | relative_url }}">
    <![endif]-->
    <meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no">

  </head>
  <body>
      <div id="header">
        <nav>
          <li class="fork"><a href="{{ site.github.repository_url }}">View On GitHub</a></li>
          {% if site.show_downloads %}
            <li class="downloads"><a href="{{ site.github.zip_url }}">ZIP</a></li>
            <li class="downloads"><a href="{{ site.github.tar_url }}">TAR</a></li>
            <li class="title">DOWNLOADS</li>
          {% endif %}
        </nav>
      </div><!-- end header -->

    <div class="wrapper">

      <section>
        <div id="title">
          <h1>{{ site.title | default: site.github.repository_name }}</h1>
          <p>{{ site.description | default: site.github.project_tagline }}</p>
          <hr>
          <span class="credits left">Project maintained by <a href="{{ site.github.owner_url }}">{{ site.github.owner_name }}</a></span>
          <span class="credits right">Hosted on GitHub Pages &mdash; Theme by <a href="https://twitter.com/michigangraham">mattgraham</a></span>
        </div>

        {{ content }}

      </section>

    </div>

    {% if site.google_analytics %}
      <script>
        (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
        (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
        m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
        })(window,document,'script','//www.google-analytics.com/analytics.js','ga');
        ga('create', '{{ site.google_analytics }}', 'auto');
        ga('send', 'pageview');
      </script>
    {% endif %}
  </body>
</html>

### Phantom GPS是什么
![product1.png](http://upload-images.jianshu.io/upload_images/5872815-dc2dc69e4028d067.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)<br>
（2017年4月，没有外壳的产品原型）

PhantomGPS是iOS设备的外置GPS，用于修改手机的地理位置，方便程序员调试程序所用。
### 支持哪些设备
支持使用lightning接口（16pin小口USB）的iPhone、iPad、iPod<br>
支持iOS 8.x、9.x、10.x、11.x<br>
目前支持最新的版本是iOS11.3（15E216)，Beta版本未测试。

### 使用方法、操作手册
app安装分为两步：<br>
1. 从 app store下载TestFlight。<br>
2. 从邮件里获取兑换码，输入到TestFlight中。<br>
更详细的步骤参考：[app安装方法](https://gitee.com/phantomgps/codes/2xhf935ukc84zilov1asd31/raw?blob_name=%E4%BB%8ETestFlight%E4%B8%8B%E8%BD%BDPhantomGPS.pdf) 和[使用方法](https://gitee.com/phantomgps/codes/2xhf935ukc84zilov1asd31/raw?blob_name=PhantomGPS%E4%BD%BF%E7%94%A8%E6%8C%87%E5%AF%BC.pdf) <br>

### 演示视频
[PhantomGPS操作演示](http://player.youku.com/embed/XMzI2NzQ1NzEyOA==) （录屏）

[未越狱手机如何在国内玩原版Pokemon Go](http://player.youku.com/embed/XMjcxMjE0MjYzNg==)(拍摄）

[如何实时修改微信位置](http://player.youku.com/embed/XMjcwODc2NzAzNg==)(拍摄）

### 如何购买
**外设**需要购买,通过快递才能到你手上，不是软件。<br>
购买链接：[微店](http://weidian.com/i/2258146475&ifr=itemdetail&wfr=c)<br>
购买时备注邮箱地址，用于获取苹果发送的测试邀请邀请邮件，从TestFlight下载App。<br>
一个设备只发送一个邀请。多个手机共用设备的情况，用相同apple id登录，再下载TestFlight即可以安装。<br>

### 常见问题、交流
[如何使用TestFlight安装软件](https://jingyan.baidu.com/article/63f23628276e1d0209ab3d10.html)<br>
[其他常见问题](https://github.com/phantomgps/phantomgps.github.io/blob/master/faq.md)

QQ群：612428052<br>
![rqcode.png](http://upload-images.jianshu.io/upload_images/5872815-efba5722342dc399.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
