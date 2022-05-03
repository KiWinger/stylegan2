# 介绍
http://cedro3.com/ai/anime/

ipynbファイルをクリックするとJupyter notebook形式のファイルが表示されます。先頭にある「Open in Colab」ボタンを押すと、Google Colab上で実行できます。使用環境は、Google 

Colab が動作すれば、どんなものでも構いません。
单击 ipynb 文件以显示 Jupyter 笔记本格式文件。您可以通过按顶部的“在 Colab 中打开”按钮在 Google Colab 上运行它。只要 Google Colab 可以工作，您就可以在任何环境中使用它。


# 主要使用方法
点击文件中的“generate_ayadao's_anime.ipynb”链接到谷歌云计算，
修改参数以生成。


# Edit_new_image.ipynb
　学習済みStyleGAN2モデルを使って、新規画像の画像編集がどの程度出来るのかを検証します。\
新規画像としては、あらかじめモデルを使って最も新規画像に近い画像を生成するベクトルデータ (18, 512) を求めて使用しています。詳細は、[cedro-blog](http://cedro3.com/ai/edit-new-image/)をご覧下さい。

使用经过训练的 StyleGAN2 模型来验证您可以编辑多少新图像。 \ 
对于新图像，预先使用模型获取并使用生成最接近新图像的图像的矢量数据(18, 512)。详情请参阅 [cedro-blog](http://cedro3.com/ai/edit-new-image/)。


# Find_your_favorite.ipynb
　学習済みStyleGAN2モデルの潜在空間にある画像の中から、好みの画像を探します。\
嫌いな画像のベクトルの平均はマイナス補正し、好みの画像のベクトルの平均はプラス補正することで、ベクトルを適切に補正します。\
また、画像ベクトルの一部をランダムに入れ替えることで、意外なバリエーションの中から、好みのものがないか探します。

  从经过训练的 StyleGAN2 模型的潜在空间中的图像中找到您喜欢的图像。 \ 
通过负向校正不喜欢图像的向量的平均值和正向校正最喜欢的图像的向量的平均值来适当地校正向量。 \ 
此外，通过随机替换图像矢量的一部分，您可以从意想不到的变化中搜索您喜欢的那个。


# Sarch_for_Yui.ipynb
　学習済みStyleGAN2モデルの潜在空間の中に、新垣結衣そっくりの画像がないか探します。\
新垣結衣の画像を用意し、その画像に出来るだけ近い画像を生成するベクトルを探索します。
詳細は、[cedro-blog](http://cedro3.com/ai/search-for-yui/)をご覧下さい。

  在训练有素的 StyleGAN2 模型的潜在空间中寻找与新垣结衣一模一样的图像。 \ 
准备一张新垣结衣的图像，然后搜索一个矢量，该矢量将生成尽可能接近该图像的图像。
详情请参阅 [cedro-blog](http://cedro3.com/ai/search-for-yui/)。


# generate_ayadao's_anime.ipynb
　通常、GANでアニメキャラを生成するというと顔のみです。しかし、これは、なんとアニメキャラの上半身を生成するGANです。詳細は、[cedro-blog](http://cedro3.com/ai/anime/)をご覧ください。

  通常，GAN 只在脸上产生动漫人物。然而，这是一个生成动漫人物上半身的 GAN。详情请参阅[cedro-blog](http://cedro3.com/ai/anime/)。
