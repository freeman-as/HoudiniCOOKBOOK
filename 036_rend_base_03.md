## 036_rend_base_03
第36回：レンダリング基礎編（3）
～カメラとライトの仕組みを学ぼう～

---
### メモ

- Cameraの設定
  Render
  カメラのwireframeの色や表示のON/OFF
  View
  Houdiniでは1ユニットは1メートル
  **`Resolution:`**Houdiniではレンダラーではなくカメラが解像度を決める
  **`Projection:`**Polar(球状に展開), Lens Shader(独自シェーダーで360度展開)
  **`Focal Length:`**焦点距離。単位はミリメートル。長いほど望遠で、短いと広角
  **`Aperture(レンズの口径):`**Houdini的にはフィルムサイズの横幅（Horizontal）
  → 変更すると画角が変わる。35mmだとフルサイズ
  **`Background:`**カメラに背景を設定
  **`Screen Window:`**2D的にフィルムサイズでのオフセット
  **`crop`**
  Sampling
  **`ShutterTime:`**
  **`FocusDistance:`**フォーカスがあたるところの距離。単位はユニット
  **`F-Stop:`**大きければ大きいほどピントが合う範囲が広い（カメラでいうF値）
  **`Bokeh:`**ボケさせる時の絞りの形（radial(丸)が基本）
- Lightについて
- **`Environment Light(全天球)`**
  Light
  **`LightColor`**
  **`LightExposure:`**露出。1にすれば、intensityが2乗
  **`EnviromentMap:`**32bit floatのHDRI画像ならOK
  **`LightEnabled:`**完全にレンダリングオフ
  **`EnableLightViewport:`**レンダリングのみに適用
  **`SkyLightEnviroment:`**組み込みのスカイライトが適用できる
  **`LightType:`**
  AttenuationOption：自分でコントロールしたいとき
  Attenuation: ライトの減衰
  Shadow: シャドウのコントロール

- 
