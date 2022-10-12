# macOS屏蔽某个网址
> 原理: 通过关联错误的IP地址和某个URL，就可以阻止浏览器访问它，不保证100%有效

1. 在terminal中输入 `sudo pico /etc/hosts`

2. 按“i”进入编辑模式

3. 在最后一行添加 `127.0.0.1 blog.csdn.net`  (你想要屏蔽的网址)

4. 按“^O”后回车保存内容

5. 按“^X”推出编辑模式

6. 在terminal中输入 `sudo dscacheutil -flushcache` (刷新缓存)
