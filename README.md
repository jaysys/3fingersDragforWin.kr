[![Release](https://img.shields.io/github/v/release/clementgre/ThreeFingersDragOnWindows?label=Download%20version)](https://github.com/clementgre/ThreeFingersDragOnWindows/releases/latest)
[![TotalDownloads](https://img.shields.io/github/downloads/clementgre/ThreeFingersDragOnWindows/total)](https://github.com/clementgre/ThreeFingersDragOnWindows/releases/latest)
[![LatestDownloads](https://img.shields.io/github/downloads/clementgre/ThreeFingersDragOnWindows/latest/total)](https://github.com/clementgre/ThreeFingersDragOnWindows/releases/latest)

# 사용전 설정사항
- 설정 >> 장치 >> 터치패드 >> "세손가락 제스처"에서 "없음"으로 셋팅해놓으세요. 
- 그렇게 해놓으면 해당 세 손가락 제스처 기능은 본 설치프로그램 설치후에 셋팅되는  "세 손가락 드래그 기능"으로 대체됩니다.  
- Mac맥에서 자주 사용하는 세 손가락 윈도우 창 드래그 기능사용을 윈도우에서 사용가능하도록 구현한 앱입니다.

# ThreeFingersDragOnWindows

A windows app that allows the macos three fingers drag, using the Raw Inputs of precision touchpad.

- [kamektx/TouchpadGestures_Advanced][1]
- [mfakane/rawinput-sharp][2]
- [emoacht/RawInput.Touchpad][3]

## Preview
![screenshot](https://raw.githubusercontent.com/ClementGre/ThreeFingersDragOnWindows/main/Resources/preview.png)


## 빌드 및 실행
- Visual Studio Code설치, .Net 6.0설치하고
```
https://code.visualstudio.com/download
https://dotnet.microsoft.com/en-us/download/visual-studio-sdks
```
- 본 소스를 다운 받아 아래와 같이 빌드하면 됩니다.


## Requirements
- .NET 6.0

## Build and Execute
```
cd /path/to/ThreeFingersDragOnWindows/directory/
dotnet build ./ThreeFingersDragOnWindows.csproj
dotnet exec ./bin/Debug/net6.0-windows/ThreeFingersDragOnWindows.dll
```

## How to open configuration pane
Click the ThreeFingersDragOnWindows icon on the Windows task bar.

## License

- MIT License

[1]: https://github.com/kamektx/TouchpadGestures_Advanced

[2]: https://github.com/mfakane/rawinput-sharp

[3]: https://github.com/emoacht/RawInput.Touchpad
