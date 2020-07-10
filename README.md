[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)
[![Build Status](https://travis-ci.com/lastch/ngx-stack-effects.svg?branch=master)](https://travis-ci.com/lastch/ngx-stack-effects)

# StackEffects

Several Stack Effects in Angular Component.

# [Demo](https://lastch.github.io/ngx-stack-effects/)

- ts
```
import { StackEffects } from 'ngx-stack-effects';
effects = StackEffects;
```

- html
```
<ngx-stack-effects (animationEnd)="animationend($event)" [effect]="effects.SimpleSpread">
    <ngx-stack-effects-item>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSCc-1-He9YYgMnvaP1CawbPxyer3KieXBQR6NW-v0oeQC-f9iU">
    </ngx-stack-effects-item>
    <ngx-stack-effects-item>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTWHh_3hNRDQXa_7Is9_hEvnM85zFM02ooNAr1c8ChDzchBaXek">
    </ngx-stack-effects-item>
    <ngx-stack-effects-item>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRxBQDHi9zMvLgfXApwTSbgSKvh4jph5UtsHZLlawCgT3TxuQqd5w">
    </ngx-stack-effects-item>
    <ngx-stack-effects-item>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSpzqmXFsHKn7e8sgJsHlSULGuRwnGdOEQoe-048Fzry2abvEhv">
    </ngx-stack-effects-item>
    <ngx-stack-effects-item>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSQ4RniQr4e8VL-Lsjj-3qQkAW2x5aZ0upO9EWNDYl3BnR8bf8L">
    </ngx-stack-effects-item>
</ngx-stack-effects>
```

There are several effects in `StackEffects`.
```
export enum StackEffects {
  Fanout = 'fanout',
  SimpleSpread = 'simple_spread',
  RandomRotation = 'random_rotation',
  SideSlide = 'side_slide',
  SideGrid = 'side_grid',
  PeekaBoo = 'peek_a_boo',
  PreviewGrid = 'preview_grid',
  CornerGrid = 'corner_grid',
  BouncyGrid = 'bouncy_grid',
  Coverflow = 'coverflow',
  Leaflet = 'leaflet',
  VerticalSpread = 'vertical_spread',
  ElasticSpread = 'elastic_spread',
  Fan = 'fan',
  Queue = 'queue'
}

```