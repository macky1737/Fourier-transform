# フーリエ変換  
今回作ったコードは、画像をOpenCVで取得し、それをマウスで指定した場所をフーリエ変換を行う。さらにそれを逆フーリエ変換し元画像に戻すという内容。

# 実行結果
![bandicam 2019-07-28 16-05-45-871](https://user-images.githubusercontent.com/53041908/62003855-4e469e00-b158-11e9-8c12-aad06cca82f6.jpg)
動画がでかいためURLを張り付けておく  
https://raw.github.com/wiki/macky1737/github/images/FFT.mp4
# 使い方  
使い方は、実行すると表示される5つのウィンドウのうち、clickにマウスを持っていく。clickに押された場所をフーリエ変換し、Fourier_transformに表示。
また逆フーリエ変換をInverse Fourier transformで行う。もう二つの画像は、一つは変換を行う元画像とフーリエ変換を行った画像である。使ったのはopencv 4.1.0.,matplolib 3.0.3,np 1.16.2

# 参考資料  
参考にしたサイトは
http://lang.sist.chukyo-u.ac.jp/classes/OpenCV/py_tutorials/py_imgproc/py_transforms/py_fourier_transform/py_fourier_transform.html  
このサイトではフーリエ変換のコードを参考にさせてもらった  
http://rasp.hateblo.jp/entry/2016/01/24/204539  
マウスイベントの動きを参考にさせてもらった  
http://www.hello-python.com/2018/02/16/numpy%E3%81%A8opencv%E3%82%92%E4%BD%BF%E3%81%A3%E3%81%9F%E7%94%BB%E5%83%8F%E3%81%AE%E3%83%95%E3%83%BC%E3%83%AA%E3%82%A8%E5%A4%89%E6%8F%9B%E3%81%A8%E9%80%86%E5%A4%89%E6%8F%9B  
逆フーリエ変換について参考にさせてもらった
    
