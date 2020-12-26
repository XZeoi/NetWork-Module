#### request网络模块的使用
使用axios前，一定要先安装axios框架

//在其他地方使用
//	1、导入封装的request模块
import {request} from './network/request'

//	2、调用request
request({
  url: '//...',
  method: 'get'
}).then(res => {
  
}).catch(err => {
  
})

