# pm_blog
当系统运行之后，任何权限用户均能够进入博客的前台页面，包含游客。网页前端设计偏向暗色风格，网页正中间有利用Live2D技术构造的二次元人物以及网易云音乐插件实现自动播放。向下翻动时，便会出现导航栏。以此是博客首页，标签页面、归档页面、音乐播放页面、留言页面、图片展示页面以及关于我页面。点击相应的链接会跳转到相应的页面看到对应的信息。

![image](https://user-images.githubusercontent.com/43785374/157373807-1c756de8-bd96-4a0e-97b6-8925874aabec.png)


博客的主页面主要包含博客展示，博客文章会根据发布博客的顺序进行展示。点击相应博客题目跳转到对应博客内容详情页面，由Markdown进行展示。页面的右边展示的是博客文章分类、博客标签以及推荐文章。后边展示的是相对应的博客文章数量。

![image](https://user-images.githubusercontent.com/43785374/157373845-0192a24d-ecad-49d5-8ce0-e5c84035fd5a.png)


目前博客标签包含类型有：那些文字、版本升级以及Tempermonkey。标签下面展示的是博客信息。点击相对应的标签也会出现对应的博客文章，相对应类型下有对应文章展示。

![image](https://user-images.githubusercontent.com/43785374/157373876-960bacb2-6df2-41fd-875b-e833049556c4.png)

留言页面主要是实现博客留言并且游客交流学习功能。如果是管理员进入该页面，留言信息名字后面会自动显示该用户的身份是博主，若是普通游客进行信息留言则需要输入昵称以及邮箱，再输入留言信息，就可实现留言功能。并且在该页面可以对已发布的留言进行回复功能。


![image](https://user-images.githubusercontent.com/43785374/157373922-c87168fc-c03b-40c6-ac4b-2160c273f6c8.png)


live2D交互小人实现
具体实现步骤：首先在博客程序头部文件引入界面样式。在body标签内合适的位置插入Live2D 看板娘的元素，引入模型并且设置人物的高度和宽度。在message.json文件内写入点击看板娘将会出现的提示文字对话。


![image](https://user-images.githubusercontent.com/43785374/157374020-e54a4a67-beb1-41b3-a3d1-614b2d37ee9b.png)

后台管理员


![image](https://user-images.githubusercontent.com/43785374/157374107-74a422a7-66e1-471d-b1d5-8e47b00bf062.png)
![image](https://user-images.githubusercontent.com/43785374/157374122-a0edfe32-7b40-4ff5-990e-bb35946a17ec.png)
![image](https://user-images.githubusercontent.com/43785374/157374129-6b3e9d14-b8aa-468b-86a3-e9277204dfc0.png)
