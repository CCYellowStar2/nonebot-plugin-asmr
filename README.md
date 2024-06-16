<div align="center">
  <a href="https://v2.nonebot.dev/store"><img src="https://github.com/A-kirami/nonebot-plugin-template/blob/resources/nbp_logo.png" width="180" height="180" alt="NoneBotPluginLogo"></a>
  <br>
  <p><img src="https://github.com/A-kirami/nonebot-plugin-template/blob/resources/NoneBotPlugin.svg" width="240" alt="NoneBotPluginText"></p>
</div>

<div align="center">

# nonebot-plugin-asmr

_✨ 一个简易的能在群里听音声的插件 ✨_


<a href="./LICENSE">
    <img src="https://img.shields.io/github/license/CCYellowStar2/nonebot-plugin-asmr.svg" alt="license">
</a>
<a href="https://pypi.python.org/pypi/nonebot-plugin-asmr">
    <img src="https://img.shields.io/pypi/v/nonebot-plugin-asmr.svg" alt="pypi">
</a>
<img src="https://img.shields.io/badge/python-3.9+-blue.svg" alt="python">

</div>

## 📖 介绍

简易的调用asmr.one站api的asmr插件，可以在群里查询音声和生成音声音乐卡片，因为是音乐卡片所以电脑端ntqq听不了

## 💿 安装

<details open>
<summary>使用 nb-cli 安装</summary>
在 nonebot2 项目的根目录下打开命令行, 输入以下指令即可安装

    nb plugin install nonebot-plugin-asmr

</details>

<details>
<summary>使用包管理器安装</summary>
在 nonebot2 项目的插件目录下, 打开命令行, 根据你使用的包管理器, 输入相应的安装命令

<details>
<summary>pip</summary>

    pip install nonebot-plugin-asmr
</details>
<details>
<summary>pdm</summary>

    pdm add nonebot-plugin-asmr
</details>
<details>
<summary>poetry</summary>

    poetry add nonebot-plugin-asmr
</details>
<details>
<summary>conda</summary>

    conda install nonebot-plugin-asmr
</details>

打开 nonebot2 项目根目录下的 `pyproject.toml` 文件, 在 `[tool.nonebot]` 部分追加写入

    plugins = ["nonebot_plugin_asmr"]

</details>

## 🎉 使用
### 指令表
| 指令 | 权限 | 需要@ | 范围 | 说明 |
|:-----:|:----:|:----:|:----:|:----:|
|听音声 RJxxx 编号（可选） | 群员 | 否 | 群聊 | 查询相关rj号音声，再发序号生成音乐卡片 |
|搜音声 伪娘/催眠 1（可选） | 群员 | 否 | 群聊 | 搜索音声语音（用”/”分割不同tag）|
### 效果图
![Screenshot_20240616_202944](https://github.com/CCYellowStar2/nonebot_plugin_asmr/assets/149048350/ea5693c0-8799-4546-ad2b-46bcd383ce9a)
![Screenshot_20240616_202951](https://github.com/CCYellowStar2/nonebot_plugin_asmr/assets/149048350/707107a7-67d3-4f5c-9cff-7672bf537104)

## 💡 鸣谢

### [asmr.one](https://asmr.one/)
- 音声资源站

