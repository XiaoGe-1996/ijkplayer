# ijkplayer

#### 项目简介
重新编译ijkplayer实现的可以播放rtsp视频流


#### 使用方式
- Gradle
```Java
   Step 1:

   allprojects {
       repositories {
           ...
           maven { url "https://jitpack.io" }
       }
    }


   Step 2:
   dependencies {
            # required, enough for most devices.
	        implementation 'com.github.XiaoGe-1996.ijkplayer:ijkplayer-java:v1.0.0'
	        implementation 'com.github.XiaoGe-1996.ijkplayer:ijkplayer-armv7a:v1.0.0'

	        # Other ABIs: optional
            implementation 'com.github.XiaoGe-1996.ijkplayer:ijkplayer-armv5:0.8.8'
            implementation 'com.github.XiaoGe-1996.ijkplayer:ijkplayer-arm64:0.8.8'
            implementation 'com.github.XiaoGe-1996.ijkplayer:ijkplayer-x86:0.8.8'
            implementation 'com.github.XiaoGe-1996.ijkplayer:ijkplayer-x86_64:0.8.8'

            # ExoPlayer as IMediaPlayer: optional, experimental
            implementation 'com.github.XiaoGe-1996.ijkplayer:ijkplayer-exo:0.8.8'


	}
```