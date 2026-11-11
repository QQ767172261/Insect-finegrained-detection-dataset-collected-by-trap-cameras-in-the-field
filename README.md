陷阱相机昆虫数据 722类52948标注 细粒度识别![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/5b8227a69aa44896b6c18e8fb616ab5f.png)


【数据集名称】陷阱相机昆虫细粒度识别数据集（YOLO格式）
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/e1639fbe056f481a987cf4376ddaf883.png)

数据规模
总图像 2,893 张 | 有效类别 722 类 | 标注目标 52,948 个
标注格式：YOLO（txt标注文件）
数据来源：陷阱相机（trap camera）实地拍摄
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/8cc5c51a7b0f41b983a9c87c0d40dd5d.png)

数据说明
· 数据集呈长尾分布（long-tail），部分稀有类别仅有个位数标注，训练时建议做重采样或Focal Loss
· 陷阱相机拍摄角度多样，天然包含复杂背景和遮挡场景，泛化性优于实验室拍摄数据![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/662e6277eb804bebbfb25bc49fdcc45e.png)


适用场景
· 细粒度图像识别（Fine-grained Visual Classification）论文实验
· 生态监测 / 生物多样性 AI 识别系统
· 农业虫害自动监测与预警
· 长尾分布学习（Long-tail Learning）算法研究
· 计算机视觉课程作业 / 竞赛备赛


# 陷阱相机昆虫细粒度识别数据集（YOLO格式）
| 项目 | 详情 |
| ---- | ---- |
| 数据集名称 | 陷阱相机昆虫细粒度识别数据集（YOLO格式） |
| 采集方式 | 陷阱相机实地拍摄 |
| 总图像数量 | 2893张 |
| 有效类别 | 722类（分类等级包含：界ORDER、科FAMILY、亚科SUBFAMILY、族TRIBE、属GENUS、种SPECIES） |
| 标注目标总数 | 52948个 |
| 标注格式 | YOLO txt标注 |
| 文件结构 | images（图像文件夹）、labels（标签文件夹）、classes.txt、notes.json、yolo_class_statistics.csv |
| 数据特点 | 典型长尾分布，包含蛾类、非蛾类、不可识别昆虫；标注层级丰富，覆盖物种、属、族、亚科、科、目；实拍场景，存在遮挡、复杂背景，部分稀有类别样本极少 |

## 数据集摘要
本数据集为陷阱相机野外采集的昆虫细粒度检测数据集，一共2893张图像，722个有效类别，标注目标52948个，YOLO标准txt格式。类别层级丰富，包含物种、属、族、亚科、科、目多个分类等级，包含Moth蛾类、Non-Moth非蛾类、Unidentifiable无法识别昆虫；数据呈明显长尾分布，野外实拍自带遮挡、复杂背景，适合细粒度识别、长尾学习、生态监测、农业虫害识别相关科研与模型训练。数据集配套完整统计csv、类别文件，开箱即可用于YOLO系列模型训练。

## 应用场景
- 昆虫细粒度目标检测、细粒度识别论文实验
- 野外生态监测、生物多样性统计系统
- 农田虫害自动识别、虫情预警
- 长尾分布算法、类别不平衡算法研究
- 计算机视觉竞赛、科研项目、课程实验

## 应用价值
1. 分类层级丰富：同时包含种、属、科、目多等级标签，支持多粒度识别任务；
2. 真实野外场景：陷阱相机自动采集，贴近野外生态监测真实部署环境，模型泛化能力更强；
3. 规模大、类别极多：722类昆虫，是高质量细粒度昆虫检测数据集；
4. 配套完善：自带类别清单、统计报表，YOLO格式，直接适配YOLOv5/v8/v11等主流框架；
5. 天然长尾样本：适合做长尾识别、重采样、损失函数（Focal Loss等）相关算法研究。

## 标签
`昆虫细粒度识别` `陷阱相机` `蛾类检测` `长尾数据集` `YOLO标注` `生物多样性监测` `农业虫害识别`

## 类别说明（）
|类别ID|类别名称|分类等级|
| ---- | ---- | ---- |
|0|Non-Moth|NA|
|1|Moth|ORDER|
|2|Unidentifiable|NA|
|3|Tortricidae|FAMILY|
|4|Lepidoptera|ORDER|
|5|Chrysoteuchia culmella|SPECIES|
|6|Crambidae|FAMILY|
|7|Choristoneura fumiferana|SPECIES|
|8|Geometridae|FAMILY|
|9|Hypoprepia fucosa|SPECIES|
|10|Macaria sp.|GENUS|
|11|Crambus sp.|GENUS|
|12|Cnephasia stephensiana|SPECIES|
|13|Crambini|TRIBE|
|14|Pandemis limitata|SPECIES|
|15|Yponomeuta sp.|GENUS|
|16|Campaea perlata|SPECIES|
|17|Scopariinae|SUBFAMILY|
|18|Noctuidae|FAMILY|
|19|Hyphantria cunea|SPECIES|
|20|Microcrambus elegans|SPECIES|
|21|Choristoneura sp.|GENUS|
|22|Palpita magniferalis|SPECIES|
|23|Choristoneura rosaceana|SPECIES|
|24|Hydrelia inornata|SPECIES|
|25|Archipini|TRIBE|
|26|Dryocampa rubicunda|SPECIES|
|27|Drepana arcuata|SPECIES|
|28|Spilosoma lubricipeda|SPECIES|
|29|Eupithecia sp.|GENUS|
|30|Notodontidae|FAMILY|
|31|Idaea aversata|SPECIES|
|32|Pandemis lamprosana|SPECIES|
|33|Eilema lurideola|SPECIES|
|34|Gelechiidae|FAMILY|
|35|Calliteara pudibunda|SPECIES|
|36|Pyralidae|FAMILY|
|37|Tortricinae|SUBFAMILY|
|38|Apotomis sp.|GENUS|
|39|Coleophoridae|FAMILY|
|40|Spilomelinae|SUBFAMILY|
|41|Erebidae|FAMILY|
|42|Eucosmini|TRIBE|
|43|Pandemis sp.|GENUS|
|44|Parapoynx stratiotata|SPECIES|
|45|Deltote pygarga|SPECIES|
|46|Blastobasidae|FAMILY|
|47|Argyrotaenia velutinana|SPECIES|
|48|Lophocampa caryae|SPECIES|
|49|Eilema complana|SPECIES|
|50|Argyrotaenia mariana|SPECIES|
|51|Olethreutini|TRIBE|
|52|Agriphila sp.|GENUS|
|53|Pelosia muscerda|SPECIES|
|54|Scoparia sp.|GENUS|
|55|Platynota sp.|GENUS|

> 注：完整722类在数据集内`classes.txt`与`yolo_class_statistics.csv`中存放。


