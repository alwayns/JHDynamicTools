# JHDynamicTools功能
##  JHTools工具能够动态分布式打包，但局限性是我们掌握游戏工程的情况下，但对于游戏来说，很多时候拿不到原始工程，iOS不像安卓拥有母包可以用来进行分包经过试验，在JHTools工具基础上，将core库以及渠道库全部改为动态库，并且将渠道库固定为CommonSDK库，通过CommonSDK库包含渠道SDK库，再将CommonSDK通过core库进行插件式加入，利用core库和运行时调用CommonSDK，那么在ipa包已经生成的情况下，我们任然能对库进行替换，并修改参数来达到生成渠道马甲包的目的。
##  目前JHDynamicTools还在初步试验阶段，替换库以及修改参数等功能只能手动完成，待稳定后，跟JHTools一样实现脚本替换，更方便。
##  JHDynamicTools还在初步摸索阶段，欢迎大佬提供更优方案，若有错误欢迎指出。
