　ipynbファイルをクリックするとJupyter notebook形式のファイルが表示されます。先頭にある「Open in Colab」ボタンを押すと、Google Colab上で実行できます。使用環境は、Google Colab が動作すれば、どんなものでも構いません。

# Edit_new_image.ipynb
　学習済みStyleGAN2モデルを使って、新規画像の画像編集がどの程度出来るのかを検証します。\
新規画像としては、あらかじめモデルを使って最も新規画像に近い画像を生成するベクトルデータ (18, 512) を求めて使用しています。詳細は、[cedro-blog](http://cedro3.com/ai/edit-new-image/)をご覧下さい。

# Find_your_favorite.ipynb
　学習済みStyleGAN2モデルの潜在空間にある画像の中から、好みの画像を探します。\
嫌いな画像のベクトルの平均はマイナス補正し、好みの画像のベクトルの平均はプラス補正することで、ベクトルを適切に補正します。\
また、画像ベクトルの一部をランダムに入れ替えることで、意外なバリエーションの中から、好みのものがないか探します。

# Sarch_for_Yui.ipynb
　学習済みStyleGAN2モデルの潜在空間の中に、新垣結衣そっくりの画像がないか探します。\
新垣結衣の画像を用意し、その画像に出来るだけ近い画像を生成するベクトルを探索します。
詳細は、[cedro-blog](http://cedro3.com/ai/search-for-yui/)をご覧下さい。

# generate_ayadao's_anime.ipynb
　通常、GANでアニメキャラを生成するというと顔のみです。しかし、これは、なんとアニメキャラの上半身を生成するGANです。詳細は、[cedro-blog](http://cedro3.com/ai/anime/)をご覧ください。
