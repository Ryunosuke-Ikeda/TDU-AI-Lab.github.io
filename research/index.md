{% include header.md %} <!-- _includes内のheader.mdをインクルード -->


[surgery]: /research/surgery/
[detection]: /research/detection/
[denoising]: /research/denoising/


# 東京電機大学 理工学部 人工知能研究室

<meta name="description" content="東京電機大学 理工学部 人工知能研究室のホームページです．深層学習（Deep Learning）による画像認識・画像生成をはじめとするAI技術の研究を行っています．音声認識・音声生成・自然言語処理などにも手を伸ばしています．">

主な研究テーマや関心のある研究キーワードを紹介します．

## 研究紹介
  + 手術状況・手術行為の自動認識（準備中）

  + [高難度物体検出][detection]

  + 電子顕微鏡画像のノイズ除去・鮮明化（準備中）

<!--
  + [手術状況・手術行為の自動認識][surgery]

  + [電子顕微鏡画像のノイズ除去・鮮明化][denoising]
-->

## 関係・関心がある研究キーワード

以下のような手法を勉強／使用／改良するような研究室です．

+ 画像認識系
  + CNNモデル全般
    + Alexnet
    + VGG
    + Residual network
  + 非CNN系モデル
    + Capsule Network
    + Vision Transformer
+ 物体検出系
  + R-CNN系
    + Faster R-CNN
    + Mask R-CNN
  + Attention系
    + DETR
  + アプリケーション
    + Openpose
    + OpenFace
+ 敵対的生成
  + GAN
  + Conditional GAN
+ 画像生成系
  + Encoder-Decoder系
    + U-net
    + VAE
    + Disentanglement
  + GAN系
    + Pix2Pix
    + Cycle GAN
+ 言語処理系
  + Transformer
  + BERT
+ 言語⇒音声
  + EATS
  + Hifi-GAN
  + Glow-TTS
+ 言語⇒画像
  + DALL-E
  + GPT-3
+ Attention機構
  + 特徴ベクトル系
    + Self attention
    + Source-target attention
  + 特徴マップ系
    + Squeeze-and-Excitation
+ Selective attention (cognitive science)
  + Saliency map
    + Pan's model
+ データ拡張
  + Mixup
  + Cutout
  + CutMix
+ 損失関数全般
  + GAN関係
    + Adversarial loss
    + Cycle consistency loss
  + Metric関係
    + Contrastive loss (Siamese network)
    + Triplet loss
  + 物体検出系
    + Hungarian Loss (DETR)
+ 構造最適化 (Network Architecture Search: NAS)
+ 敵対的サンプル生成／敵対的攻撃
+ テクスチャバイアス


{% include footer.md %} <!-- _includes内のfooter.mdをインクルード -->
