## 0.5.0(2020-04-13)
* 新增：新增控制台 log 日志显示开启/关闭功能；
* 新增：新增 logout() 接口；

## 0.4.0(2020-03-30)
* 新增：新增 init() 接口，在调用 init() 接口之前，采集的数据被缓存在内存中；调用 init() 接口后，会将缓存的数据通过网络发送出去；

## 0.3.0（2020-03-06）
* 优化：​去除了 sensorsdata_conf.js文件，初始化时通过 setPara() 方法配置参数；
* 修复：修复页面路径 $url_path 有时获取不到的 bug；
* 新增：新增渠道追踪功能；

## 0.2.0
* 优化：修改$os的取值

## 0.1.0
* 第一个版本