#linux服务器监控平台
技术：nodejs vue java mongodb springboot linux shell

前台配置后台请求地址：
在文件：db-service-monitoring\src\axios\axiosUrl.js
/**
 * 配置全局使用的请求地址url
 *  11.24.201.68
 *  192.168.0.5
 */
export default {
  rootDirectory: function () { // 请求接口的根路径
    return 'http://192.168.0.26:9999'
  },
  
1、启动前台：
使用命令：先控制台cmd命令切换到项目目录：db-service-monitoring 
后执行：npm run dev
启动后显示如下信息
 DONE  Compiled successfully in 16239ms                                                                                                                         16:44:38

 I  Your application is running here: http://localhost:8083
 
 
 
 2、后台启动类
 com.example.DemoApplication
 
 
