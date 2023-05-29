## 参考链接

[本地安装 ChatGPT！无需API、 免翻墙、完全免费使用纯正OpenAI的全部功能！ 支持 Windows、 Mac、NAS、Linux系统 | 零度解说](https://www.youtube.com/watch?v=gKmawmUw7Jo)



# 本地安装 ChatGPT！无需API、 免翻墙、完全免费使用纯正OpenAI的全部功能！ 支持 Windows、 Mac、NAS、Linux系统 | 零度解说博客

https://www.freedidi.com/9557.html

1. 下载并安装Docker 【[官网下载](https://www.docker.com/)】
2. 使用开源项目：潘多拉 (Pandora) 【[github](https://github.com/pengzhile/pandora)】
3. 一键安装命令

```
docker pull pengzhile/pandora
```

```
docker run  -e PANDORA_CLOUD=cloud -e PANDORA_SERVER=0.0.0.0:8899 -p 8899:8899 -d pengzhile/pandora
```



4. 获取自己的 Access TOKEN：http://chat.openai.com/api/auth/session
5. 访问本地链接：http://127.0.0.1:8899 即可搞定！

