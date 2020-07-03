---
tags: 讀書會, CleanCode
---
> - [LearnWeb Taiwan 開源專案](https://github.com/LearnWeb-Taiwan)
> - [LearnWeb Taiwan 臉書社團](https://www.facebook.com/groups/LearnWeb.Taiwan)
> - [LearnWeb Taiwan 即時聊天室](https://gitter.im/LearnWeb-Taiwan/community)
> - [Markdown 教學](https://markdown.tw/)、[LearnWeb Taiwan 簡易版教學](https://hackmd.io/8LoSJ-eNQo-3hrUQvvrGPQ)
---
# Clean Code 導讀：為何我們需要 Clean Code？

## 筆記術，markdown
- [Markdown 教學](https://markdown.tw/)
- [LearnWeb Taiwan 簡易版教學](https://hackmd.io/8LoSJ-eNQo-3hrUQvvrGPQ)

## 讀書會
- 聽到不同的觀點與經驗
- 學習如何分享技術
- 嘗試自己所不會的

## 實體聚會
- 脫離媒介
- 即時交流
- 工作坊

## 讀書會的場次
- 艾賓豪斯的遺忘曲線 Hermann Ebbinghaus
- 不同人導讀，不同角度
- 多場次，避免遺忘

## 如何導讀
- 訂出目標
- 找到問題，如何解決
- 思考尚未釐清的問題
- 不同書籍的比較


## 準備簡報（範例）
- 參考他人的簡報
- 先整理思維再撰寫簡報
- 善用筆記整理 idea
- 去蕪存菁
- 練習展示

## 導讀過程
- 分享自己的心得
- 再補充別人的心得跟觀點
- 交流雙方的意見

## 流程
- 一場 30~60 分鐘
- 互動、討論、工作坊
- 共筆

## 我們為什麼需要 Clean Code?

- 工程師要做什麼？解決問題
- 在意小事，成就大業
- 留意壞味道 Bad Smell
- 無意義的變數名稱
- 缺乏排版

## bad smell sample
```js
a = 3
b = 2

if (b < a){
  doit()
} else
{
  dontdoit()
}

function doit(){
  console.log('success.')
}

function dontdoit(){console.log('failure.')}
```