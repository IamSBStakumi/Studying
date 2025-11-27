# REST の原則

## 概要

Representational State Transfer の略

REST とは Roy Fielding 氏によって提唱されたアーキテクチャスタイルで、
原著では以下の 6 つの原則について述べられている。

- `Client-Server`
- `Stateless`
- `Cacheable`
- `Uniform Interface`
- `Layered System`
- `Code on Demand` (この原則だけ任意とのこと)

ただ、解釈には個人差があるようで、
日本では以下の 4 つの原則として捉えられていることが多い印象。

- アドレス可能性
- 統一インターフェース
- 接続性
- ステートレス性

統一インターフェースやステートレス性の考え方は、両者で共通している。

## 6 原則の詳細

一旦、日本での解釈を優先して調べてみる。

<details>
    <summary>クリックで開く</summary>

### Client-Server

### Stateless

### Cacheable

### Uniform Interface

### Layered System

### Code on Demand

</details>

## 4 原則の詳細

### アドレス可能性

### 統一インターフェース

### 接続性

### ステートレス性

情報のやり取りにおいて状態(= State)を保持せず、
リクエスト/レスポンスはそれぞれ独立した情報を持ち、完結した状態。

基本的にクライアント側で状態を保持し、サーバとのやり取りで必要な情報は
URI と HTTP メソッドだけで表現することが推奨されている。

## 参考文献

1. [AWS RESTful API とは](https://aws.amazon.com/jp/what-is/restful-api/#seo-faq-pairs#what-is-rest)
