# frontend

**Vue:**

- vue-cli 搭建的模块化脚手架工程

```shell
npm install webpack -g //全局安装webpack
npm install --global vue-cli //安装vue-cli
```

- 运行成功端口![img](https://raw.githubusercontent.com/NilPointerError/frontend/main/image-20230726152248559.png)

- 整合Vue UI框架ElementUi

```shell
npm i element-ui -S //安装elementui
```

```js
import ElementUI from 'element-ui';
import 'element-ui/lib/theme-chalk/index.css';

Vue.use(ElementUI);
```

