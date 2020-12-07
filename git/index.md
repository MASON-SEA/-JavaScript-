<!--
 * @Author: mason
 * @Date: 2020-12-07 10:14:06
 * @LastEditTime: 2020-12-07 10:22:36
 * @LastEditors: Please set LastEditors
 * @Description: 记录git的方法
 * @FilePath: \test\daily_study\Development-Diary\git\index.md
-->

//本地项目传送给GitHub

``` javascript
git init

git add .

git commit -a -m 'description'

git remote add origin GitHub项目地址

git push -u origin master

```

//新建一个分支

``` javascript

//1.创建本地分支
git branch 分支名

//2.切换本地分支
git checkout 分支名

//3.提交分支数据到远程服务器
git push origin 分支名
//在此分支下时
git push

//4.删除远程分支
git push origin :develop

//5.查看分支
git branch

```
