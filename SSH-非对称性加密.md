## SSH
### 对称性加密
###　非对称性加密

### 配置SSH连接github
1. 在本地生成秘钥：ssh-keygen -t rsa
2. 找到秘钥生成的目录，将公钥放到Github中
    a、github点击右上角人物头像
    b、选择settings菜单
    c、选择SSH相关菜单
    d、选择添加一个SSH
    e、输入ssh的名称，已知内容（就是公钥）将公钥放入其中，保存即可
3. 在本地测试 ssh git@github.com看看是否成功
Hi chengxc! You've successfully authenticated, but GitHub does not provide shell access.
4. 以后在本机提交代码就不用再去输入用户名和密码了，提交代码的时候需要获取到该仓库的SSH地址(git@github.com:hahareg12345/conflict.git)，就可以直接提交代码
