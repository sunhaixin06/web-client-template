# 简介  
  本项目为基于 React/Redux 以及 Ant Design 的Web前端模板。 

# TODO  
**在项目初始化时，应完成以下内容：**  
1. 修改`package.json`  
    - 项目信息：name、repository  
    - 更新 dependencies、devDependencies 组件版本  
1. 修改`conf/tools.conf.js`  
    - 调整项目名称：runtime.title  

# 本地运行  
  ~~~bash
  npm run server    在本机 3000 端口上运行开发调试环境
  npm run lint      使用 eslint 进行代码风格检查
  npm run build     编译发布文件至 build 目录
  ~~~

# 常用参数  
**参数设置仅针对当前环境有效**  
## tools.conf.js  
   - dev：开发调试环境`地址`、`端口`、`静态资源目录`设置  
   - runtime：client 入口参数设置  
   - mock：api 入口参数设置  
> 更多设置请参考 [web-tools](https://gitlab.sdtdev.net/rd/web/web-tools/blob/develop/README.md)