libyuv-original
---

# 简介
* 在使用了chrome下的libyuv和libyuv-android导致部分交叉功能无法使用。创建改项目来完善libyuv下的所有功能。

* 并使用该库下生成的静态库完成android下的实际使用情况：
[libyuv-tool]<https://github.com/Yangandmore/yuv-tool>

* 该库下所有完善的功能均以上述库下的功能为主。

# 使用
* 修改***Application.mk***和***Android.mk***

# 编译
```
ndk-build clean
ndk-build
```
