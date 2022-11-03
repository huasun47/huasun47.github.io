# Shell 命令行动画制作

## By Nodejs

1. 视频转图片

   ```bash
    # 安装 ffmpeg （）
    brew install ffmpeg

    ## 检测是否安装 ffmpeg
    ffmpeg -h

    # ffmpeg -i 视频路径 -r 帧数 输出图片路径
    ffmpeg -i 绝对路径 -r 15 输出文件夹/%d.png

   ```

2. 转化步骤
   [代码](https://github.com/huasun47/nodejs-shell-video)里已经标注步骤

3. [素材链接](https://dweb.link/ipfs/bafybeifeip2gpo7x5ycr2bftwnpvjwxynzeiuju47oxlr7ytwyjtivytte?filename=cool-moto.mp4)

4. 感谢 [大佬](https://www.bilibili.com/video/BV1mW4y1a7Jn/?p=1) 提供 go 版本的教程
