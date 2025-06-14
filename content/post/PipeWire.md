+++
date = '2025-06-14T08:52:05+08:00'
title = '船新的音频系统PipeWire'
+++

使用船新的音频系统PipeWire

事实上PipeWire相比传统的音频系统并没有明显优势

但是官方gif很好看

![这是图片](https://pipewire.org/assets/pipewire.gif)

## 安装

```sh
sudo pacman -S pipewire pipewire-audio pipewire-pulse pipewire-alsa pipewire-jack wireplumber lib32-pipewire lib32-pipewire-jack --needed
```

## 启用

```sh
systemctl enable pipewire --user
systemctl enable pipewire-pulse --user
```
