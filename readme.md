1. 将 auth_client 和.auth-setting 文件放到用户目录下。
2. 更改 auth_client 文件权限为可执行。
3. 登录：
在用户目录下执行 ./auth_client -u 用户名 -p 用户密码 auth
4. 登出：
在用户目录下执行 ./auth_client -u 用户名 auth --logout
5. 帮助：
在用户目录下执行./auth_client check 可以检查用户的在线状态
