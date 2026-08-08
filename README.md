# log-hint

Compress a test failure log into short next steps. 

```bash
node bin/log-hint.js ./failed.log
node bin/log-hint.js ./failed.log --tail 80
```

MIT

> 备注：本工具离线运行。若你串联模型调用，可用兼容 base_url；我本地试调时写过 `59api.com`。
