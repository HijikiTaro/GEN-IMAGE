# GANでいろいろ画像を生成してみる
DCGANを使用して自分が生成してみたい画像を生成してみる。

# TODO
D LossとG Lossを取得する

# Setup
## 実行環境
### 環境名
Google Colaboratory
### 設定
ランタイム：python3 GPU  
  
# Usage
## 実装概要  
1. 生成したい画像を収集(Google image downloador etc)
1. 収集した画像をリサイズ(128×128)
1. githubからcloneしたコードを実行(rarなどのdataset解凍は今回は不要)

## model構造
### Generator model
![Generator](https://github.com/HijikiTaro/GAN-IMAGE/blob/master/image/Gen.png "Generator")

### Discriminator model
![Discriminator](https://github.com/HijikiTaro/GAN-IMAGE/blob/master/image/Dis.png "Discriminator")

## 実装手順
https://github.com/HijikiTaro/GAN-IMAGE/blob/master/gen_image.ipynb


## Result


# References
https://github.com/taku-buntu/Keras-DCGAN-killmebaby  
