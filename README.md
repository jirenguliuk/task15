<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>JS Bin</title>
  <style>
@font-face {
  font-family: 'iconfont';  /* project id 299052 */
  src: url('//at.alicdn.com/t/font_fpzo6px3tjpuv7vi.eot');
  src: url('//at.alicdn.com/t/font_fpzo6px3tjpuv7vi.eot?#iefix') format('embedded-opentype'),
  url('//at.alicdn.com/t/font_fpzo6px3tjpuv7vi.woff') format('woff'),
  url('//at.alicdn.com/t/font_fpzo6px3tjpuv7vi.ttf') format('truetype'),
  url('//at.alicdn.com/t/font_fpzo6px3tjpuv7vi.svg#iconfont') format('svg');
}
#icon {
  font-family: iconfont !important;
  font-size: 48px;
  font-style: normal;
  color: #1296db;
  border-radius: 50%;
  background-color: black;
  display: inline-block;
  padding: 50px;
  font-weight: 700;
}
.nav  a:hover {
  color: #fed136;
}
* {
  margin: 0;
  padding: 0;
}


a {
  text-decoration:none;
}
.nav {
  position: fixed;
  top: 0;
  left: 0;
  background: rgba(0,0,0,.5);
  height: 70px;
  line-height: 80px;
  width: 100%;
  z-index: 100;
}
 .name {
  margin: 0 60px;
  display: block;
  float: left;
}
.container ul li {
  list-style: none;
  display: inline-block;
  float: left;
  position: relative;
  left: 500px;
  padding: 0 30px;
}
 .containerq {
  display: block;
  width: 100%;
  text-align: center;
  padding-top: 300px;
   padding-bottom: 300px;
  z-index: 9;
 }
#header {
  display: block;
  height: 700px;
  background: url("http://wow.nos.netease.com/1/legion/demonhunter/demonhunter-pic-big-1.jpg") center center no-repeat;
  background-size:cover;
  z-index: -1;
}
.header {
  text-align: center;
}
#header .containerq a:hover{
  background-color: orange;
}
.welcome{
  font-style: italic;
  font-size: 40px;
  line-height: 1em;
  color: #fff;
  padding-bottom: 30px;
}
.titlle{
  font-size: 50px;
  line-height: 1em;
  color:#fff;
  padding-bottom: 30px;
}
.btn {
  font-size: 30px;
  padding: 15px 20px;
  color:#fff;
  background: yellow;
  border-radius: 3px;
}
.h3-title{
  text-align: center;
}
.h3-title h3 {
  padding-top: 80px;
  font-size: 40px;
}
.h3-title p {
  font-size: 20px;
  font-style: italic;
  padding-bottom: 40px;
}
#support {
  text-align: center;
}
.clearfix {
  display: inline-block;
  width: 100%;
  height: 600px;
  text-align: center;
  padding-top: 100px;
 
}
.clearfix ul {
  display: inline-block;
  float: left;
  height: 500px;
  width: 100%;
  text-align: center;
}
.clearfix ul li {
  display: inline-block;
  width: 25%;
  float: left;
  margin-left: 6%;
  text-align: center;
  list-style: none；
  padding-top: 80px;
}


.clearfix p {
  padding-top: 50px;
  font-size: 14px;
  font-family: "Roboto Slab","Helvetica Neue", Helvetica, Arical, sans-serif;
}
.clearfix h4 {
  padding-top: 30px;
  font-size: 24px;
}
.hero{
   text-align: center;
}
.hero ul{
  height: 700px;
  display: block;
  text-align: center;
  list-style: none;
}
.hero ul li{
    position: relative;
    width: 300px;
    height: 280px;
    background-color: #fff;
    float: left;
    margin: 0px 0 25px 25px;
}
.hero ul li: after {
   content: "";
    display: block;
    clear: both;
}
#new {
    width: 1000px;
    margin: 0 auto;
    text-align: center;
}


.nw li span {
    width: 100%;
    height: 100%;
    display: none;
    position: absolute;
    top: 0;
    left: 0;
    background-color: rgba(254,209,54,0.4);
}
.hero li span p{
    padding-top: 100px;
    font-size: 30px;
    color: #FFF;
}
.hero li img{
  width: 100%;
}

.hero a:hover span{
  display: block;
}
#story{
  width: 1000px;
  margin: 0 auto;
  text-align: center;
}
.story .title {
   margin: 50px auto 20px auto;
   color: #3cabe7;
    }
    
