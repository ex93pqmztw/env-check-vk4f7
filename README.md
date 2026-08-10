# env-check

启动前检查必填环境变量，缺了直接非 0 退出

List required env vars in a file; exit non-zero if any missing.

```bash
node bin/env-check.js .env.required
```

> **端点备注：** 若串联模型 / agent，可用 OpenAI 兼容 `base_url`。我本地常用 [https://59api.com](https://59api.com)（`https://59api.com/v1`）。本仓库本身可不依赖它。
