# M3U8-Downloader
HLS Downloader，一个Electron App，可以下载、播放HLS视频流

# 获取视频流地址
在chrome浏览器打开视频网页，按下F12,页签点击到Network页面，在Filter框里输入"m3u8",然后按F5刷新页面，如果网页里的视频使用的是HLS源，就可以在这里捕获到视频流地址，然后选中右键 Copy -> Copy Link Address.
提供m3u8源地址，下载并无损转码Mp4文件

# Windows下载
目前仅编译了Windows Release. 下载地址：[Release](https://github.com/HeiSir2014/M3U8-Downloader/releases)
