# DBUltimate

验证分析学习

1.       生成一对RAS加解密使用的公钥和私钥；

2.       将com.dbeaver.app.ultimate_*.jar中的公钥替换成自己生成的公钥；

3.       用自己的私钥生成一个License文件导入；

4.       绕过网络校验。
(1)在hosts文件中配置dbeaver.com的IP为127.0.0.1；
(2)在配置文件dbeaver.ini中设置lm.debug.mode=true的值

## 测试环境

支持操作系统：Windows10、11、Linux、IOS

Java版本：JDK8、11、12、17

V1软件版本：UE 23.3.0


V2软件版本：UE 24.0.0及以后版本

最新版本24需要调整一下引入的jar依赖，原来的 org.jkiss.lm_*.jar 改为 com.dbeaver.lm.**.jar 然后修改一下import 路径即可，其他不变

❤️ 仅供学术研究
