在arcgis python 2.7环境下安装 rasterio   gdal

1、判断自己 python 版本，以2.7为例
2、在 http://www.lfd.uci.edu/~gohlke/pythonlibs/#rasterio   中找到 gdal  rasterio，选择版本！！
	安装的不是对应python版本的库，下载的库名中cp27代表python2.7,其它同理。
	
3、	pip install -U pip

4、 cd 到 whl 下载的目录，并安装 
	pip install GDAL-2.2.2-cp27-cp27m-win32.whl
	pip install rasterio-1.0a10-cp27-cp27m-win32.whl
