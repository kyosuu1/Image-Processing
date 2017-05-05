# Image-Processing
ゴールデンウィークのお勉強レポジトリです。論文読んで何かやろうとしたら何もわからなくて、結局既存のソースコードをつなげて遊ぶことになりました…

## Prerequisites
すみません、ただのお遊びのくせに用意しなきゃいけないのがたくさんあります。
+ Ubuntu 16.04で動きます
+ Python 3.x
+ OpenCV 3.2
+ NumPy, SciPy, matplotlib

## 遊び方
`python opencv_mouse.py`
したら絵が立ち上がります。そこに長方形を描いてください。
そしてsキーを押すと、segmentationしてくれます。

## 参考文献
マジわかんなかったんですけど…
内部と外部の2乗誤差の和を少なくするんだな…という雰囲気しかわかんなかったんですけど、
一応論文リンクします。

[1] [T.Chan, L.Vese, Active Contours Without Edges, IEEE Trans. IMAGE PROCESSING, Vol. 10, No. 2, 2001.](http://www.math.ucla.edu/~lvese/PAPERS/IEEEIP2001.pdf)

[2] kevin-keraudrenさんのGitHub https://github.com/kevin-keraudren/chanvese
