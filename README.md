## BOM = Browser Object Model 浏览器对象模型
### window对象 
* 输出API：alert(), prompt(), conﬁrm(), console() 
* 定时器： setTimeout(), setInterval() 
* 页面位置： Location对象 
* 页面历史： History对象 
* 浏览器特征： Navigator对象 
* 更多的页面： window.open(),  window.opener 
* 嵌套页面：Frame对象 

#### Location对象 
* location.assign(url)：页面载⼊入指定的url 
* location.replace(url)：页面载⼊入url，并在跳转之前从浏览历史中删除当前⽂文档 
* location.reload()：重新载入当前页面

#### History对象 
* history.back()：退回到上次浏览器的页面，相当于浏览器的“后退”按钮 
* history.forward()： 相当于浏览器的“前进”按钮 •
* history.go(number)： 去往第number次浏览器的页面

#### Navigator对象 
* navigator.appName： 浏览器全称 
* navigator.appVersion： 当前版本 
* navigator.userAgent： 更详细的浏览器版本信息 
* navigator.platform： 当前运⾏行浏览器的操作系统平台名称


## DOM = Document Object Model

#### 从⽂文档中获取指定的元素
* 根据元素的ID获取元素：getElementById⽅方法
* 根据元素的name获取元素：getElementsByName⽅方法 
* 根据标签名称获取元素：getElementsByTagName⽅方法 
* 根据CSS类名称获取元素： getElementsByClassName⽅方法  在IE8及一下的版本中不支持
* 根据CSS选择器获取元素： querySelectorAll⽅方法  在IE8及一下的版本中不支持

