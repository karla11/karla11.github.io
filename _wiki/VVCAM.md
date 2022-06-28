---
layout  : wiki
title   : VVCAM is...
summary : 
date    : 2022-06-27 06:03:55 +0900
updated : 2022-06-27 06:48:44 +0900
tags    : 
toc     : true
public  : true
parent  : 
latex   : false
---
* TOC
{:toc}

# isp-imx-4.2.2.6.0
imx8mp solidrun 배포 yocto 빌드 시스템에 있다. github에서 별도로 다운받을 수
있으며 basler 사의 카메라 모듈이 nxp사의 imx8mp soc 베이스 isp 서브 시스템에서
동작할 수 있도록 서브시스템 제어 프레임워크를 직접 개발하여 배포한 것 같다.
분석하며 더 알아보도록 하겠다.


## file structure
```bash
$ tree -L1
isp-imx-4.2.2.6.0 tree -L 1
.
├── appshell
├── build-all-isp-mkpartial.sh
├── build-all-isp.sh
├── COPYING
├── dewarp
├── imx
├── mediacontrol
├── SCR.txt
├── units
├── utils3rd
└── vvcam
```

### appshell
native linux 용 Qt 어플리케이션 및 안드로이드 앱이다. GUI앱이므로 생략한다.  

### dewarp
### imx
### mediacontrol
```bash
isp-imx-4.2.2.6.0/mediacontrol$ tree -L 1
.
├── buffer
├── case
├── CMakeLists.txt
├── daemon
├── fpga
├── include
├── include_api
├── readme
└── server

```

### units
### utils3rd
### vvcam
 
