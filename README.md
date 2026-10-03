# Loon 插件图标

此仓库保存用户提供的两个 App 图标及校验信息，不包含脚本、账户信息或代理配置。图标的商标及原有权利属于对应权利人。

## 网易云音乐

采用用户提供的 `sources/neteasecloudmusic.svg`。原始 SVG 按字节保留；`netease-cloud-music.svg` 只增加品牌填充色 `#D43C33`，路径、viewBox、填充规则与透明区域保持原样。由 rsvg-convert 导出 512 × 512 的透明 `netease-cloud-music.png`，供 Loon 的 `#!icon` 使用。旧 PNG 仍可通过此前的固定修订链接访问。

## 看理想

`kanlixiang.png` 为用户提供的 512 × 512 PNG 原图，字节保持原样。插件继续使用原固定修订链接。

各文件的 SHA-256 见 `SHA256SUMS`；来源、颜色和导出信息见 `manifest.json`。
