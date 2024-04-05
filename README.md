# jioj-frontend

## 页面设计
做题界面
![只因在线做题系统-做题界面](https://img-blog.csdnimg.cn/direct/3c7f4b722d074250b2cfbb0f4c6ede1c.jpeg)

浏览题目界面
![只因在线做题系统-浏览题目界面](https://img-blog.csdnimg.cn/direct/08eda1c912434aedbdf135d0efebbe80.jpeg)

更新题目界面
![只因在线做题系统-更新题目界面](https://img-blog.csdnimg.cn/direct/510e7d8e1ee84cc18cecd2c16279a889.jpeg)

题目管理界面
![只因在线做题系统-题目管理界面](https://img-blog.csdnimg.cn/direct/3e942ebcc71c43afbee19c3a67d8ee87.jpeg)

## 根据后台生成代码

```shell
openapi --input http://localhost:8121/api/v2/api-docs --output ./generated --client axios
```


## Project setup

```
yarn install
```

### Compiles and hot-reloads for development

```
yarn serve
```

### Compiles and minifies for production

```
yarn build
```

### Lints and fixes files

```
yarn lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).
