# TS-OneKeyProcess
简化对TS片源的人工处理操作，实现无人值守一键完成对批量TS片源的初步处理。
主要供有一定经验的字幕组片源、压制人员使用。
本工具主要自动执行以下工作：

1. 调用eac3to分析轨道信息

2. 调用eac3to提取音频轨道、图形字幕

3. 调用dgindexnv索引视频轨道

4. 按需读取avs模板生成avs文件

5. 调用caption2ass_pcr抽取ass字幕

6. 按需压制小档


--- 声明 ---

○ 本工具仅供技术交流研究之用，免费使用，不得用于任何买卖或营利。

○ 请勿非法滥用本工具去侵犯他人的合法权益。

○ 本工具由非专业人士业余制作，若发现bug欢迎反馈，感谢支持。

工具下载：https://github.com/qiangbro/TS-OneKeyProcess/releases

问题反馈：https://github.com/qiangbro/TS-OneKeyProcess/issues

author：mikey

所在团队：有村花纯字幕组