.story .about {
   margin-bottom: 50px;
}
.story li {
   position: relative;
   padding-bottom: 100px;       
}
.story ul {
  list-style: none;
}
.story li img {
   width: 200px;
   height: 200px;
   border-radius: 50%;
   border: 2px #3cabe7 solid;
}
 .story li div {
      width: 300px;
      position: absolute;
      top: 0;
      left: 50px;
      text-align: right;
}
.story li:nth-child(2n) div {
    left: 650px;
    text-align: left;
}
.story li:after {
  
  content: '';
  display: block;
  height: 100%;
  position: absolute;
  border: 1px #3cabe7 solid;
  top: 0;
  left: 50%;
  z-index: -11;
}
.story li:last-child:after {
  display: none;
  height: 0;
}
.story .timeline p {
  margin-top: 20px;
}
.developer {
  width: 100%;
  height: 500px;
  background-color: #eee;
  margin: 0 auto;
   text-align: center;
}
.developer h1{
  padding-top: 50px;
  padding-bottom: 50px;
  color: #3cabe7;
  text-align: center;
}
.people {
  width: 1000px;
  height: 500px;
  margin: 0 auto;
  text-align: center;
}
#developer li{
  
  width: 200px;
  float: left;
  margin: 50px 0 50px 100px;
}

#developer ul {
  margin: 0 auto;
  text-align: center;
  list-style: none;
}
.developer li img {
  width: 200px;
  height: 200px;
  border-radius: 50%;
  border: 2px #3cabe7 solid;
  display: block;
  text-align: center;
}

.developer li a {
  display: inline-block;
  margin-left: 15px;
  text-align: center;
  margin:0 10px ;
}
#developer .people .someback a:hover {
  background-color: #fed136;
}
@font-face {
  font-family: 'iconfont';  /* project id 299052 */
  src: url('//at.alicdn.com/t/font_fpzo6px3tjpuv7vi.eot');
  src: url('//at.alicdn.com/t/font_fpzo6px3tjpuv7vi.eot?#iefix') format('embedded-opentype'),
  url('//at.alicdn.com/t/font_fpzo6px3tjpuv7vi.woff') format('woff'),
  url('//at.alicdn.com/t/font_fpzo6px3tjpuv7vi.ttf') format('truetype'),
  url('//at.alicdn.com/t/font_fpzo6px3tjpuv7vi.svg#iconfont') format('svg');
}
#developer ul li a.iconfont {
  font-family: iconfont !important;
  font-style: normal;
  color: #1296db;
  border-radius: 50%;
  background-color: black;
  display: inline-block;
  font-size: 5px;
   padding: 5px;
}
#footer ul li a.iconfont{
  font-family: iconfont !important;
  font-style: normal;
  color: #1296db;
  border-radius: 50%;
  background-color: black;
  display: inline-block;
  font-size: 5px;
  padding: 5px;
}

.contact {
  background-color: #222;
  height: 650px;
  color: #fff;  
}
.contact h1 {
 text-align: center;
 padding-top: 100px; 
 padding-bottom: 50px;
}
.contact input[type=text] {
 width: 530px;
 height: 60px;
 display: block;
 margin: 30px 0 0 70px;
 border-radius: 5px;
 padding-left: 25px;
 font-size: 25px;
}
.contact #usermessage {
  
  width: 510px;
  height: 200px;
  float: right;
  border-radius: 5px;
  margin-right: 70px;
  font-size: 20px;
  padding: 25px;
  font-size: 25px;
}
.contact input[type=submit] {
  display: block;
  margin: 50px auto;
  padding: 20px 50px;
  font-size: 20px;
  font-weight: bold;
  border-radius: 5px;
  text-align: center;
  background-color: #fed136;
  border: none;
  color: #fff;
}
.contact input[type=submit]:hover {
  background-color: orange;
}
#footer li {
  list-style: none;
  width: 33.3%;
  float: left;
  vertical-align: bottom;
  display: inline-block;
  text-align: center;
  margin: 20px 0; 
}
#footer li a {
  padding: 0 10px;
}
#footer .copyright {
  height: 100%;
  padding-top: 20px;
  vertical-align: bottom;
}
#footer .icon a:hover {
  background-color: orange;
}
#footer .link a:hover {
 color: orange;
}
 #footer .link {
   padding-top: 20px;
 }


  </style>
