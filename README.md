# GANでいろいろ画像を生成してみる
DCGANを使用して自分が生成してみたい画像を生成してみる。

# TODO
D LossとG Lossを取得する

# Setup
## Ènvironment
### Ènvironment Name
Google Colaboratory
### Config
runtime：python3 GPU  
  
# Usage
## Overview
1. 生成したい画像を収集(Google image downloador etc)
1. 収集した画像をリサイズ(128×128)
1. githubからcloneしたコードを実行(rarなどのdataset解凍は今回は不要)

## model
### Generator model
![Generator](https://github.com/HijikiTaro/GAN-IMAGE/blob/master/image/Gen.png "Generator")

### Discriminator model
![Discriminator](https://github.com/HijikiTaro/GAN-IMAGE/blob/master/image/Dis.png "Discriminator")

## Code
https://github.com/HijikiTaro/GAN-IMAGE/gen_image.ipynb


## Result


# References
https://github.com/taku-buntu/Keras-DCGAN-killmebaby  
