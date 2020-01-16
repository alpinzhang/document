# 营销云概况
!> 营销云概况中使用的默认技术测试。。。

# 图文列表 
?> 不知道到底配置的对还是不对

# 如何定制侧边栏
侧边栏倒还是比较简单，但是这个全文搜索，确实有点问题
```js
function() {
  console.log(1111111111)
}
```
```
1.Win10下Chrome的默认安装路径是 “C:\Users\<你的用户名>\AppData\Local\Google\Chrome”；

2.确保目录：“C:\Users\<你的用户名>\AppData\Local\Google\” 下没有Chrome这个文件夹，有的话删除干净；

3.在你的非系统盘创建新的Chrome文件夹，例如：“D\Chrome”;

4.创建mklink：以管理员的身份运行命令提示符：【开始菜单—运行(以管理员的身份)—cmd】

    mklink /d "C:\Users\zxp46\AppData\Local\Google\Chrome" "D:\Chrome"

    回车，操作完成。

5. 原理介绍，就是利用“mklink”，在系统默认安装目录下创建非系统目录下文件夹的映像，实体文件存在于非系统目录下，映像文件夹并不占据系统盘的内存。

C:\Users\zxp46\AppData\Local\Google
```