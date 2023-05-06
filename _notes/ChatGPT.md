---
title: ChatGPT
---

# 如何访问
## 官方站点
虽然没有明说，但OpenAI并不欢迎中国用户使用ChatGPT：除了需要翻墙外，使用+86手机号无法注册，使用QQ等国内邮箱有概率无法注册（但.edu.cn的教育邮箱可以），国内的信用卡无法用于绑定扣款账户，使用港澳台代理有概率吃Access Denied，之前还出现过国内注册的账号大规模被封的现象。

请使用港澳台之外的海外代理，使用海外的[[虚拟手机号]]和Gmail注册，并尽可能选用稳定可靠的代理供应商。即便如此，随着OpenAI算力日益紧张，限制措施很可能进一步收紧，还请做好心理准备。

[这是官网](https://chat.openai.com/chat)，可以用邮箱或Google账号注册，**注册时必须验证手机号**，请使用[[虚拟手机号]]验证。手机号码只有注册时需要，后续登录不再需要，因此可以买那种有效期几分钟的一次性号码。

由于官网经常限流，bug一堆，高峰期速度感人，

## 第三方站点
- [poe.com](poe.com)，这里除了ChatGPT，还有Sage、Claude等其它语言模型，与ChatGPT定位相近，实际性能可以自行体验。这是一个免费站点，但UI不太好用，而且目前不能渲染Markdown语法。
- [xx025/carrot](https://github.com/xx025/carrot)和[LiLittleCat/awesome-free-chatgpt](https://github.com/LiLittleCat/awesome-free-chatgpt)，这里集中收录了第三方ChatGPT站点，Github上类似的仓库应该不止这俩。收录的站点非常多并且持续更新，使用时建议货比三家。

需要注意的是：
1. 第三方站点使用的是OpenAI提供的接口，可以使用的最新模型是`gpt-3.5-turbo`，与ChatGPT官方站点使用的是同一个模型。在特定领域性能接近ChatGPT的竞品已经出现，但ChatGPT依然是认可度最高的那个。
2. 调用接口需要按文本的token数计费，对于`gpt-3.5-turbo`，中文文本每个汉字消耗大约1.1个token，价格是0.002/1k tokens（详见[Pricing](https://openai.com/pricing)），而且包括回答在内的整个聊天上下文都参与token的计算。**开放免费的第三方站点是非常烧钱的慈善行为**。请在个人能力范围内支持开发者，使用时心怀感恩。
3. 

# 使用心得
## 