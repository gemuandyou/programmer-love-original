# programmer-love-original
一个使用angular2的样例。整个项目分成多个不相干的模块。

### Charity
>这个模块的最终目的是一个求助信息发布平台。只是对于页面的布局和功能还没有好的想法。所以该模块目前用来测试angular2的特性，主要是路由的使用。

### Notes
>用来记录日志或笔记的模块。快速记录笔记和日志等信息。加了个音乐盒功能。这个模块目前是给自己用的，会在使用中不断完善。
* 示例图片如下（编辑区内容显示已优化）
!['示例图片'](https://github.com/gemuandyou/programmer-love-original/blob/master/app/assets/other/notes-demo.png?raw=true)

### So on
>等待扩展


##### 使用说明
由于typescript中Notification的d.ts定义文件中没有permission，所以会报错。需要在`node_modules/typescript`中查找`declare var Notification`，并在Notification中添加一个`permission: any;`属性。
```shell
npm install
```
```shell
npm start
```
