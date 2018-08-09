# Barcode_decode-decodability 条码译码及可译码度计算</br>
对图像中的EAN-13商品条码进行译码，检验可译码度。
### 1.通过PIL库将视觉信息转化为数据
模式“1”
### 2.获取色块宽度（单位：像素）
将区域内颜色相同的相连区域设定为同一组，按照从左到右的顺序输出每组所包含的像素数量。
### 3.识别出条码位置
起始符、间隔符、终止符识别
### 4.计算条码宽度参数
条码字符宽度（p）</br>
相似边缘之间的距离（ei）</br>
参考阈值（RT)</br>
条码字符的相似边缘尺寸所包含的模块宽度数（Ei）</br>
前置码</br>
字符相似边缘尺寸所包含的模块宽度字典--->数字字符+ABC子集
### 5.条码译码
![译码过程](https://github.com/Amexpo/Barcode_decode-decodability/条码译码过程.png)
### 6.计算可译码度
可译码度Vc
### 7.参考标准：
GB 12904</br>
GB/T 18348</br>

