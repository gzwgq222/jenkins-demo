<template>
  <div class="hello">
<<<<<<< HEAD
    <h2>{{ msg }}</h2>
=======
    <h1>{{ msg }}</h1>
    <h1>Success</h1>
    <h2>Essential Links</h2>
>>>>>>> 216246f5b59a291c92159c9a02b4b8d1e9fb4bef
    <ul>
      <a
        target="_blank"
        v-for="(item, index) in mv"
        :key="index"
        :href="`https://jx.beiwo77.com/?url=${item.src}`">
        <li>
          <img :src="item.img" :alt="item.title">
          <h4>{{ item.title }}</h4>
        </li>
      </a>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
<<<<<<< HEAD
      msg: 'Jenkins Ci Test， push event will build',
      mv: [
        {
          'title': '少年的你',
          'img': 'https://rpg.pic-imges.com/pic/upload/vod/2019-10/1572014327.jpg',
          'src': 'https://youku.cdn7-okzy.com/20191126/15946_b6e68816/index.m3u8'
        },
        {
          'title': '惊奇队长',
          'img': 'http://ws3.sinaimg.cn/large/8848761fly1g13orkun9qj20a60e7q3u.jpg',
          'src': 'https://youku.cdn7-okzy.com/20191126/15952_08392867/index.m3u8'
        },
        {
          'title': '天气之子',
          'img': 'https://img.kuyun88.com/pic/uploadimg/2019-9/20199291971153410.jpg',
          'src': 'https://baidu.com-ok-baidu.com/20190929/15161_9c171864/index.m3u8'
        },
        {
          'title': '决战中途岛',
          'img': 'https://img.kuyun88.com/pic/uploadimg/2019-11/2019111018304523773.jpg',
          'src': 'https://vip888.kuyun99.com/20191110/Nr7lOPzj/index.m3u8'
        },
        {
          'title': '海上钢琴师',
          'img': 'http://pic.yc370.com/upload/vod/2019-11-09/15732708635.jpg',
          'src': 'https://zk1.603ee.com/2019/11/09/b9x8xhIbCKTvfCkt/playlist.m3u8'
        },
        {
          'title': '蜘蛛侠：英雄远征',
          'img': 'https://img.pic-imges.com/pic/upload/vod/2019-06/15618663320.jpg',
          'src': 'https://youku.com-ok-tudou.com/20190906/4345_8530bac2/index.m3u8'
        },
        {
          'title': '蜘蛛侠：英雄远征',
          'img': 'https://img.pic-imges.com/pic/upload/vod/2019-06/15618663320.jpg',
          'src': 'https://baidu.com-ok-baidu.com/20190912/14950_e222f712/index.m3u8'
        },
        {
          'title': '惊奇队长',
          'img': 'http://ws3.sinaimg.cn/large/8848761fly1g13orkun9qj20a60e7q3u.jpg',
          'src': 'https://baidu.com-ok-baidu.com/20190919/15040_86a73138/index.m3u8'
        },
        {
          'title': '新铁石心肠/铁石心肠2019',
          'img': 'http://ws3.sinaimg.cn/large/8848761fly1g1ptnduxacj206n09ijri.jpg',
          'src': 'https://vip888.kuyun99.com/20190305/UvPNQnUj/index.m3u8'
        },
        {
          'title': '蜘蛛侠：英雄远征',
          'img': 'https://img.pic-imges.com/pic/upload/vod/2019-06/15618663320.jpg',
          'src': 'https://56.com-t-56.com/20190728/23849_9b8076fd/index.m3u8'
        },
        {
          'title': '惊奇队长',
          'img': 'http://ws3.sinaimg.cn/large/8848761fly1g13orkun9qj20a60e7q3u.jpg',
          'src': 'https://56.com-t-56.com/20190527/23076_565f60df/index.m3u8'
        },
        {
          'title': '新铁石心肠/铁石心肠2019',
          'img': 'http://ws3.sinaimg.cn/large/8848761fly1g1ptnduxacj206n09ijri.jpg',
          'src': 'https://pptv.com-h-pptv.com/20190305/15638_5a2d2eb9/index.m3u8'
        }
      ]
=======
      msg: 'push event will build'
>>>>>>> 216246f5b59a291c92159c9a02b4b8d1e9fb4bef
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
img {
  width: 270px;
  height: 377px;
}
a {
  color: #2c3e50 !important;
}
h4 {
  text-align: center;
}
h1, h2 {
  font-weight: normal;
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
</style>
