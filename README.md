# gemini-shadowrocket-rules

Gemini 2026 Shadowrocket Rules

## 订阅链接（Shadowrocket RULE-SET 直链）

复制下面这条链接，粘贴到小火箭里使用：

```
https://raw.githubusercontent.com/Anke66666/gemini-shadowrocket-rules/main/Gemini_2026_Shadowrocket.list
```

## 在 Shadowrocket（小火箭）中使用

1. 复制上面的订阅链接
2. 打开小火箭 →「配置」→ 进入当前正在用的配置文件的编辑页面 →「规则」→ 添加规则 → 类型选 RULE-SET
3. URL 粘贴订阅链接，策略选自己的代理组/节点，保存
4. 回到首页，运行模式选「规则」模式，打开连接即可

也可以编辑配置文件纯文本，在 [Rule] 段、FINAL 那一行之前加一行（PROXY 换成自己的代理组名）：

```
RULE-SET,https://raw.githubusercontent.com/Anke66666/gemini-shadowrocket-rules/main/Gemini_2026_Shadowrocket.list,PROXY
```

说明：仓库里更新规则文件后，小火箭中的规则集会自动更新，不需要重新复制链接。
