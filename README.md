<p align="center"><img src="https://wyz-xyz.oss-cn-huhehaote.aliyuncs.com/2022-07-16/1657940551-778457-frame-1.jpg" width="100%"></p>

<p align="center">
<a href="http://www.nxime.com"><img src="https://img.shields.io/badge/version-3.2.9-green" alt="Build Status"></a>
<a href="http://www.nxime.com"><img src="https://img.shields.io/badge/laravel-10.0-%23ef3b2d" alt="Total Downloads"></a>
<a href="http://www.dcatadmin.com/"><img src="https://img.shields.io/badge/dcatadmin-2.0.0-%234c5ec2" alt="Latest Stable Version"></a>
<a href="http://www.nxime.com"><img src="https://img.shields.io/badge/MYSQL-8.0-%2300758f" alt="License"></a>
</p>

## 关于 Nxcrm
 ---

NXCRM 是一套基于 Laravel 的 CRM 应用程序。它包含了一个管理中心，可以管理用户、客户、产品、订单、商机，合同，收款，附件，联系人，跟进动态，发票，业绩目标，团队管理，消息通知等等。NXCRM设计简约但功能并不简单。在囊括了上百项几乎满足绝大多数企业的管理功能的同时，我们始终让设计保持简约，而不是让它变得复杂。也因此理念，NXCRM在诸多CRM应用程序中保持着自己独具一格的设计特色，令人耳目一新。 
  
    
##### DEMO：
https://crm.demo.nxime.com



## 系统截图
 ---
 ![](https://wyz-xyz.oss-cn-huhehaote.aliyuncs.com/2022-07-16/1657955894-153994-frame-1.png)
![](https://wyz-xyz.oss-cn-huhehaote.aliyuncs.com/2022-07-16/1657955779-55971-frame-2.png)
![](https://wyz-xyz.oss-cn-huhehaote.aliyuncs.com/2022-07-16/1657956032-996617-frame-2.png)
![](https://wyz-xyz.oss-cn-huhehaote.aliyuncs.com/2022-07-16/1657956865-534180-frame-2.png)
![](https://wyz-xyz.oss-cn-huhehaote.aliyuncs.com/2022-07-16/1657956285-614775-frame-2.png)
![](https://wyz-xyz.oss-cn-huhehaote.aliyuncs.com/2022-07-16/1657956583-634749-frame-2.png)
![](https://wyz-xyz.oss-cn-huhehaote.aliyuncs.com/2022-07-16/1657956708-49788-frame-2.png)
![](https://wyz-xyz.oss-cn-huhehaote.aliyuncs.com/2022-07-16/1657957094-184481-frame-2.png)
![](https://wyz-xyz.oss-cn-huhehaote.aliyuncs.com/2022-07-16/1657957855-287145-frame-2.png)

 ## 安装
 ---

本仓库提供完整的中文安装与使用教程：

- [安装教程](docs/安装教程.md)：环境准备、全新安装、`.env` 配置、当前本机启停、安装验收与故障排查。
- [使用教程](docs/使用教程.md)：账号权限、线索客户、跟进、商机合同、收款发票、导入、合同生成、公海及消息提醒。
- [部署与维护](docs/部署与维护.md)：Nginx 部署、定时任务、异步队列、备份恢复和升级。

当前电脑已配置的后台地址为 <http://127.0.0.1:8000/admin>。全新安装的初始账号为 `admin/admin`，登录后请修改密码。其他电脑从安装教程的“全新安装”开始。

**已有业务数据时不要重复运行 `php artisan nxos:install`。** 该命令会重新生成密钥、重置管理员及部分配置数据；升级前请阅读部署与维护教程。

原项目 Wiki：https://gitee.com/shebaoting/nxcrm/wikis/


 ## 其他说明
  ---
既然开源，文件以及代码就是完整的。不会刻意的去减少什么文件，或者故意增加大家的安装门槛。系统是基于laravel 开发，遇到问题可以提issue或者自己想办法解决一下。平时工作忙，所以很抱歉不能对所有用户提供人工支持。如果有急于解决的问题，可以寻求付费解决。

## 鸣谢
 ---
`Nxcrm` 基于以下组件:

+ [Laravel](https://laravel.com/)
+ [Dact Admin](http://www.dcatadmin.com/)
+ [Laravel Admin](https://www.laravel-admin.org/)
+ [AdminLTE3](https://github.com/ColorlibHQ/AdminLTE)
+ [bootstrap4](https://getbootstrap.com/)
+ [jQuery3](https://jquery.com/)
+ [Eonasdan Datetimepicker](https://github.com/Eonasdan/bootstrap-datetimepicker/)
+ [font-awesome](http://fontawesome.io)
+ [jquery-form](https://github.com/jquery-form/form)
+ [moment](http://momentjs.com/)
+ [webuploader](http://fex.baidu.com/webuploader/)
+ [bootstrap-fileinput](https://github.com/kartik-v/bootstrap-fileinput)
+ [jquery-pjax](https://github.com/defunkt/jquery-pjax)
+ [Nestable](http://dbushell.github.io/Nestable/)
+ [toastr](http://codeseven.github.io/toastr/)
+ [editor-md](https://github.com/pandao/editor.md)
+ [fontawesome-iconpicker](https://github.com/itsjavi/fontawesome-iconpicker)
+ [layer弹出层](http://layer.layui.com/)
+ [waves](https://github.com/fians/Waves)
+ [bootstrap-duallistbox](https://www.virtuosoft.eu/code/bootstrap-duallistbox/)
+ [char.js](https://www.chartjs.org)
+ [nprogress](https://ricostacruz.com/nprogress/)
+ [bootstrap-validator](https://github.com/1000hz/bootstrap-validator)
+ [Google map](https://www.google.com/maps)
+ [Tencent map](http://lbs.qq.com/)
