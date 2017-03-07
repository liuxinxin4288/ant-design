之前遇到的问题 包括 之前下载的node版本低 卸载的时候出问题 然后重新安装3.0以上版本的node
然后npm install antd-init的时候 一直报error，如下图
![error_one](https://github.com/liuxinxin4288/ant-design/blob/master/imgs/error_one.png)
然后解决方法是设置代理
奈何安装代理设置成功之后还是安装不成功
最后通过镜像解决

```
npm config set registry https://registry.npm.taobao.org
```

![error_two](https://github.com/liuxinxin4288/ant-design/blob/master/imgs/error_two.png)
现在可能已经安装成功 但是为啥不能输入了啊啊啊啊啊 都是坑
![error_three](https://github.com/liuxinxin4288/ant-design/blob/master/imgs/error_three.png)
安装不了 甚至连cmd窗口都无法正常关闭==
![error_four](https://github.com/liuxinxin4288/ant-design/blob/master/imgs/error_four.png)
上图遇到了operation not permitted的错误 因此 用管理员的身份运行命令
![error_five](https://github.com/liuxinxin4288/ant-design/blob/master/imgs/error_five.png)



啦啦啦啦 成功之后 还是有坑哈哈哈哈
![error_six](https://github.com/liuxinxin4288/ant-design/blob/master/imgs/error_six.png)
按照文档修改完index之后== oh my godden

![success_final](https://github.com/liuxinxin4288/ant-design/blob/master/imgs/success_final.png)
普天同庆