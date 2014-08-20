# hubot-tiqav

tiqav の画像を返す hubot-scripts。

## Configuration

**HUBOT_TIQAV_404_MESSAGE**

画像がない場合に返すメッセージ

**HUBOT_TIQAV_ERROR_MESSAGE**

エラーが発生した場合に返すメッセージ

## Installation

1. `npm install hubot-tiqav --save`
2. "hubot-tiqav" を external-scripts.json に追加
4. Reboot Hubot

## Commands

```
hubot tiqav - tiqav から画像をランダムで返す
hubot tiqav <query> - tiqav から <query> で検索した画像を返す
```
