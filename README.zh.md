简体中文 | [English](/README.md)
# 简介
用Python制作的，一个下载[抖音](https://www.douyin.com/)无水印短视频的小程序。
# 演示
![demo.gif](/demo.gif) 
# 安装
```bash
pip install -r requirements.txt
```
# 用法
1. 克隆仓库后运行`down.py`。
```bash
git clone https://github.com/XavierJiezou/python-dy-down.git
cd python-dy-down
python down.py
```
2. 输入[抖音](https://www.douyin.com/)短视频的分享链接, 例如: [https://v.douyin.com/dMTkJfu/](https://v.douyin.com/dMTkJfu/)。
```bash
请输入复制的抖音分享链接：https://v.douyin.com/dMTkJfu/
100%|█████████████| 6/6 [00:00<00:00, 1515.37KB/s]
```
3. [7002803323900415246.mp4](7002803323900415246.mp4)就是刚才那个测试链接下载的视频。
# 打包
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
注意：构建后的EXE文件放在`dist`文件夹中。
# 下载
> [dydown-1.0.0-win64.exe](https://github.com/XavierJiezou/python-dy-down/releases/download/1.0.0/dydown-1.0.0-win64.exe)
# 推荐
> [python-ks-down](https://github.com/XavierJiezou/python-ks-down): 一个下载快手无水印短视频的小程序。
