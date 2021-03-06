# Fun

(have)Fun with Serverless

![logo.jpg](https://tan-blog.oss-cn-hangzhou.aliyuncs.com/img/20181123143028.png)

[中文文档](https://github.com/aliyun/fun/blob/master/README-zh.md)

[Fun](https://github.com/aliyun/fun) is a development tool for serverless applications. It can help you to efficiently arrange cloud resources such as Function Compute, API Gateway, Log Service and so on. You can use it to develop，build and deploy FC by describing relative resources in a `template.yml` file.

If you want to use the old syntax, please refer to [README.md](https://github.com/aliyun/fun/blob/v1.x/README.md).

## Get Started

As a command-line tool, Fun has built-in subcommands such as config, local, deploy, and so on.

The config subcommand can be used to configure fun, the local subcommand can be used to run the debugging function locally, and the deploy subcommand can publish your resources.

We have prepared a series of tutorials to help you use the Fun tool more easily:

- [Installation](https://github.com/aliyun/fun/blob/master/docs/usage/installation.md): Learn how to install Fun on Mac, Linux or Windows.
- [Getting Started](https://github.com/aliyun/fun/blob/master/docs/usage/getting_started.md): The basic usage of Fun is introduced with a simple example.
- **Running and debugging locally**: A series on how to run locally, debug functions, and tips on troubleshooting related issues.
  - [Guidelines for Function Compute Development - Use Fun Local for Local Running and Debugging](https://yq.aliyun.com/articles/686333): Introduced the basic usage of Fun Local.
  - [Guidelines for Function Compute Development - Crawler](https://yq.aliyun.com/articles/686340): How to use the Fun tool to develop a Serverless application from scratch.
  - [Guidelines for Function Compute Development - Troubleshoot Timeout Issues](https://yq.aliyun.com/articles/686349): Demonstrates how to solve a series of bugs and introduces the tricks of debug.
  - [开发函数计算的正确姿势 —— Http Trigger 本地运行调试](https://yq.aliyun.com/articles/683683):  Demonstrates how to run and debug Http Trigger functions locally.
  - [开发函数计算的正确姿势 —— 本地运行、调试、发布 NAS 函数](https://yq.aliyun.com/articles/683684):  Demonstrates how to run and debug functions configured with NAS services locally.
  - [开发函数计算的正确姿势 —— Api 本地运行调试](https://yq.aliyun.com/articles/683685):  Demonstrates how to run and debug functions locally through the API.
  - [开发函数计算的正确姿势 —— 开发 WordPress 应用](https://yq.aliyun.com/articles/683686): Demonstrates how to develop and debug a WordPress web application locally.
  - [开发函数计算的正确姿势 —— 开发 NAS 文件管理应用](https://yq.aliyun.com/articles/685803): Demonstrates how to develop and debug a NAS file manager web application locally.
- [Specification](https://github.com/aliyun/fun/blob/master/docs/specs/2018-04-03.md): Introduces the syntax of the fun's template.yml file.
- [FAQ](https://github.com/aliyun/fun/blob/master/docs/usage/faq.md): Frequently asked questions and answers when using fun.
- [More Examples](https://github.com/aliyun/fun/tree/master/examples)

## References

- [以函数计算作为 API 网关后端服务](https://help.aliyun.com/document_detail/54788.html)
- [函数计算](https://www.aliyun.com/product/fc)
- [API Gateway](https://www.aliyun.com/product/apigateway)
- [Fun 发布 2.0 新版本啦](https://yq.aliyun.com/articles/604490)
- [函数计算工具链新成员 —— Fun Local 发布啦](https://yq.aliyun.com/articles/672656)
- [三十分钟快速搭建 serverless 网盘服务](https://yq.aliyun.com/articles/613780)
- [Fc Docker](https://github.com/aliyun/fc-docker)

## License

The MIT License
