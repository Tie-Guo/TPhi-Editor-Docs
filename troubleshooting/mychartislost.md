# 我的谱面不见了

## 如果你用的事0.9 - 0.9.7（不包括0.9.7.1）版本的TPhiEditor

前往`/storage/emulated/0/.TGPhiEdit/charts/<你的谱面ID/名称>`，然后检查以下内容是否存在（0.9.x版本）：
```
chart.json
chart.mp3
chart.png
data.json
.editor
```
之后回到编辑器主页点击扳手转换一下。

## 我用的是0.8.4.2版本的TPhieditor

~~如果你是从0.9 - 0.9.7版本降级到0.8.4.2版本的，那很不幸了。（0.9 - 0.9.5和0.8.4.2版本文件结构不相同。~~

> [!ATTENTION] 如果你是在0.9 - 0.9.7版本创建的谱面导出后发现json结构不全的情况，不要去找cmdysj，铁锅或者去Phira的Github开issue（这个时候找它们反而会导致你被骂或者引起不可预料的争议，参考[这个动态](https://www.bilibili.com/opus/1101603981287751680)）。

该问题已在0.9.7.1版本修复，为了方便起见，确保提交问题之前TPhi Editor更新到最新版本。

## 我暴力修改了json文件内容

只能算你是个人才。

## “offset”，“eventLayers”，“LineLists”等相关报错

如果你用的是0.9.0 - 0.9.7的TPhi Editor，**请更新到TPhi Editor 0.9.7.1**，并重新导出为pez格式。

> [!WARNING] Phira不支持`*.tpe`格式的文件，请勿向Phira的Github提交相关Issues（后续会跟进）。