# testfronted

知构课程用的**静态**测试站点。根目录就是 `index.html`，不需要 pip / npm。

开发舱：

```text
git clone git@github.com:CarlYuHQ/testfronted.git
cd testfronted
run python3 -m http.server 8786 as web
```

浏览器打开 `http://主机:8786/`，应看到青绿卡片「知构测试作品」。

结束：`app stop web`
