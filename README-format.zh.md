[En](https://github.com/P-KB-O/good-first-repo/blob/main/README-format.md) | Zh

## stand-off format

所有标注IDs包含一个表示标注类型的大写字母以及一个数字，标志类型如下所示：

T: text-bound annotation(实体/事件trigger)

E: event

M: event modification

R: relation

N: normalization(external reference)(添加于`BioNLP-ST 2013`任务)

此外还有星号\*用来标记特殊的例子

### Entity annotation files(.a1)

`\.a1` 文件存储文本的实体标注，所有实体标注都有其类型以及一个唯一ID（例如：Protein或者Chemical）, 并且包含entity mention的字符范围（以“start end”对进行表示）

### Target annotation files (.a2)

`\.a2`文件包含事件、关系和其他相关信息的注释，这些信息是每个任务中需要提取的目标。

包含
1. Event annotations
2. Relation annotations
3. Additional entity annotations
4. Entity equivalence annotations
