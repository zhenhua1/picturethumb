# picturethumb
图片压缩不失真

## 使用示例

```
use zzhPictureThumb\DataProvider;
use zzhPictureThumb\PictureService;

var_dump(DataProvider::client(PictureService::class)->pictureThumb('./pic/1.jpg',500,500));
//如果想在浏览器上看一下压缩后的图片如下
var_dump(DataProvider::client(PictureService::class)->setBrowserPrint()->pictureThumb('./pic/1.jpg',500,500));

```
