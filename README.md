# EzbotSup
Easybot的多元化仓库，方便，快捷实现安装
[![Docker Pulls](https://img.shields.io/docker/pulls/zzh4141/easybot-docker)](https://hub.docker.com/r/zzh4141/easybot-docker)
[![Docker Image Size (tag)](https://img.shields.io/docker/image-size/zzh4141/easybot-docker/latest)](https://hub.docker.com/r/zzh4141/easybot-docker)
[![Docker Stars](https://img.shields.io/docker/stars/zzh4141/easybot-docker.svg)](https://hub.docker.com/r/zzh4141/easybot-docker)

## 介绍
`EzbotSup` 是一个旨在简化 `EasyBot` 在各种服务器可视化管理面板中安装部署的项目。

适配进度
- [√] 1panel
- [ ] 飞牛系统
- [ ] ... (欢迎提交 PR)

## 🚀 安装指南
### 1Panel

1.  访问本仓库的 [Releases](https://github.com/easybot-team/EzbotSup/releases/tag/1panel) 页面，下载最新的 `*-1panel.zip` 压缩包。

2.  将下载的压缩包上传至 1Panel 服务器的以下目录：
    ```bash
    /opt/1panel/resource/apps/local
    ```
    并且解压所上传的压缩包
    > **注意**: `/opt` 是 1Panel 的默认安装目录。如果您的安装目录不同，请相应地修改路径。

3.  登录到 1Panel 后台，进入 **应用商店**，然后点击右上角的 **更新应用列表** 按钮，同步本地应用。

4.  在应用列表中找到 **EasyBot**，点击 **安装** 并根据提示完成即可。

## 🤝 贡献

欢迎各种形式的贡献！如果您有兴趣为 `EzbotSup` 做出贡献，请随时 Fork 本仓库并发起 Pull Request。

您可以：

- 适配新的服务器管理面板。
- 修复 Bug。
- 完善文档。

---