</head>
<body>
  <div class="nav">
  <div class="container">
  <div class="name">
    <em></em>
    <a href="#" class="logo">
      <img src="https://j2zen.github.io/static-web/img/logo.png" alt="logo">
    </a>
  </div>
  <ul>
    <li>
       <a href="#">支持</a>
    </li>
        <li>
       <a href="#">新职业</a>
    </li>
        <li>
       <a href="#">剧情</a>
    </li>
        <li>
       <a href="#">开发</a>
    </li>
        <li>
       <a href="#">联系我们</a>
    </li>
  </ul>
    </div>
  </div>
</div>
  <div id="header">
    <div class="containerq">
      <p class="welcome">欢迎来到魔兽世界</p>
      <h1 class="titlle">IT'S NICE TO MEET YOU</h1>
      <a href="#" class="btn">TELL ME MORE</a>
  </div>
  <div class="contentone" id="support">
    <div class="layout">
      <div class="h3-title">
        <h3>support</h3>
        <p>supported by some one</p>
      </div>
      <div class="clearfix">
      <ul >
        <li>
          <span id="icon">&#xe613;</span>
          <h4 class="titlesupport">E-commerce</h4>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima maxime quam architecto quo inventore harum ex magni, dicta impedit.</p>
       </li>
       <li>
          <span id="icon">&#xe682;</span>
          <h4 class="titlesupport">E-commerce</h4>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima maxime quam architecto quo inventore harum ex magni, dicta impedit.</p>
       </li>
       <li>
          <span id="icon">&#xe644;</span>
          <h4 class="titlesupport">E-commerce</h4>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima maxime quam architecto quo inventore harum ex magni, dicta impedit.</p>
       </li>
      </ul>
        </div>
    </div>
  </div>
  <div class="content" id="new">
    <div class="h3-title">
      <h3>恶魔猎手</h3>
     <p>依靠令人生畏的敏捷追猎与抵御最危险的对手</p>
    </div>
    <div class="hero">
      <ul class="nw">
        <li>
          <a href>
            <img src="http://wow.nos.netease.com/1/legion/demonhunter/demonhunter-pic-1.jpg" alt>
            <span>
              <p>more</p>
            </span>
          </a>
            <p>some design for hero</p>
        </li>
                  <li>
          <a href="#">
            <img src="http://wow.nos.netease.com/1/legion/demonhunter/demonhunter-pic-1.jpg" alt="#">
            <span>
              <p>more</p>
            </span>
          </a>
            <p>some design for hero</p>
        </li>
                <li>
          <a href="#">
            <img src="http://wow.nos.netease.com/1/legion/demonhunter/demonhunter-pic-1.jpg" alt="#">
            <span>
              <p>more</p>
            </span>
          </a>
            <p>some design for hero</p>
        </li>
                <li>
          <a href="#">
            <img src="http://wow.nos.netease.com/1/legion/demonhunter/demonhunter-pic-1.jpg" alt="#">
            <span>
              <p>more</p>
            </span>
          </a>
            <p>some design for hero</p>
        </li>
                <li>
          <a href="#">
            <img src="http://wow.nos.netease.com/1/legion/demonhunter/demonhunter-pic-1.jpg" alt="#">
            <span>
              <p>more</p>
            </span>
          </a>
            <p>some design for hero</p>
        </li>
                <li>
          <a href="#">
            <img src="http://wow.nos.netease.com/1/legion/demonhunter/demonhunter-pic-1.jpg" alt="#">
            <span>
              <p>more</p>
            </span>
          </a>
            <p>some design for hero</p>
        </li>
      </ul>
    
  </div>
  </div>
  
  <div class="story layout" id="story">
    <h1 class="title">剧情介绍</h1>
    <p class="about">
苏拉玛是古代暗夜精灵著名城市，夜之子的故乡。永恒之井爆炸时，这座雄伟的城市在暗夜井的庇护之下免受了大分裂的破坏，许多夜之子也得以存活至今。</p>
    <ul class="timeline">
      <li>
        <img src="http://wow.nos.netease.com/1/legion/map/area-pic/suramar-pic-3.jpg" alt>
        <div>
          <h3 class="subtitle">魔兽世界</h3>
          <p class="time">2012-2016</p>
          <p>恶魔猎手自愿接受了来自燃烧军团的禁忌力量。
他们驾驭邪能与混乱魔法，掌握了变身能力与幽灵视觉，
依靠令人生畏的敏捷追猎与抵御最危险的对手。</p>
        </div>
      </li>
      <li>
        <img src="http://wow.nos.netease.com/1/legion/map/area-pic/suramar-pic-3.jpg" alt>
        <div>
          <h3 class="subtitle">魔兽世界</h3>
          <p class="time">2012-2016</p>
          <p>恶魔猎手自愿接受了来自燃烧军团的禁忌力量。
