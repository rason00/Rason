# 仿知乎日报app页面

---

- Demo：

        1. html+css+js+jq版本：

         - https://rason00.github.io/rason/zhihuribaoapp/index.html

        2. vue版本：

         - https://rason00.github.io/rason/zhihuribaoapp/vue2.0/index.html

- 仅实现：

        1，主页的banner。

        2，主页内容部分排版与数据显示。

        3，滑动到底部自动加载前一天数据（未实现下拉刷新页面功能，注：vue版本已实现）。

        4，文章详情页面版面展示。
        
        5，评论页展示。（仅vue版实现）

- 2017/09/08增加

        vue版本：

        1.文章详情页右上角增加评论数和点赞数。
        
        2.增加查看评论页。

        3.修改返回图标，夜间模式按钮图标。

- 2017/09/03修复

        vue版本日夜间模式刷新bug修复
        
        利用vue的watch监视状态存到localstorage中，再监视日夜间状态与缓存是否一致

- 2017/09/02增加

        vue版增加夜间模式
        
        使用vuex处理夜间模式状态
        
        （刷新页面会使夜间模式变成日间模式）注：2017/09/03日已修复

- 2017/08/09增加

        vue版本增加下拉刷新页面功能，并且增加判断防止底部加载更多时多次发起请求。

- 2017/08/08增加

        使用vue2.0-cli+vue-router+axios+mint-ui制作相同的页面展示（实现功能如上‘仅实现’）。  

- 2017/08/02优化

        优化首页banner，改用插件，做滑动切换效果。

- 2017/07/30优化

        优化首页banner以及详情页顶部图片，适配分辨率图片不变形。

- 2017/07/25修改

        1，把详情页面展示从清空原页面渲染请求内容改为，新增一个文章详情页面。
        
        2，模拟点击文章跳到详情页面后，返回时页面返回到之前跳出的位置。

- 内容部分使用了 https://segmentfault.com/a/1190000009242864 整理的api，在此表示感谢。 

- 另图片加载时遇到了图片防盗链问题，最后在 https://github.com/biaodigit/vue-news 里找到了相应的处理方法，在此表示感谢。

- 建议PC模式下使用chrome移动端模式浏览观看
