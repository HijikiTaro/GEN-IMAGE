# GANでいろいろ画像を生成してみる
DCGANを使用して自分が生成してみたい画像を生成してみる。

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
1. githubからcloneしたコードを実行(clone対象References参照。rarなどのdataset解凍は今回は不要。)

## model
### Generator model
![Generator](https://github.com/HijikiTaro/GEN-IMAGE/blob/master/image/Gen.png "Generator")

### Discriminator model
![Discriminator](https://github.com/HijikiTaro/GEN-IMAGE/blob/master/image/Dis.png "Discriminator")

## Code
https://github.com/HijikiTaro/GEN-IMAGE/blob/master/gen_image.ipynb


## Result
![iteration_0](https://github.com/HijikiTaro/GEN-IMAGE/blob/master/image/iteration_0.png "iteration_0")
  
![iteration_71000](https://github.com/HijikiTaro/GEN-IMAGE/blob/master/image/iteration_71000.png "iteration_71000")
  
今回のテーマとして、ドラクエのスライムを生成してみた。  
が、画像数不足と学習不足でかなりおそろしいスライムたちが生成された。

# References
https://github.com/taku-buntu/Keras-DCGAN-killmebaby  