他们驾驭邪能与混乱魔法，掌握了变身能力与幽灵视觉，
依靠令人生畏的敏捷追猎与抵御最危险的对手。</p>
        </div>
      </li>
      <li>
        <img src="http://wow.nos.netease.com/1/legion/map/area-pic/suramar-pic-3.jpg" alt>
        <div>
          <h3 class="subtitle">魔兽世界</h3>
          <p class="time">2012-2016</p>
          <p>恶魔猎手自愿接受了来自燃烧军团的禁忌力量。
他们驾驭邪能与混乱魔法，掌握了变身能力与幽灵视觉，
依靠令人生畏的敏捷追猎与抵御最危险的对手。</p>
        </div>
      </li>
      <li>
        <img src="http://wow.nos.netease.com/1/legion/map/area-pic/suramar-pic-3.jpg" alt>
        <div>
          <h3 class="subtitle">魔兽世界</h3>
          <p class="time">2012-2016</p>
          <p>恶魔猎手自愿接受了来自燃烧军团的禁忌力量。
他们驾驭邪能与混乱魔法，掌握了变身能力与幽灵视觉，
依靠令人生畏的敏捷追猎与抵御最危险的对手。</p>
        </div>
      </li>
      <li>
        <img src="http://wow.nos.netease.com/1/legion/map/area-pic/suramar-pic-3.jpg" alt>
        <div>
          <h3 class="subtitle">魔兽世界</h3>
          <p class="time">2012-2016</p>
          <p>恶魔猎手自愿接受了来自燃烧军团的禁忌力量。
他们驾驭邪能与混乱魔法，掌握了变身能力与幽灵视觉，
依靠令人生畏的敏捷追猎与抵御最危险的对手。</p>
        </div>
      </li>
    </ul>
  </div>
  <div class="developer" id="developer">
    <div class="people">
      <h1>开发人员</h1>
      <ul>
        <li>
          <img src="https://ss0.baidu.com/73F1bjeh1BF3odCf/it/u=3622940760,28753507&fm=85&s=84C4934ADC40A45506CD08880300F012" alt>
          <br>
          <span>克里斯·梅森</span>
          <p>游戏剧本设计师</p>
           <div class="someback">
            <a href class="iconfont icon1">&#xe662;</a>
            <a href class="iconfont icon2">&#xe705;</a>
            <a href class="iconfont icon3">&#xe664;</a>
          </div>
        </li>
                <li>
          <img src="https://ss0.baidu.com/6ONWsjip0QIZ8tyhnq/it/u=287909514,182213312&fm=58" alt>
          <br>
          <span>格雷格·斯特里特</span>
          <p>系统设计师</p>
          <div class="someback">
            <a href class="iconfont icon1">&#xe662;</a>
            <a href class="iconfont icon2">&#xe705;</a>
            <a href class="iconfont icon3">&#xe664;</a>
          </div>
        </li>
                <li>
          <img src="https://ss1.baidu.com/6ONXsjip0QIZ8tyhnq/it/u=1584296620,843673346&fm=58" alt>
          <br>
          <span>Dustin Browder</span>
          <p>用户设计师</p>
          <div class="someback">
            <a href class="iconfont icon1">&#xe662;</a>
            <a href class="iconfont icon2">&#xe705;</a>
            <a href class="iconfont icon3">&#xe664;</a>
          </div>
        </li>
      </ul>
    </div>
  </div>
  <div class="contact" id="contact">
    <h1>联系我们</h1>
    <form action="contact" method="post">
    <textarea id="usermessage" name="" usermessage="" cols="30" rows="10" placeholder="请输入信息"></textarea>
    <label for="username"></label>
    <input id="username" type="text" name="username" placeholder="请输入姓名">
    <label for="useremail"></label>
    <input id="useremail" type="text" name="useremail" placeholder="请输入Email">
    <label for="userphone"></label>
    <input id="userphone" type="text" name="userphone" placeholder="请输入电话">
      <label for="usermessage"></label>
       </form>
    <input type="submit" value="发送消息">
  </div>
  <div id="footer">
    <ul class="formation">
      <li class="copyright">Copyright @ your Website 2017</li>
      <li class="icon">
            <a href class="iconfont icon1">&#xe662;</a>
            <a href class="iconfont icon2">&#xe705;</a>
            <a href class="iconfont icon3">&#xe664;</a>
      </li>
      <li class="link">
       <a href class>Privacy Policy</a>
        <a href class> See More</a>
      </li>
    </ul>
  </div>
</body>
</html>
