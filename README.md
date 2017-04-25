# UnityRTC
基于webrtc的unity多人游戏实时语音(A Unity Demo for Impl Real-time Game Voice Among Mutiplayers Based On WEBRTC)
## 简介
### MutiRTC_Unity
  unity工程，基于版本5.3.3f1.包含一个简单的多人实时语音聊天室场景。语音模块以平台sdk形式集成进unity，包括安卓和ios的语音sdk，详见plugins目录。<br>
#### 支持功能：
* 多人同时在线聊天：由于基于webrtc的p2p连接，每两个人之间都有一个peerconnection，只能少数几人互通，否则性能会有问题<br>
* 支持android和ios<br> 
* 语音扬声器模式与游戏背景音共存<br>
* 网络断线重连
### SignalServer
  信令服务器，即房间服务器负责端对端信令的传输
### ICE Server
  
## 使用

