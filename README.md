# AdvAPP
目前已集成的广告SDK有：
* 1.穿山甲SDK
* 2.广点通SDK
* 3.链咖视频SDK
* 4.精众视频SDK
* 发布到jitpack容易产生依赖冲突，所以只能下载library,以module方式导入

7月18日更新：
* 修改广告加载机制：
    > 修改之前加载模式：先加载配置着有比率的广告，如果配置有比率的广告加载失败,那么会按照配置文件排列广告的顺序去加载没用配置比率的广告。  
    > 修改之后加载模式：先加载配置着有比率的广告，如果配置有比率的广告加载失败,那么不会去加载其他配置为0比率的广告。
