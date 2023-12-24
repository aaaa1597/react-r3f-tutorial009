# react-r3f-tutorial009
React +TypescriptのWebアプリで、React Three Fiberのtutorialその9。(OrbitControls カメラ座標制御)

![](https://storage.googleapis.com/zenn-user-upload/cb4914f52301-20231224.png)

# まとめ
## 1.dreiのインストール
OrbitControlsは、dreiのライブラリなので、インストールしと
```shell
$ npm install --save @react-three/drei
```
## 2.OrbitControlsのimport
OrbitControlsをimport。
```ts
import { OrbitControls } from "@react-three/drei";
```
## 3.OrbitControlsを使う
<Canvas></Canvas>の範囲内で、使う。
```ts
    <OrbitControls />
```

簡単～。
