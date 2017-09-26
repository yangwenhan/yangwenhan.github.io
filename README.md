#HEXO指令

#### hexo new "postName"      ：          新建文章
#### hexo new page "pageName"           ：        新建页面
#### hexo generate  ： 生成静态页面至public目录
#### hexo server  ： 开启预览访问端口（默认端口4000，'ctrl + c'关闭server）
#### hexo deploy  ： 部署到GitHub
#### hexo help  ： 查看帮助
#### hexo version  ： 查看Hexo的版本

#### hexo s -g  : 生成并本地预览
#### hexo d -g  : 生成并上传


#### title: postName  文章页面上的显示名称，一般是中文
#### date: 2013-12-02 15:30:16  文章生成时间，一般不改，当然也可以任意修改
#### categories: 默认分类
#### tags: [tag1,tag2,tag3] w章标签，可空，多标签请用格式，注意:后面有个空格
#### description: 附加一段文章摘要，字数最好在140字以内，会出现在meta的description里面


#### 默认情况下，生成的博文目录会显示全部的文章内容，在合适的位置加上`<!--more-->`,可设置文章摘要的长度。