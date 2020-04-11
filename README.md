## 实验报告 ##
<p><small>来自19302010069_项心叶</small><br>
<small><a href="https://github.com/Sherlock-Watson/">我的GitHub地址</a></small><br>
<small><a href="https://sherlock-watson.github.io/My_Travel/">我的Gitpages地址</a></small>
</p>

### 1.项目完成情况 ###
#### 1.1首页 ###
<p>
首页由导航栏、一张很大的图、图片与缩略文字、页脚组成
</p>
<p>
首页的导航栏和其他页面的导航栏有所不同，虽然首页、搜索、
浏览、我的页面这些元素和其他页面在相同的位置，但是首页的
导航栏是透明的，我采用背景图片的方式使得文字漂浮在大图的
上方。My Travel是这个网站的名称，图上的大字使得首页特点
十分鲜明。
</p>
<p>
首页下面的部分是缩略图和带有省略号的介绍文字，省略号的
实现方式为：
</p>

       overflow:hidden;
       text-overflow:ellipsis;
       white-space: nowrap;
       
<p>
这和后面几个界面的实现方式不一样，后面几个界面只有在Chrome
等支持<code>-webkit-</code>的浏览器中才能正常显示。
</p>
<p>
采用四列布局，
</p>
<p>
缩略图使用的非正方形图片，具体实现方式见下面关于Bonus实现部分
的介绍。
</p>