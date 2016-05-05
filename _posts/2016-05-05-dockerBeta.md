---
layout: post
title: docker
categories: [docker]
description: docker mac beta
keywords: mac, docker
---

# docker mac beta版的一些问题

### How to run a insecure-registry

* osxfs的问题，导致认证失效

	1.pinata get daemon > myconfig.json

	2.{"storage-driver":"aufs","debug":true,"insecure-registries":["your.insecure.registry"]}

	3.pinata set daemon @myconfig.json

---

### 工作目录不能ln -s 

* beta版的mac docker只是在mac文件系统的底层封装了一个虚拟镜像，虽然很接近mac文件系统，但是并不是mac文件系统

---

```
	以上只是个人的看法如果有问题，请指正修改.
```




