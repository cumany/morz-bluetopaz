# 蓝托帕石 / Blue Topaz for Morz

Morz 的第一个市场主题：Blue Topaz 的 Morz 适配版，保留上游的视觉签名——托帕蓝、
蓝色标题阶梯（暗色下绿→青→蓝→紫）、着色引言、圆角代码/表格卡片——不含 Obsidian 专属 UI。

上游主题：[Blue Topaz](https://github.com/PKM-er/Blue-Topaz_Obsidian-css)，
由 whyt-byte 与 PKMer 社区维护，MIT 许可。本适配版同样 MIT，署名见 [LICENSE](LICENSE)。

## 安装

Morz → **设置 → 外观 → 主题市场** → 选择「蓝托帕石」→ 安装。
明暗两套变体随「深色模式」偏好自动切换，无需额外插件。

## 文件

| 文件 | 用途 |
|---|---|
| `theme.css` | 浅色变体 |
| `theme-dark.css` | 深色变体（写作面 `--bt-bg: rgba(21,21,21,.85)`，与侧栏透明度对齐） |
| `export.css` | 导出 HTML/PDF 时的精修规则（页码、书签排版） |

## 自定义

设置 → **自定义 CSS** 可直接覆盖；主题暴露稳定的 `--bt-*` 变量集。
深色写作面等细节说明见 Morz 帮助中心。
