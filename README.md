# Behinder-clone

本项目基于[Behinder_V3.0 Beta2](https://github.com/rebeyond/Behinder/releases/tag/Behinder_v3.0_Beta_2)进行修改，
仅供内存webshell的研究与测试

## 修改内容

修改内容为更改了连接的逻辑，equals方法不再传递pageContext，而是传递一个Object数组，数组内包含reuquest,response,以及session
