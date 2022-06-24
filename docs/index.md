# ペンプロッター

## 概要

ペンプロッターを作成します。

### (WIP)

## パーツ

|        名前      |   個数     |     値段    |    リンク    |
|------------------------------|------------|------------|-------------|
|Quimat Nema 17 ステッピングモータ|   2   |     ¥1796       |[リンク](https://www.amazon.co.jp/Quimat-17%E3%82%B9%E3%83%86%E3%83%83%E3%83%94%E3%83%B3%E3%82%B0%E3%83%A2%E3%83%BC%E3%82%BF-3D%E3%83%97%E3%83%AA%E3%83%B3%E3%82%BF%E3%83%BC%E7%94%A8-36-8oz-3D%E3%83%97%E3%83%AA%E3%83%B3%E3%82%BF%E3%83%BC/dp/B06XRFGTR4/ref=asc_df_B06XRFGTR4/?tag=jpgo-22&linkCode=df0&hvadid=265845994451&hvpos=&hvnetw=g&hvrand=104924426555351107&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=1009052&hvtargid=pla-444781979692&th=1)|
|KKHMF 2個 V3 彫刻 シールド 3D プリンタ CNC 拡張ボード A4988 ドライバーボード|   2   |     ¥689      |[リンク](https://www.amazon.co.jp/gp/product/B088FLTQ2K/ref=as_li_tl?ie=UTF8&tag=101010fun-22&camp=247&creative=1211&linkCode=as2&creativeASIN=B088FLTQ2K)|
|デジタル・マイクロサーボ SG90|   1   |     ¥480      |[リンク](https://www.amazon.co.jp/TOWER-PRO-SG90D-%E3%83%87%E3%82%B8%E3%82%BF%E3%83%AB%E3%83%BB%E3%83%9E%E3%82%A4%E3%82%AF%E3%83%AD%E3%82%B5%E3%83%BC%E3%83%9C-SG90/dp/B016FKJJ8M/ref=sr_1_6?keywords=sg90%2Bservo&qid=1656045938&sr=8-6&th=1)|


## デザインファイル

## 理論

### ステッピングモーターの仕様
<br><br><br>
![](../img/stepper/stepper_1.jpg#center)

<br><br><br>

Step angle: 1.8°と記載されております。1.8°ステップ角度ということはステッピングモーターを一回転(360°)させるためには

```
360 / 1.8 = 200  
```

200ステップ必要ということになります。


## Inkscape

### 参考資料
- [CNC pen plotter, machine setup and Software video](https://www.youtube.com/watch?v=I4omT2L9aI8)
- [【XYペンプロッター制作】Inkscapeで画像をGコードに変換する](https://101010.fun/iot/arduino-cnc-image-to-gcode.html)


