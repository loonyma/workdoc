# ip camera使用
海康威视的摄像头，windows通过网页预览正常，在centos下网页访问有问题改用vlc。vlc使用配置如下：

```
主码流
rtsp://admin:12345@192.0.0.64:81/h264/ch1/main/av_stream
rtsp://admin:12345@192.0.0.64:81/MPEG-4/ch1/main/av_stream

子码流：
rtsp://admin:12345@192.0.0.64/mpeg4/ch1/sub/av_stream
rtsp://admin:12345@192.0.0.64/h264/ch1/sub/av_stream
```
