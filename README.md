# study-react
# 概要
react勉強用

## Goal
- reactの基本概念・動作環境・文法等を把握する
    - reactのtutorialをやる

##js memo
```
JavaScript のクラスでは、サブクラスのコンストラクタを定義する際は常に super を呼ぶ必要があります。constructor を持つ React のクラスコンポーネントでは、すべてコンストラクタを super(props) の呼び出しから始めるべきです。
```

## react memo
```
Square コンポーネントはもう自分で state を管理しないようになったので、Board コンポーネントから値を受け取って、クリックされた時はそのことを Board コンポーネントに伝えるだけになりました。React 用語でいうと、Square コンポーネントは制御されたコンポーネント (controlled component) になったということです。Board が Square コンポーネントを全面的に制御しています。
```
つまり、親コンポーネントが子コンポネーントを制御する