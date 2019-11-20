<template>
  <div class="myresume">
    <div class="my-info">
      <h2 class="my-name">{{ msg }}</h2>
        <ul>
          <li>
            <a href="" target="_blank">简历</a>
          </li>
          <li>
            <a href="" target="_blank">作品</a>
          </li>
        </ul>
    </div>
    <div class="my-contain">
      <div class="page">
        <section>
          <h1>联系方式</h1>
          <div class="boxes bg-gray">
            <div class="row">
              <div class="col-2">● 手机：15768697632</div>
              <div class="col-2">● Email：1668711344@qq.com</div>
            </div>
          </div>
        </section>
        <section>
          <h1>个人信息</h1>
          <div class="boxes bg-gray">
            <div class="row">
              <div class="col-2">● 何宇青 | 女 | 1998</div>
              <div class="col-2">● 专科 | 广东科学技术职业学院 | 移动应用开发</div>
            </div>
            <div class="row">
              <div class="col-2">● 期望职位：Web前端开发</div>
              <div class="col-2">● 期望城市：广东珠海</div>
            </div>
            <div class="box">
              ● GitHub：<a href="https://github.com/yuqing-he" target="_blank">https://github.com/yuqing-he</a>
            </div>
            <div class="box">
              ● Gitee：<a href="https://gitee.com/he_yuqing" target="_blank">https://gitee.com/he_yuqing</a>
            </div>
          </div>
        </section>
        <section>
          <h1>技能掌握</h1>
          <div class="boxes bg-gray">
            <div class="box">● 前端框架：Ionic / Vue / Flutter / 微信小程序</div>
            <div class="box">● 前端工具：Webpack / Sass / Less / Cordova</div>
            <div class="box">● 版本管理工具：Git / GitLab / Svn</div>
          </div>
        </section>
        <section>
          <h1>项目经验</h1>
          <div class="boxes bg-gray">
            <p>● 2019金慧IT精英项目班 （ 2019 年 3 月 ~ 至今 ）</p>
            <div class="box">
              <p><b>前端开发</b></p>
              <p>- 使用HTML语言、div+css+javascript等前端技术进行app的开发与制造，使用ionic框架、flutter框架等技术进行项目开发</p>
              <p>- 涉及功能：token加密、用户权限管理、全局状态与路由管理、树状数据管理、列表数据展示、表单验证、关系图示、原生接口对接等</p>
            </div>
          </div>
          <div class="boxes bg-gray">
            <p>● 珠海金慧科技有限公司 （ 2019 年 6 月 ~ 8月 ）</p>
            <div class="box">
              <p><b>主导金桥法务1.0后台管理系统开发</b></p>
              <p>- 使用*H-ui*前端框架开发的轻量级网站后台模版采用源生 html 语言，使用vue.js进行项目开发</p>
              <p>- 涉及功能：律师管理、图文管理、用户权限管理、列表数据展示、数据审核、增删改查、原生接口对接等</p>
            </div>
          </div>
          <div class="boxes bg-gray">
            <p>● 就服你项目 （ 2019 年 5 月 ~ 至今 ）</p>
            <div class="box">
              <p><b>创业项目负责人/前端开发</b></p>
              <p>- 负责开发小组的工作调度、人员职能安排与分配、参加创新创业大赛的活动，前端与后端开发的进度以及跟进和时间安排等任务</p>
              <p>- 负责app静态页开发及简单交互</p>
            </div>
          </div>
          <div class="boxes bg-gray">
            <p>● 章鱼校园 （ 2019 年 9 月 ~ 至今 ）</p>
            <div class="box">
              <p><b>前端开发</b></p>
              <p><b>主导微信小程序、后台管理系统开发</b></p>
              <p>- 负责小程序校园百卡样式的实现和商家后台管理模块。</p>
              <p>- 涉及Visual Studio Code开发工具、html、css、vue、mpvue+vant-weapp等开发技术，现几大功能运行稳定，运算速度明显变快</p>
            </div>
          </div>
          ......
        </section>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MyResume',
  data () {
    return {
      msg: 'Yuqi'
    }
  }
}
</script>

<style scoped>
h1, h2 {
  font-weight: normal;
}
p {
    margin-top: 0;
    margin-bottom: 1em;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
a:link { text-decoration: none;color: #42b983}
a:active { text-decoration:blink}
a:hover { text-decoration:underline;color: red}
a:visited { text-decoration: none;color: #948c76}

.my-name {
    font-size: 1.8em;
    font-weight: 400;
    padding: 0 .5em;
    letter-spacing: .1em;
    line-height: 2em;
    display: inline-block;
    color: #AB82FF;
    background: #F0F8FF;
    opacity: 0.8;
}
.page {
    max-width: 800px;
    margin: 20px auto;
    padding: 20px;
    box-shadow: 1px 1px 8px rgba(0,0,0,.15);
    background-color: #fff;
    color: #3f1c1c;
    font-size: 1.0em;
}
h1 {
  padding: 0;
  margin: 0;
}
.page h1 {
    margin-left: -20px;
    padding-left: 15px;
    border-left: 5px solid #AB82FF;
    text-align: left;
    font-size: 1.2em;
    font-weight: 900!important;
}
.page .boxes {
    border: 2px solid transparent;
    border-radius: 5px;
    margin-bottom: 15px;
}
.page .box {
    padding: 10px 0;
}
.page .bg-gray {
    background-color: #f5f5f5;
    padding: 20px 0;
    text-align: left;
    padding-left: 15px;
    padding-right: 10px
}
.page .row {
    display: flex;
    flex-wrap: wrap;
}
.page .col-2 {
    flex: 40%;
    max-width: 50%;
    padding: 10px 0;
}

</style>
