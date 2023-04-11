# lol-on-linux-2023
y run lol for 30 mins, and close the game but try, the game log show but keep running 
```
0350:fixme:heap:RtlSetHeapInformation HEAP_INFORMATION_CLASS 1 not implemented!
0350:fixme:ntdll:EtwEventSetInformation (deadbeef, 2, 27D50028, 16) stub
0bd4:err:seh:dispatch_exception unknown exception (code=c0000420) raised
```

wine version used:  https://github.com/polkaulfield/lol-for-linux-installer/releases/download/wine-lol-staging/wine-lol-staging-8.5-1.tar.xz

go to lutris and add this config: 

1)configuration> runner options> wine version wine-lol-stanging-8.5-1
2)configuration> runner options> enable dxvk/vkd3d : true
3) configuration> runner options> DXKV version : v1.7.1L
4) configuration> runner options> enable Esync
5) configuration> system options> enviroment variable: WINEDEGUB  trace+seh

screenshots on spanish

![image](https://user-images.githubusercontent.com/22879539/231023700-78efc24e-1887-4a1a-b028-5beeec8d173b.png)
![image](https://user-images.githubusercontent.com/22879539/231023736-b75471d6-f7d8-45a2-b388-696d1826b49e.png)
