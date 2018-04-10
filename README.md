# KuerMusic Player

## 使用vue2.0制作的音乐播放器（基于qq音乐api）持续更新中...

## 源代码
源代码地址：[GitHub](https://github.com/duke1922/KuerMusic)  

### 在线预览
在线预览地址： [Vue音乐播放器](https://lxyisme.github.io) (PC端请在浏览器的移动端模式下查看)

![移动端二维码](https://github.com/lxyisme/vue-musicApp/blob/master/preview/1494160244.png)

### 预览图
![Vue音乐播放器](https://github.com/921227965/vue-musicApp/blob/master/preview/preview.gif?raw=true)

## 使用 Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

```

### 目录结构
<pre>

├── README.md           
├── config             // 项目不同环境的配置
├── dist               // 项目build目录
├── package.json       // 项目配置文件
├── src                // 生产目录
│   ├── assets         // 图片资源
│   │	├── icon
│   │	└── img
│   ├── components     // 各种组件
│   │	├── ActionSheet.vue
│   │	├── Album.vue
│   │	├── Cd.vue
│   │	├── Hello.vue
│   │	├── Lyric.vue
│   │	├── Play.vue
│   │	├── PlayingList.vue
│   │	├── Rank.vue
│   │	├── RankPage.vue
│   │	├── Recomand.vue
│   │	├── Search.vue
│   │	└── Singer.vue
│   ├── config          // 设置
│   │	├── api.js
│   │	└── def.js
│   ├── lib             // 推荐页面数据
│   │	├── components    // 组件数据
│   │	├── libs          // 路由配置
│   │	├── mixins        // 混入配置
│   │	└── styles        // 应用样式
│   ├── store           // 状态管理
│   │	├── ApiService.js        // 组件数据
│   │	├── index.js             // 路由配置
│   │	├── NotifyService.js     // 混入配置
│   │	└── PlayService          // 应用样式
│   ├── style           // 组件基本样式
│   │	├── weui_actionsheet.less     
│   │	└── weui_mask.less           
│   ├── utils      
│   │	└── base64.js           // 应用样式
│   ├── App.vue           // 项目入口文件
│   ├── router.js        // 路由配置接口
│   └── main.js        // Webpack 预编译入口
</pre>


### 已实现功能：

- [x]   音乐播放
- [x]   自动播放下一曲
- [x]   提前添加到下一首播放
- [x]   音乐列表（增删）
- [x]   下一曲
- [x]   排行榜
- [x]   排行榜详情页
- [x]   搜索
- [x]   loading
- [x]   播放详情页
- [x]   滚动歌词
- [x]   展示音乐进度

---

