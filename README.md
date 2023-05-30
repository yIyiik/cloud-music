# 云音乐播放软件

## 概括

这是一款仿照网易云音乐软件页面制作出来的移动端音乐播放软件

## 使用

1. 先使用[网易云 API](https://neteasecloudmusicapi-docs.4everland.app)调取 API 接口
2. 再使用

   ```javaScript
    npm run serve
   ```

   命令即可运行项目

## 功能介绍

1. 首页
   - 点击右上角搜索图标可进入搜索页面
   - 点击中间歌单列表可进入歌单详情页面
   - 点击底部组件可进入歌曲详情页面
2. 歌单页
   - 头部组件展示歌单信息
   - 点击歌曲列表可以进行播放
3. 搜索页
   - 在上方搜索栏输入歌手或者歌名可进行搜索
   - 搜索结果在下方展示
   - 点击搜索出来的歌曲列表可进行音乐播放
4. 歌曲详情页
   - 点击底部组件可进入歌曲详情页
   - 点击旋转的专辑封面可查看歌词
   - 下方有进度条显示

## 技术栈

1. [网易云 API](https://neteasecloudmusicapi-docs.4everland.app/)
2. [vue](https://cn.vuejs.org/)
3. [vant](https://vant-contrib.gitee.io/vant/#/zh-CN)
4. [axios](http://www.axios-js.com/zh-cn/docs/)
