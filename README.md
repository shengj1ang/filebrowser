Fork info:
支持生成视频缩略图的file browser.
This fork implements generating video thumbnails.

Fork from: 
https://github.com/cody82/filebrowser/tree/videopreview
他已经做的足够好了，只是没有同步到最新版本，使用GitHub Action直接在线编译是很方便的。
[直接下载编译好的文件](https://github.com/shengj1ang/filebrowser/releases/tag/202502240240)，windows解压后需要加上.exe的后缀

customaizations include:
* Widely supports all operating systems, only requires the presence of ffmpeg, has been tested on macOS and Windows
* Video thumbnails do not use cache to prevent excessive junk files, modern device performance is sufficient to support real-time thumbnail generation.
* Use GitHub Action to generate releases
* 广泛的支持所有操作系统，只需要ffmpeg的存在，已在macOS和windows下测试过
* 视频缩略图不使用cache，防止垃圾文件过多，现代的设备性能足以支持实时生成缩略图。
* 使用GitHub Action生成release

Modified files are:

/http/preview.go

/frontend/src/components/files/ListingItem.vue

废话删了

More Infomation: [https://github.com/filebrowser/filebrowser](https://github.com/filebrowser/filebrowser)
