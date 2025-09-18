# BGA：从节拍转换到帧

## 本教程所用到的软件

- Microsoft Excel（网页版）

## 先决条件

- 你已经确定了曲目偏移和BPM。
- 谱面已经采过音（可选）。

> [!WARNING] 本教程不需要用到冰与火之舞，如果你的谱面存在偏移且误差≤±5ms，请直接使用这个偏移值。

## 步骤与流程

1. 确定节拍数。
2. 使用以下公式： $c=[(60/a)*1000]/(1000/b)$

其中，$c$和$b$为帧数，前者为结果，后者为设定fps（$b$值默认为60）。

3. 将结果值输入到素材时间长度当中。（具体如何操作请参照各自剪辑软件）

## 附件

相关Excel实现：

[OneDrive for Business - BPM到帧](https://castorice-my.sharepoint.com/:x:/g/personal/admin_ys844522051_onmicrosoft_com/EUqTy24FEHREgwIR79X-79YB_VUAk4SWPYT9tkDQ8KYU_w?e=TyjMS4)

（这会打开Office 365客户端）