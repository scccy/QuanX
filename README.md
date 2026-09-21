# quanx

Quantumult X 自用分流规则。

## 订阅

在 QX 配置的 `[filter_remote]` 中添加：

    https://raw.githubusercontent.com/scccy/quanx/main/USGames.list, tag=美区游戏, force-policy=美区游戏, update-interval=86400, opt-parser=true, enabled=true

需在配置 `[policy]` 中存在同名策略组 `美区游戏`，例如：

    static=美区游戏, 美国节点, 自动选择, direct, proxy
