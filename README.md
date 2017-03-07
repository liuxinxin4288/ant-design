之前遇到的问题 包括 之前下载的node版本低 卸载的时候出问题 然后重新安装3.0以上版本的node
然后npm install antd-init的时候 一直报error，如下图
![Alt text](./1488763667866.png)
然后解决方法是设置代理
奈何安装代理设置成功之后还是安装不成功
最后通过镜像解决

```
npm config set registry https://registry.npm.taobao.org
```

![Alt text](./1488764384457.png)
现在可能已经安装成功 但是为啥不能输入了啊啊啊啊啊 都是坑
![Alt text](./1488770211922.png)
安装不了 甚至连cmd窗口都无法正常关闭==
![Alt text](./1488781962121.png)
上图遇到了operation not permitted的错误 因此 用管理员的身份运行命令
![Alt text](./1488782608909.png)



啦啦啦啦 成功之后 还是有坑哈哈哈哈
![Alt text](./1488783597633.png)
按照文档修改完index之后== oh my godden

![Alt text](./1488854506228.png)
普天同庆