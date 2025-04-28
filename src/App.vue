<template>
  <div>
    <div>
      <div class="ask">
        <img src="./assets/ask.jpg">
      </div>
      <div class="question">
        <div style="margin-bottom: 20px">
          最近准备去西安旅游，请问西安玩几天合适?有哪些必去景点?吃住行怎么安排?费用大概多少?
        </div>
        <div class="comment">
          <span>9486浏览</span><span>370回答</span><span>822评论</span>
        </div>
        <div class="bottom">
          <div class="where">
            <img src="./assets/map.png" alt=""><span>陕西西安</span>
          </div>
          <div class="who">
            <img src="./assets/who.png" alt=""><span>L不是山谷 发布于 7天前</span>
          </div>
        </div>
      </div>
    </div>
    <div>
      <div class="ansPer">
        <img class="answer" src="./assets/answer.jpg" alt="">
        <span style="margin-left: 54px;margin-right: 8px">勇往直前zl</span>
        <img class="level" src="./assets/level.jpg" alt="">
        <img class="gold" src="./assets/gold.jpg" alt="">
        <span class="time">七天前</span>
      </div>
      <div class="text">
        <img class="bestAnswer" src="./assets/bestAnswer.jpg" alt="">
        答：<br>
        <p style="z-index: 1px">楼主你好，我和老公刚从西安旅游回来，这里给楼主简单分享一下我们的旅程经历吧</p>
        <p>希望对你有所帮助。我们在西安玩了5天，都是玩的精华景点，现在西安的天气很凉爽</p>
        <p>非常适合出游!因为最近几年疫情影响，旅游不景气，所以现在去西安旅游可以享受很多优惠! 具体的可以先问问当地导游 <span style="color: #4095E5;font-weight:bold ;"><span style="color: #4095E5;font-weight:bold ;">{{ nowName }}</span></span>，她的微信是: <span style="color: #4095E5;font-weight:bold ;">{{ nowPhone }}</span>(电话微信同号-有兴趣的朋友可以加微信聊聊)</p>
        <p class="points">西安好玩的景点:大唐不夜城、长恨歌、华山、壶口瀑布、兵马俑、华清宫、法门寺、陕西历史博物馆</p>
        <img style="width: 100%" src="./assets/图片1.jpg" alt="">
        <div>西安主要景点</div>
        <div>1.【西安市区】:大雁塔，音乐喷泉，大唐芙蓉园，陕西历史博物馆，钟楼和鼓楼，明城墙</div>
        <div>2.【网红打卡】:大唐不夜城，回民街，长恨歌，永兴坊</div>
        <div>3.【精华景区】:华山，壶口瀑布，兵马俑、华清宫，法门寺，黄帝陵</div>
        <div>（<span style="color: #4095E5;font-weight:bold ;">{{ nowName }}</span>会根据你游玩时间为你合理推荐搭配路线景点，不用担心时间和行程不匹配，想怎么玩就怎么玩）</div>
        <div class="person"><span style="color: #4095E5;font-weight:bold ;">{{ nowName }}</span> <span style="color: #BD3124;font-weight:bold ;"> 微信: <span>{{ nowPhone }}</span>(长按复制)</span></div>
        <div>不错过任何好玩的地方，还有众多小吃等着你!如果你预约了又不想去了提前说一声还可以随时取消行程，这点很棒</div>
        <p>西安导游<span style="color: #4095E5;font-weight:bold ;">{{ nowName }}</span>联系方式: <span style="color: #BD3124;font-weight:bold ;"><span>{{ nowPhone }}</span>(长按复制)&lt;←点击号码复制添加微信&gt;。</span>记得添加的时候说是可可推荐的，她们会给你最优惠价格的</p>
        <img style="width: 100%" src="./assets/图片2.jpg" alt="">
        <p>可能你要问，西安现在可以玩吗，这么多景点，时间不多的话怎么兼顾呢?</p>
        <p>其实不仅仅是西安，任何地区美好的景点总不会都挤在一块，如果要玩得好，傻乎乎靠自己去做攻略，是很浪费时间和金钱的，咱们必须懂得利用网上各种资源。</p>
        <img style="width: 100%" src="./assets/图片3.jpg" alt="">
        <p>我的解决方案是:准备去旅行前，都要先去网上找一些当地导游的微信，问<span style="color: #4095E5;font-weight:bold ;">{{ nowName }}</span>们要旅游线路，然后问住宿、门票、交通的报价，基本上，她们的报价都会比我自己拿到的价格要低，毕竟她们是专门做旅游的，和酒店、景点都是长期合作。这样大概就有一个前期的预算了。我的5天4晚费用仅仅花了1000元左右哦(包括吃饭+住宿+门票等全含）</p>
        <p>西安这边，我找的这个导游叫<span style="color: #4095E5;font-weight:bold ;">{{ nowName }}</span>，是个口碑不错的导游，要去西安游玩的朋友也可以加她的微信: <span style="color: #BD3124;font-weight:bold ;"><span>{{ nowPhone }}</span>(长按复制)(←点击号码复制添加微信)(<span>{{ nowName }}</span>)</span>。路线推荐，门票预定，酒店预定，甚至是车票及飞机票都能搞定，还能拿到优惠哦。</p>
        <img style="width: 100%" src="./assets/图片4.jpg" alt="">
        <p>开始的时候，我是想完全自由行的，但网上的攻略总是看得一头雾水，尤其景点太分散，交通、安排路线很麻烦的，还有酒店预订，景点门票一大堆事情，有的景点还限流，不提前定好票，去了还玩不了。所以后来还是用老习惯，加了<span style="color: #4095E5;font-weight:bold ;">{{ nowName }}</span>，拿了她的几个路线方案，选了我喜欢的，很省钱，而且省心，车接车送，都是老司机，很安全。(好了，接下来给大家看看我的行程吧)</p>
        <img style="width: 100%" src="./assets/图片5.jpg" alt="">
        <p>第一天:下午抵达西安，<span style="color: #4095E5;font-weight:bold ;">{{ nowName }}</span>安排接机，入住酒店，自由活动(晚上逛不夜城)</p>
        <img style="width: 100%" src="./assets/图片6.jpg" alt="">
        <p>第二天:黄帝陵、轩辕庙、黄河壶口瀑布</p>
        <img style="width: 100%" src="./assets/图片7.jpg" alt="">
        <p>第三天:西安大雁塔、延安(王家坪、枣园、1938文化广场南泥湾革命旧址、宝塔4、南泥湾革命旧址)</p>
        <img style="width: 100%" src="./assets/图片8.jpg" alt="">
        <p>第四天:明城墙、华清宫、秦始皇帝兵马俑博物馆</p>
        <img style="width: 100%" src="./assets/图片9.jpg" alt="">
        <p>第五天:华山</p>
        <img style="width: 100%" src="./assets/图片10.jpg" alt="">
        <p>短短几天时间，让我感受到不一样的西安想走就走，走走停停，停停拍拍，处处是风景，度假散心真的再适合不过了。<span style="color: #4095E5;font-weight:bold ;">{{ nowName }}</span>带我吃的西安美食很正宗，不仅味道好还很便宜!</p>
        <img style="width: 100%" src="./assets/图片11.jpg" alt="">
        <p>西安景点众多，并且分散:~建议大家去之前可以先找她咨询一下!她会把去西安的注意事项、准备哪些东西、一些景点交通住宿的具体费用、旅游线路、防坑指南等一些细节都会统统告诉你。机票高铁票紧张的话<span style="color: #4095E5;font-weight:bold ;">{{ nowName }}</span>也会帮忙抢优惠票哦，她的微信: <span style="color: #BD3124;font-weight:bold ;"><span>{{ nowPhone }}</span>(长按复制)(←点击号码复制添加微信)</span></p>
        <img style="width: 100%" src="./assets/图片12.jpg" alt="">
        <p>总结一下选择她安排的几个好处:</p>
        <p>
          第一:交通问题<br>当时查了很多航班和高铁，价格都比较贵并且机票和高铁票也很紧张，最后是<span style="color: #4095E5;font-weight:bold ;">{{ nowName }}</span>通过渠道帮我订的往返特价机票。旅行中全程都是坐的商务车，很舒适。总之此次的西安之行特别顺利，也实惠。<br>
          第二:行程安排<br>让<span style="color: #4095E5;font-weight:bold ;">{{ nowName }}</span>安排行程的好处就是自己想怎么玩就怎么玩，根据自己的安排设计好行程线路想玩几天都可以根据具体时间来安排，累了就休息，饿了<span style="color: #4095E5;font-weight:bold ;">{{ nowName }}</span>就带我吃西安当地特色美食，哪里的风景好看就停下来多欣赏，多拍照，很自由。<br>
          第三:食宿问题<br>她给我安排的都是当地的星级酒店，价格不仅实惠而且环境特别舒适，吃这一块也没得说，西安的特色美食基本都尝遍了，想吃宵夜的话她会带我去当地的美食街去吃。
        </p>
        <p>
          回复：<br>君生：刚步入大学，正好我计划要同学一起去西安玩,不想要太累的，所以不想跟团，你们是怎么玩的，价格怎么样?
        </p>
        <p>勇往直前zl：我们是5天4晚的行程，每人才1000多元。你和同学去可以先选择咨询她看下好不好，反正我们玩的挺开心的，毕竟自己去人生地不熟,没人介绍完全不知道怎么玩。她的微信: <span style="color: #BD3124;font-weight:bold ;"><span>{{ nowPhone }}</span>(长按复制)&lt;←点击号码复制添加微信&gt;</span></p>
        <img style="width: 100%" src="./assets/图片13.jpg" alt="">
        <p>潮已平：当时我和闺蜜们在西安游玩了5天，选的是<span style="color: #4095E5;font-weight:bold ;">{{ nowName }}</span>的自由行套餐，精华的地方都玩到了，随手一拍就是风景大片，美不胜收!但是呢最大的感受就是西安的景点过于分散，自己玩容易走回头路，非常浪费时间，我个人觉得现在国内的成熟的旅游景点比如西安这样的，最好还是结伴玩，可以请一个导游，毕竟出来玩，重要的是轻松和开心嘛!感谢<span style="color: #4095E5;font-weight:bold ;">{{ nowName }}</span>带我们一群人吃喝玩乐，度过了一个开心的旅程!</p>
      </div>
    </div>
    <div class="personBottom"><span style="color: #4095E5;font-weight:bold ;">{{ nowName }}</span> <span style="color: #BD3124;font-weight:bold ;"> 微信: <span>{{ nowPhone }}</span>(长按复制)</span></div>
  </div>
</template>
<script>
export default ({
  data() {
    return {
      index: 0,
      nowName: '',
      nowPhone: '',
      nameAndPhone: [
        {
          name: '露露',
          phone: '19567686573'
        },
        {
          name: '露露',
          phone: '19567686573'
        },
        {
          name: '露露',
          phone: '19567686573'
        },
        {
          name: '露露',
          phone: '19567686573'
        }
      ]
    }
  },
  created() {
    this.index = Math.floor(Math.random() * 4);
    this.nowName = this.nameAndPhone[this.index].name
    this.nowPhone = this.nameAndPhone[this.index].phone
  }
})
</script>

<style>
html, body {
  margin: 0;
  padding: 0;
  width: 100%;
  overflow-x: hidden;
}
.ask {
  font-weight: bold;
  position: absolute;
  top: 20px;
}
.ask img {
  width: 30px;
}
.question {
  padding: 20px 20px 20px 50px;
}
.comment {
  margin-bottom: 20px;
}
.bottom {
  width: 100%;
}
.comment span {
  display: inline-block;
  padding: 0px 30px 0px 8px;
}
.where{
  width: 30%;
  color: #50ccb4;
  display: inline-block;
  height: 30px;
  line-height: 30px;
}
.who {
  width: 70%;
  text-align: right;
  height: 30px;
  line-height: 30px;
  display: inline-block;
}
.where img {
  width: 30px;
  position: absolute;
}
.who img {
  width: 30px;
  position: absolute;
}
.who span {
  display: inline-block;
  margin-left: 35px;
}
.where span {
  display: inline-block;
  margin-left: 30px;
}

.answer {
  position: absolute;
  width: 50px;
}
.level {
  width: 30px;
  margin-right: 8px;
}
.gold {
  width: 44px;
}
.time{
  position: absolute;
  right: 10px;
  font-size: 14px;
  color: gray;;
}
.text{
  padding: 20px;
}
.points {
  color: #E99D42;
}
.bestAnswer {
  z-index: -10;
  width: 80px;
  position: absolute;
  right: 20px;
}
.person {
  height: 30px;
  line-height: 30px;
  vertical-align: middle;
  text-align: center;
  border: 1px solid #f5f5f5;
  background-color: #f5f5f5;
  width: 100%;
}
.personBottom {
  position: fixed;
  bottom: 0;
  height: 30px;
  line-height: 30px;
  vertical-align: middle;
  text-align: center;
  border: 1px solid #f5f5f5;
  background-color: #f5f5f5;
  width: 100%;
}
</style>
