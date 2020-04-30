# porn-detect




Python 黄色、色情图片识别

简单有效的识别色情图片。

基于文献：《基于肤色特征的色情图像识别算法》 





## 效果

![效果图](./process.jpg)

## Usage

run:

```shell

python3 porn_detect.py  test_sets/3.jpg

```

output:

```shell

皮肤占比: 0.029348927875243666
皮肤占人体矩形比: 0.15305323723455083
是否识别为黄图: False

```

将变量`save_image`设置为 `True` 后，可以保存关键路径的图片。方便调试。

## License

MIT
