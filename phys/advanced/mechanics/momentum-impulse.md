---
title: 運動量と力積
description: "運動量と力積の関係をベクトルで扱い、物体の衝突や分裂の実験を通じて運動量保存の法則を扱う"
goal: "運動量と力積の関係、運動量保存の法則を、実験結果から見いだして説明できるようになる"
tags: [phys, mechanics, momentum]
stage: advanced
subject: 力学
hierarchy:
  - title: 物理
    path: ../../index.md
  - title: 応用編
    path: ../index.md
  - title: 運動量と力積
    path: momentum-impulse.md
requires:
  - title: 運動の法則
    path: laws-of-motion.md
---

## 運動量と力積

質量$m$の物体が速度$\boldsymbol{v}$で運動しているとき、$\boldsymbol{p} = m\boldsymbol{v}$を物体の**運動量**といいます。運動量は速度と同じ向きをもつベクトルです。

物体に力$\boldsymbol{F}$が時間$\Delta t$の間はたらき続けたとき、$\boldsymbol{F}\Delta t$を、その力による**力積**といいます。運動方程式$m\boldsymbol{a}=\boldsymbol{F}$から、次の関係が導けます。

$$m\boldsymbol{v}' - m\boldsymbol{v} = \boldsymbol{F}\Delta t$$

**物体の運動量の変化は、物体が受けた力積に等しくなります。** これを運動量と力積の関係といいます。力が時間的に変化する場合（バットでボールを打つときのように、短時間だけ大きな力がはたらく場合など）も、この関係は成り立ちます。

**例題**：質量$0.5\ \mathrm{kg}$のボールが静止した状態から、力積$4\ \mathrm{kg\cdot m/s}$を受けたときの速さを求める。

$$v = \frac{4}{0.5} = 8\ \mathrm{m/s}$$

## 運動量保存の法則

2つの物体が衝突するとき、それぞれの物体は互いに、作用・反作用の関係にある力を及ぼし合います。2つの物体をまとめて1つの系として考えると、内部で及ぼし合う力（内力）による力積は互いに打ち消し合うため、外から力がはたらかない（または無視できる）限り、衝突の前後で2つの物体の運動量の和は変化しません。

$$m_1\boldsymbol{v_1} + m_2\boldsymbol{v_2} = m_1\boldsymbol{v_1}' + m_2\boldsymbol{v_2}'$$

これを**運動量保存の法則**といいます。台車どうしを衝突させたり、分裂させたりする実験を行うと、外力を無視できる範囲で、衝突（分裂）の前後で運動量の和が変化しないことが確かめられます。

**例題**：質量$2\ \mathrm{kg}$の台車が速さ$3\ \mathrm{m/s}$で、静止した質量$1\ \mathrm{kg}$の台車に衝突し、2台が一体となって動いた（完全非弾性衝突）ときの速さを求める。

$$2\times3 + 1\times0 = (2+1)v \quad\Longrightarrow\quad v = 2\ \mathrm{m/s}$$

## まとめ

運動量は質量と速度の積で表されるベクトル量で、物体が受けた力積の分だけ変化します。互いに力を及ぼし合う物体どうしの系では、外力がなければ運動量の総和は衝突や分裂の前後で保存されます。

## 関連ページ

- [衝突と力学的エネルギー（応用編）](collision-energy.md)
- [運動の法則（応用編）](laws-of-motion.md)
