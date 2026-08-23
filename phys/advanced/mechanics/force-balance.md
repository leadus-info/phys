---
title: 力のつり合い
description: "平面内で働く複数の力がつり合う条件を、力の成分への分解と合成を使って扱う"
goal: "力を成分に分解し合成する方法と、平面内で働く力のつり合いの条件を、実験結果から見いだして説明できるようになる"
tags: [phys, mechanics, force]
stage: advanced
subject: 力学
hierarchy:
  - title: 物理
    path: ../../index.md
  - title: 応用編
    path: ../index.md
  - title: 力のつり合い
    path: force-balance.md
requires:
  - title: 様々な力
    path: various-forces.md
  - title: 力の合成・分解
    path: ../../intermediate/mechanics/force-composition.md
---

## 力の成分

平面内ではたらく力$\boldsymbol{F}$は、互いに垂直な$x$軸・$y$軸方向の成分に分解できます。力の大きさを$F$、$x$軸となす角を$\theta$とすると、

$$F_x = F\cos\theta, \qquad F_y = F\sin\theta$$

と表せます。複数の力を扱うときは、それぞれの力を成分に分解してから、成分ごとに足し合わせると計算しやすくなります。

## 力の合成（成分による方法）

2つの力$\boldsymbol{F_1} = (F_{1x}, F_{1y})$、$\boldsymbol{F_2} = (F_{2x}, F_{2y})$の合力$\boldsymbol{F}$は、成分ごとの和として求められます。

$$\boldsymbol{F} = \boldsymbol{F_1} + \boldsymbol{F_2} = (F_{1x}+F_{2x},\ F_{1y}+F_{2y})$$

これは、中級編で学んだ平行四辺形の法則による作図と同じ結果を、数値計算で求める方法です。**例**：中級編で扱った、大きさ$3\ \mathrm{N}$と$4\ \mathrm{N}$の2力が直角に交わっている場合を成分で表すと、$\boldsymbol{F_1}=(3,0)$、$\boldsymbol{F_2}=(0,4)$となり、その和は$\boldsymbol{F}=(3+0,\ 0+4)=(3,4)$。この合力の大きさは$\sqrt{3^2+4^2}=5\ \mathrm{N}$となり、中級編で作図によって求めた結果（$5\ \mathrm{N}$）と一致します。

## 力のつり合いの条件

平面内で物体に複数の力がはたらいていて、物体が静止し続けているとき、これらの力は**つり合っている**といいます。力がつり合っているとき、すべての力を合成した合力は$\boldsymbol{0}$になります。成分で表すと、次の2つの式が同時に成り立ちます。

$$\sum F_x = 0, \qquad \sum F_y = 0$$

**例題**：質量$m$の物体が、水平から角度$\theta$の斜面上で静止している。斜面が滑らかで摩擦がない場合、斜面に垂直な方向の力のつり合いから垂直抗力$N = mg\cos\theta$が、斜面に平行な方向の力のつり合いから、物体を支える力（張力など）の大きさは$mg\sin\theta$になることが求められる。

重力$mg$を「斜面に垂直な成分」と「斜面に沿う成分」に分解するとき、斜面の傾き角$\theta$と、鉛直方向（重力の向き）と斜面の垂線とのなす角が等しくなることから、斜面に垂直な成分は$mg\cos\theta$、斜面に沿う成分は$mg\sin\theta$になります。$\theta=30°$、$m=2\ \mathrm{kg}$、$g=9.8\ \mathrm{m/s^2}$のとき、$N=2\times9.8\times\cos30°\approx17\ \mathrm{N}$、斜面に沿う成分は$2\times9.8\times\sin30°=9.8\ \mathrm{N}$。

## まとめ

平面内の力は、互いに垂直な2方向の成分に分解して扱うと、合成や計算が見通しよく行えます。物体にはたらく力がつり合っているとき、任意の2方向について力の成分の和がそれぞれ0になります。この考え方は、斜面上の物体や複数の糸で吊るされた物体など、平面内の様々なつり合いの問題に応用できます。

## 関連ページ

- [様々な力](various-forces.md)
- [運動の法則](laws-of-motion.md)
