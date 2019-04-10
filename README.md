#### 项目描述:

- 此项目为前后台分离的招聘的SPA(单页应用),保罗前段应用和后端应用
- 包括用户注册/登录,实时聊天等模块
- 前段使用:React全家桶+ES6+webpack(打包工具)等技术
- 后端:使用Node+express+mongodb+socketIO等技术
- 采用模块化,组件化,工程化的模式开发

> 模块化:
> 组件化:
> 工程化:

> 技术选型(确定当前项目主要用到的技术):
> 技术选型

> 编码测试打包发布项目
>
> - 编码测试:
>   npm start
>   访问:localhost:3000
>   编码:自动编译打包刷新(live-reload)
> - 打包发布:
>   npm run build
>   npm install -g serve
>   serve build
>   访问:localhost:5000

### 项目步骤说明：

> 安装下载：
> npm install antd-mobile --save

> 对于移动端viewport：
>
>   <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, minimum-scale=1, user-scalable=no" />

> 对于移动端点击延迟0.3秒问题
>
> <script src="https://as.alipayobjects.com/g/component/fastclick/1.0.6/fastclick.js"></script>
>     <script>
>       if ('addEventListener' in document) {
>         document.addEventListener('DOMContentLoaded', function() {
>           FastClick.attach(document.body);
>         }, false);
>       }
>       if(!window.Promise) {
>         document.writeln('<script src="https://as.alipayobjects.com/g/component/es6-promise/3.2.2/es6-promise.min.js"'+'>'+'<'+'/'+'script>');
>       }
>     </script>