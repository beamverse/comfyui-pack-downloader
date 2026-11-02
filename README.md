# ComfyUI 离线安装包下载工具

把 ComfyUI 离线安装包下载到移动硬盘，再把硬盘插到 GPU 服务器上安装
需要管理员发的下载码

本仓库只发布程序，请到 [Releases](https://github.com/beamverse/comfyui-pack-downloader/releases/latest) 下载

- [Windows](https://github.com/beamverse/comfyui-pack-downloader/releases/latest/download/comfyui-pack-download.exe)
- [Linux（x86-64）](https://github.com/beamverse/comfyui-pack-downloader/releases/latest/download/comfyui-pack-download-linux-amd64)
- Mac（M系列芯片）：不要用浏览器下载会被系统拦截。打开终端，粘贴下面一行，按回车：

```bash
curl -fL -o ~/comfyui-pack-download https://github.com/beamverse/comfyui-pack-downloader/releases/latest/download/comfyui-pack-download-macos-arm64 && chmod +x ~/comfyui-pack-download && ~/comfyui-pack-download
``
Mac上用的移动硬盘必须是 exFAT格式，否则服务器读不了
