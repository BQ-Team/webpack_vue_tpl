**前端模块化项目模板（SPA单页应用）**

**基本框架：** webpack(构建工具) + vue（框架） + zepto（类库） + seaJs（模块化） + director（路由）

```bash
运行项目，步骤如下（预先安装nodeJS）：


```


目录结构如下：
```
project
  ├─ modules     工程模块
  │  ├─ common  公共模块
  │  │  └─ baseDialogPage 模态窗口基类
  │  │  └─ basePage       所有模块基类
  │  ├─ components         独立组件
  │  │  ├─ header
  │  │  └─ .....
  │  └─ pages               一般页面、弹框模块
  │     ├─ selectCity
  │     └─ home
  ├─ static      静态资源
  │  ├─ css     
  │  ├─ images  
  │  ├─ js      
  ├─ app.js         项目入口
  ├─ webpack-config.js    webpack编译配置
  ├─ index.html     html页面
  ├─ package.json   npm配置文件 
  ...
```



 - [vue官网](http://cn.vuejs.org/guide/installation.html)
 - [webpack官网](https://webpack.github.io/)
