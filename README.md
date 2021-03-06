# DjangoMyStarMeow
个人学习项目整合，包含（Event系统、WiKi系统、个人博客）

# 事件管理系统Event
## 功能描述

1. 用户创建一个事件
2. 进行处理
3. 提交事件的处理过程
4. 处理完成后提交事件分析
5. 最终确认时间处理完成
6. 时间列表查看
7. 事件筛选

# 内容管理系统WiKi

## 功能描述

**后台文章管理**

1. 文章树形排列
1. 支持文章目录移动、修改、删除，使用mptt库优化内容显示
1. 支持Markdown显示文章正文
1. 标签管理及显示文章标签
1. 显示用户评论，可删除用户评论
1. 前端主题管理
2. 有redis，celery的运用

**前端文章查看**

1. 显示路径列表
1. 支持显示WiKi标题大纲
1. 显示文章正文和添加评论
1. 显示作者动态和留言回复

# 我的个人博客Blog

## 功能描述

**后台管理**

1. 博客列表展示
2. 分类查看
3. 显示最新、最热、评论最多
4. 按时间归档筛选
5. 按标签归档筛选
6. 随机推荐博客
7. 博客详情查看
8. 博客详情页展示聚合推荐
9. 创建新博客，使用editor.md，支持粘贴截图上传返回markdown格式图片
10. 博客分类、标签管理，包括增删查改
11. 还有一些网站数值统计

**用户界面**

1. 类似于后台管理内容模块的全屏版
2. 非管理员用户访问受限
3. 可对博客进行评论以及回复评论
4. mptt的应用，评论的优化展示
