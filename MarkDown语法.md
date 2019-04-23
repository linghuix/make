
[加载数据](#35数据加载实用程序-P602)

    code
    code
    code
    code

***

# This is an h1 tag
## This is an h2 tag
###### This is an h6 tag
***

* Item 1
* Item 2
  * Item 2a
  * Item 2b

***

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
   
***

<table>
  <thead>
    <tr>
      <th>First Header</th>
      <th>Second Header</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Content Cell</td>
      <td>Content Cell</td>
    </tr>
    <tr>
      <td>Content Cell</td>
      <td>Content Cell</td>
    </tr>
  </tbody>
</table>

***

> 区块引用
>> 嵌套引用

***

*斜体*，_斜体_
**粗体**，__粗体__




### 3.5.数据加载实用程序 P602
scikit-learn 能够工作在任何以 numpy 数组或者scipy稀疏矩阵形式存储的数据集上。其他能够转换为数字数组的类型，比如 pandas 中的 DataFrame 也是可以的。

这里有一些推荐的加载普通格式，[CSV](https://baike.baidu.com/item/CSV/10739#4_2)，Excel，[JSON](https://baike.baidu.com/item/JSON/2462549)，SQL的数据方法。 DataFrames 也能够从元组或者字典中生成。panda 能够方便地处理不同类型的数据，并提供操作和转化为适合 scikit-learn 使用的数值数组的工具。

* [pandas.io](https://pandas.pydata.org/pandas-docs/stable/io.html)
* [scipy.io](https://docs.scipy.org/doc/scipy/reference/io.html)
* numpy/routines.io

对于其他混杂数据，比兔图片，视频，音频，你2可能需要采用：
* [skimage.io](https://scikit-image.org/docs/dev/api/skimage.io.html) 或者 [Imageio](https://imageio.readthedocs.io/en/latest/userapi.html)
* [scipy.io.wavﬁle.read](https://docs.scipy.org/doc/scipy-0.14.0/reference/generated/scipy.io.wavfile.read.html)

























