# morepagecli

//本项目为webpack2.0+ vue 多页面自动构建打包配置+开发环境  //更多功能敬请期待 //作者很菜qq:534111616 wx:b83287403
//打包指令 npm run build
// 虚拟运行指令 npm run dev
// publicPath 配置资源绝对路径 必定要设置为根目录 比如 项目在 c盘下的 test文件里
    那么设置为 publicPath：'/test/webpack多页打包/list' 打包上线时改为线上绝对路径即可如:www.zaicd.com/public/webpack多页打包/list
// 在config.js 引用 公共 框架 或者库
// 在 每个 html文件里面的js文件引用私有的库
// 自行配置 url-loader limit 比如 limit=8000 表示转义8kb以下图片为bst64编码
