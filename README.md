This is the binary package of box86 and box64 open source code and the DEB package of wine, which is used to run x86 and x64exe on arm647ubuntu??box86 worked with box64 and no need armhf chroot/proot on arm64 ubuntu/debian.Your Ubuntu and Debian must support multiple architectures. It is recommended to use arm64 Ubuntu 21 10 or debian 11.Please use the published DEB instead of the old DEB under code. There is no need to set the environment variable manually. The execution of X86 and x64exe is no longer separated. Non snapdragon 845 processors can also run the DEB. In arm64debian / Ubuntu, the FPS of Ubuntu is about 10fps higher than that of Debian.
sudo dpkg --add-architecture armhf
sudo apt update
sudo apt install zenity:armhf libasound*:armhf libstdc++6:armhf mesa*:armhf
sudo apt install vulkan* -mesa- mesa*
sudo dpkg -i ./*.deb
New test video
【【box86 and box64 wine】安卓手机同时执行windows 64位和32位exe-哔哩哔哩】 https://b23.tv/NaO37Vy


old test video
# box86-and-box64-for-arm64
在arm64上运行box86和box64，box86不需要armhf chroot，box86和box64共同工作。
How to run box86 and box64 on arm64 Linux without 32-bit chroot? Please read how to set the environment and using Win32 and wine64. I also provide box86 and box64 DEB for arm64 Debian. Box86 is cross compiled. How to compile and refer to the official instructions of box86. I mainly provide a convenient environment setting. Reference: how to set the environment.
Demo video: blibli cinnamon 2018
[1]https://m.bilibili.com/video/BV1tL4y147GS?share_medium=android&share_plat=android&share_session_id=3c79a0fb-447f-4a9f-9ea0-f78ec78e7509&share_source=COPY&share_tag=s_i&timestamp=1642690621&unique_k=KcI9dmy&share_times=1
[2]CPU load demonstration
https://m.bilibili.com/video/BV1Lb4y1J7dU?share_medium=android&share_plat=android&share_session_id=1482d58d-48ce-42d7-88ad-aa07745de871&share_source=COPY&share_tag=s_i&timestamp=1642690732&unique_k=RlWvEEM&share_times=1
[3]Box86 wine white album:https://m.bilibili.com/video/BV1wT4y127B9?share_medium=android&share_plat=android&share_session_id=55c096cf-56bf-45dd-84aa-46ad8560350c&share_source=COPY&share_tag=s_i&timestamp=1642690777&unique_k=2q5f59h&share_times=1

now box86 and box64 wine can run x86 and x64 exe on arm64 ubuntu/debian，worked like windows。The new test vedio is
【【box86 and box64 wine】安卓手机同时执行windows 64位和32位exe-哔哩哔哩】 https://b23.tv/kB8RnFt
