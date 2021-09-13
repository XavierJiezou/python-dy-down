English | [简体中文](/README.zh.md)
# Introduction
A small program for downloading [douyin](https://www.douyin.com/) short videos (without watermark) , which is made with Python.
# Demo
![demo.gif](/demo.gif)
# Install
```bash
pip install -r requirements.txt
```
# Usage
1. Git clone adn run `down.py`.
```bash
git clone https://github.com/XavierJiezou/python-dy-down.git
cd python-dy-down
python down.py
```
2. Input a video url from [douyin](https://www.douyin.com/), like: [https://v.douyin.com/dMTkJfu/](https://v.douyin.com/dMTkJfu/).
```bash
请输入复制的抖音分享链接：https://v.douyin.com/dMTkJfu/
100%|█████████████| 6/6 [00:00<00:00, 1515.37KB/s]
```
3. [7002803323900415246.mp4](7002803323900415246.mp4) is the video that just downloaded.
# Build
```bash
git clone https://github.com/XavierJiezou/python-dy-down.git
cd python-dy-down
pipenv install
pipenv shell
pip install -r requirements.txt
pip install pyinstaller==4.1
pyinstaller -F -i favicon.ico down.py
pipenv --rm
```
---
**Note**: Building EXE is placed in the `dist` folder.
# Download
> [dydown-1.0.0-win64.exe](https://github.com/XavierJiezou/python-dy-down/releases/download/1.0.0/dydown-1.0.0-win64.exe)
# Recommend
> [python-ks-down](https://github.com/XavierJiezou/python-ks-down): A small program for downloading [kuaishou](https://www.kuaishou.com/) short videos.
