# 任务一
## 行内式链接
创建一个链接到 https://www.markdownguide.org 的文本，格式为 [链接文字](网址)。添加一个鼠标悬停提示（在网址后空格加 "提示"）。
- [Markdown官方指南](https://www.markdownguide.org"Markdown "语法导航网站")

# 任务二：参考式链接
## 参考式链接（分离源，代码和文字分开）
为“GitHub”定义引用链接：[GitHub][1]，然后在文中任意位置给出 [1]: https://github.com。使用这种方法创建两个链接，体验分离源与文本的好处。
- 前端学习去[GitHub][1] 开源项目也在[GitHub][1]
- \[1]:https://github.com "代码存放平台"

# 任务 3：插入网页图片
插入一张网络图片：![替代文本](图片URL)。尝试添加可选的 title，如 ![猫](url "一只猫")，鼠标悬停查看效果。
- ![奶油蛋糕](![BQACAgUAAyEGAASHRsPbAAEXo7VqYCM3lFoF6mGBpaJ-DL6CmV14tgACWCMAAtJdAAFXV5dzTzV4NGM9BA.jpg](https://img.remit.ee/api/file/BQACAgUAAyEGAASHRsPbAAEXo7VqYCM3lFoF6mGBpaJ-DL6CmV14tgACWCMAAtJdAAFXV5dzTzV4NGM9BA.jpg) "一份奶油蛋糕")


# 任务四
任务 4：本地图片与路径
把一张图片放入与 .md 文件相同的文件夹，用相对路径 ![我的图](./图片名.jpg) 插入。再在子文件夹中测试，学会相对路径写法。

![长白山](./长白山.jpg "天池")

# 任务 5：可点击的图片
用 [![图片](图片地址)](链接地址) 的嵌套写法，实现点击图片跳转到某个网页。写一个示例，点击小图标跳转到你的邮箱（mailto: 链接）。
- [![冰雪消融，万物复苏](https://ts3.tc.mm.bing.net/th/id/OIP-C.ZVkjygutVm5b7BwfxWXdSgHaEK?r=0&rs=1&pid=ImgDetMain&o=7&rm=3 "万物复苏")](mailto:1458773799@qq.com)

ps：
- 直接插入图片只能用md格式的链接
- 嵌套写法内部必须要用直链链接