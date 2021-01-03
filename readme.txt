1、使用icon图标
    1）首先把favicon.icon这个图标放到根目录下
    2）在html里面，head之间引入代码
    <link rel="shortcut icon" href="favicon.ico" type="image/x-icon">


2、制作icon图标
    1）把想要的切成图片
    2）把图片转换为ico图标，第三方网站 https://www.bitbug.net/

3、网站优化三大标签--在head里
SEO 搜索引擎优化
title description keywords--三大标签

    1）title建议：
    首页标题：网站名（产品名）-网站的介绍
    例如：
    品优购-综合网购首选-正品低价、品质保障、配送及时、轻松购物
        <title>品优购-综合网购首选-正品低价、品质保障、配送及时、轻松购物</title>


    2）description：不能超过100个字
    <meta name="description" content="品优购PY.COM-专业的综合网上购物商城,
        销售家电、数码通讯、电脑、家居百货、服装服饰、母婴、图书、食品等数万个品牌优质商品.
        便捷、诚信的服务，为您提供愉悦的网上购物体验!"/>

    3）keywords关键字
        <meta name="keywords" content="网上购物，网上商城，手机，笔记本..."/>

4、字体图标
使用流程：
    1）推荐字体包网站-下载
    https://icomoon.io/
    https://www.iconfont.cn/

    2）引入字体
       a、解压-把压缩包中的fonts拷贝到根目录下
       b、在html标签里添加结构-打开demo.html-在图标后面复制
          <span></span>
       c、打开压缩包中的style.css把以下代码引入
        @font-face {
            /* 1、字体名称要注意 icomoon */
            font-family: 'icomoon';
            /* 2、一定要注意路径问题 */
            src: url('fonts/icomoon.eot?odlblp');
            src: url('fonts/icomoon.eot?odlblp#iefix') format('embedded-opentype'),
                url('fonts/icomoon.ttf?odlblp') format('truetype'),
                url('fonts/icomoon.woff?odlblp') format('woff'),
                url('fonts/icomoon.svg?odlblp#icomoon') format('svg');
            font-weight: normal;
            font-style: normal;
            font-display: block;
        }
        d、给盒子定义字体
        span {
            font-family: 'icomoon';
        }
     3)追加字体图标
       a、原来压缩包里面的json文件--打开icomoon网页-import icon 上传json文件
       b、重新选择-下载-替换fonts下的文件

5、网站分析
   1）header-shortcut快捷导航