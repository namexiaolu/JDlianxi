# 京东网站模仿

本项目是模仿jd网站，思路是先写好html+css，力求做到完全一致。
在线查看 https://namexiaolu.github.io/JDlianxi/

## 设计框架

先总体规划好要用几个文件，目录怎么排。以下是我的目录 ↓

![1567126396045](/mdimg/1567126396045.png)

favicon.ico是网站的小图标，css中存放css，目前只写了base.css,包括每个页面相同的部分（头、脚）。之后会加上每个页面固定的css。fonts为iconfont存放的位置，用的阿里的图标。images存放网站用到的图片。

## 首页上边的广告条

大盒子中有小盒子，小盒子中存放广告图，在css中全局定义一个版心，我用的.w{}定义的，里边写宽，和剧中(magng 0 auto),右上角的小叉号用的阿里的iconfont，定位定到那里。并加上class，以备之后js用。

## 导航栏

## 购物车
右上角的小红色圆圈，用定位。

## 导航栏信息（navitems)
用三个ul分成三份，每个ul的margin-left 30；
ul>li*4>a
left 200
bottom 0
height 40
line-height 40
font-weight:700; 字体加粗的意思。
* 复制文字小技巧
    复制三个 然后 按住alt 选三个位置，粘贴，那么这三个复制的文字就会依次粘贴到这三个位置，很棒。
* 量字体高度的方法，可以先量明显一侧的高度，然后把这一侧的高度复制到另一侧，再量整个的高度，在css中直接写height和ling-height就行了。

### 小竖条 的设计
设置宽高、外边框。

## 底部footer
h560
分为三栏
    * 通栏+版心
        h100;
        底部搞一个线
    * 版心
    * 版心
版心里边w225
h42


### 精灵图的用法
 * 先写上bg url
 * bg-position: x轴 y轴;

### 交集选择器
    ```html
    <div class = "aaa">
        11111
        <div class = "aaa">
            22222
            </div>
    </div>
    ```
    ```css
    div.a{
        color:red;
    }
    ```


