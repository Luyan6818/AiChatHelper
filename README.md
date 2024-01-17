# 微信助手 ChatGPT 反向代理

欢迎来到微信助手 ChatGPT 反向代理项目！这个仓库帮助你部署 ChatGPT / Gemini-pro 反向代理，使其能够与懒猫的微信助手插件的 ChatGPT 功能协同工作。

## [cloudflare 分支](https://github.com/GeekinGH/AiChatHelper/tree/cloudflare-version)

1. 利用cloudflare workers 部署免费的反代，仅仅可用于懒猫的微信助手。
2. 由于 cloudflare 的 IP 不固定，导致 Gemini 的反代不稳定（）。
3. 目前个人使用来看，这个方式的 ChatGPT 反代是稳定的。
4. 它可能需要你拥有一个域名。

   
## [replit 分支](https://github.com/GeekinGH/AiChatHelper/tree/replit-version)

1. 由于 replit 的新政策，repl 的 dev 域名必须在编辑器使用期间才能访问，否则它会不定期停止运行。
2. 尝试了很多中保活措施，依旧不理想，对此方案已经不抱希望。
3. 依然希望使用的，请保持编辑器在线，同时开启第三方监控来定时产生请求来尝试保活 。

祝你在微信助手中体验愉快！
