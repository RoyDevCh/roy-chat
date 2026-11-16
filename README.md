# Roy Chat

一个单文件、零依赖的网页聊天界面，直连 DeepSeek API（OpenAI 兼容格式）。

- 打开页面 → 右上角「设置」→ 填 API Key → 开始对话
- Key 和对话历史只保存在浏览器 localStorage，不会发往 `api.deepseek.com` 以外的任何地方
- 支持流式输出、深度思考内容折叠、代码块渲染
- 不引用任何 CDN，断网之外不依赖第三方资源

接口默认 `https://api.deepseek.com`，模型默认 `deepseek-flash`，可在设置里改。

> 这是个人自用页面：任何打开它的人用的都是自己的 key，仓库里不包含任何凭据。
